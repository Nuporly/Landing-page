> Landing-page - interação de login com usuário. 

   > Utilizado Linguagens de programação HTML CSS e HTML

      
      
      
      
   CSS

 <style>
        body {
            font-family: Arial, Arial, Helvetica, sans-serif;
            background-image: linear-gradient(45deg, red, yellow);
        }

        div {
            background-color: rgba(0,0, 0, 0.9 );
            position: absolute;
            top: 200px;
            left: 550px;
            transform: translate (-50%,-50%);
            padding: 80px;
            border-radius: 15px;
            color: #ffff;
        }
        input{
            padding: 15px;
            border: none;
            outline: none; 
            font-size: 15px;
        }

        button {
            background-color: dodgerblue;
            border: none;
            padding: 15px;
            width: 100%;
            border-radius: 10px;
            font-size: 15px;
            color: white;
            cursor: pointer;
        }
        button:hover{
            background-color: deepskyblue;
        

        }
    </style>







HTML

<body>
    <div class="tela-de-login">
        <h1> Login</h1>
        <input type="text" placeholder="Nome">
        <br><br>
        <input type="password" placeholder="Senha">
        <br><br>
  
        <button> Enviar</button>
    </div>
    
</body>
