<!DOCTYPE html>
<html lang="en">
  
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="cadastrocss.css">
    <title>Document</title>
</head>
<style>
  #informações {

font-family:Arial, Helvetica, sans-serif;
font-size: 15px;

} 
img {
  width: 20%;
  margin: auto;
  display: block;
}
#titulo {

    font-family:Arial, Helvetica, sans-serif;
    margin: 40px auto; max-width: 400px;

}

#body {
    
background-color: #87CEEB;


}
h1 {
  font-family: 'Times New Roman', Times, serif;
  align-items: center;
}
fieldset{

   background-color: white;
    border-radius: 20px;
    border: 0;
    margin: auto;
    width: 30%;
    text-align: center;
}
</style>

<body id="body">
  <h1 align=" center"> 
    Academia Malho pra comer 
              </h1>

<img src="academia 1.png" align="midddle">
 


    <fieldset>
    <form >
        <h1>Inscrever-se</h1>
        <div>
            <label for="nome">Nome:</label> <br>
            <input type="text" name="Nome" placeholder="Digite seu nome" id="informações">
        </div>

        <br>

        <div>
            <label for="telefone">Telefone:</label> <br>
<input type="tel" id="telefone" class="input-padrao" required placeholder="(xx) xxxxx-xxxx">
        </div>

        <br>

        <div>
            <label for="e-mail">E-mail:</label> <br>
            <input type="email" name="Email" placeholder="Insira seu E-mail" id="informações">
        </div>

        <div>
            
        </div>
        <h4>Data de nascimento</h4>

        <div>
            <input type="date">
        </div>

        <h4>Gênero</h4>
        <div>
            <select name="gênero" id="">
                <option selected disabled value="">Selecione</option>
                <option value="Masculino">Masculino</option>
                <option value="Feminino">Feminino</option>
                <option value="Prefiro não dizer">Prefiro não dizer</option>
            </select>
        <br>
        <br>
        <div>
                <input type="checkbox" id="aceitar" value="aceitar">
                <label for="aceitar">Desejeo receber novidades e promoções da academia por e-mail.</label>
        </div>
        </div>
        <br>
        <button>Matricular</button>        
    </form>
    </fieldset>
</body>
</html>
