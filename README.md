<!DOCTYPE html>
<html lang="PT-BR">

<head>
    <Title>Projeto</Title>
    <link rel="stylesheet" href="style.css">
</head>

    <body>
        <h1>Kraft Papéis</h1>
    <main>

body{background:linear-gradient(#000000,#333333,#f0f0f0,#ffffff);
     min-height:100vh;
     text-align:center;}

h1{color: #f0f0f0;}

main{display:flex;
     justify-content:center;
     align-items:center;}
     
fieldset{display:flex;
         flex-direction:column;
         gap:10px;
         width:300px;
         padding:20px;}

legend{font-size:100%;
       font-family:sans-serif;
       color:#ffffff;}

label{font-family:sans-serif;
      color:#ffffff;}

input{padding:8px;}

button{width:300px;
       height:50px;
       margin:8px;
       border-radius:50px;
       background:linear-gradient(red, purple,blue);
       color:white;
       border:none;
       cursor:pointer;
       font-size:18px;}

<article>
<form action="/action_page.php"method="POST">

<fieldset>
            <legend><strong>Cadastre-se</strong></legend>
        <label for="fname">Primeiro Nome:</label>
            <input type="text" id="fname" name="fname" required>
        <label for="fname">CNPJ:</label>
            <input type="txt" id="CNPJ" name="CNPJ" required>
        <label for="fname">E-mail:</label>
            <input type="txt" id="E-mail" name="E-mail" required>
        <label for="fname">Telefone:</label>
            <input type="txt" id="Telefone" name="Telefone" required>
        <button>Enviar</button>
         </fieldset>
</form>
</article>
</main>
</body>     
</html>
