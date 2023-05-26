<html>
     <head>
    <title>Form Contato</title>
     </head>

     <style>
       *{margin: 0;padding: 0;box-sizing: border-box;}
       body{
            background-color:#5F7C8A;
       } 

       form{
        background-color: white ;
        max-width: 500px;
        width: 70%;
        padding: 20px;
        position:absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%,-50%);
       }
       form h3{
            text-align: center;
            color:#5F7C8A;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif ;
       }

      
       form input[type=text],
       form input[type=password]{
        width: 100%;
        height: 45px;
        border: 1px solid #ccc;
        padding-left: 10px;
        margin:10px 0;
    }

    form input[type=submit]{
        width: 100%;
        height: 40px;
        cursor: pointer;
        background: #5F7C8A;
        color: white;
        border: 0;
        border-radius: 20px;
        transition: 1s;
    }

    form input[type=submit]:hover{
        background-color: #4A5F6A;
    }
    form input[type=text];:focus{
        outline: 0;
    }
    form input[type=text];focus{
        outline: 0;
    }
    </style>

    <body>
        <form>
            <h3>Login</h3>
            <input id="email" type="text" name="email" placeholder="Seu e-mail..." />
            <input type="password" name="senha" placeholder="Sua senha..." />
            <input type="submit" name="acao" value="Enviar" />
        </form>
        <script>
            var email = document.getElementById('email');

          email.addEventListener('focus',()=>{
                    email.style.borderColor = "#4A5F6A";
          });
          email.addEventListener('blue')

        </script>
    </body>
</html>
