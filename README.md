<!DOCTYPE html>
<html>
<head>

    <title>Formulário de cadastro</title>
</head>
<body     bgcolor="#daa520">
  <style>

    input[type=text] {
  width: 20%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
}
input[type=tel] {
  width: 10%;
  padding: 8px 15px;
  margin: 8px 0;
  box-sizing: border-box;
}
select {
  width: 10%;
  padding: 16px 20px;
  border: none;
  border-radius: 4px;
  background-color: white;
}
input[type=submit], input[type=reset] {
  background-color: #04AA6D;
  border: none;
  color: white;
  padding: 16px 32px;
  margin: 4px 2px;
  cursor: pointer;
}
input[type=email] {
  width: 10%;
  padding: 8px 12px;
  margin: 8px 0;
  box-sizing: content-box;
}
p {
  font-family: Arial, Helvetica, sans-serif;
  font-size: larger;
  font-style: italic;
  
}

  </style>
    
    <h1> Cadastre  time para a copinha Tocantins 2023</h1>

    <p> Todos os times precisam ter seus próprios uniformes com numeração e o nome dos jogadores estampados.</p>
    <p> Ocorrerá do dia 20/07/2023 á 17/08/2023 </p>
    
    <form>
        
      <label for="text"> Nome do Clube: </label> 
         <br>
           <input type="text" id="clube" 
            name="clube"> 
         <br>
         <br>         
        
         <label for="text"> Cidade: </label>
        <br> 
           <input type="text" id="cidade"
            name="cidade"> 
          <br>
          <br>
          
          <label for="text"> Estado: </label>
          <br>
            <input type="text" id="Estado"
             name="Estado">     
    
      
        <p> Copinha 2023 terá 3 divisões,oportunidade para atletas de todas as idades.</p>
        <p> Informe aqui a <strong> divisão </strong> que seu time se enquadra:</p>
     
      <br>
    <form>
     
      <input type="radio" id="divisao" name="categoria" value="Sub-14">
       <label for="radio"> Sub-14 (2009)   </label> 
      
    <br>
    <br>
      <input type="radio" id="divisao"  name="categoria" value="Sub-18"> 
       <label for="radio"> Sub-18 (2005)   </label> 
    
    <br>
    <br>
      
     <input type="radio" id="divisao"  name="categoria" value="+21"> 
       <label for="radio"> Atletas de 21+ (sem limite de idade) </label>
    <br>
    <br>
    
    <p> Disponibilidade para os jogos: </p>
      <input type="checkbox" id="dias" name="disponibilidade" value="Quinta-feira">
     <label for="checkbox">  Quinta-feira  </label> 

      <input type="checkbox" id="dias" name="disponibilidade" value="Sexta-feira">
     <label for="checkbox">  Sexta-feira  </label>

      <input type="checkbox" id="dias" name="disponibilidade" value="Sábado">
     <label for="checkbox">  Sábado  </label>
    
      <input type="checkbox" id="dias" name="disponibilidade" value="Domingo">
     <label for="checkbox">  Domingo </label>
       <br>
       <br>

    <p> Coloque um  <strong> telefone </strong> para contato: </p>
       
       <label for="fone">Celular com DDD: </label>
	<input type="tel" id="fone" name="fone" required pattern="[0-9]{2} [0-9]{5}-[0-9]{4}" placeholder="11 99999-9999">
 <br>
 <br>
  
 <label for="jogadores">Númro de jogadores: </label>
	 <select id="jogadores" name="jogadores">
		 <option value="12-15(minimo)">12-15 (minimo)</option>
		  <option value="16-21">16-21</option>
		   <option value="22(maximo)">22 (máximo)</option>
   </select>
 
   <br>
 
   <P> Coloque um  <strong> e-mail </strong> para receber mais informações: </P>  
   <label for="email">Email</label>
	   <input type='email' id='email' name='email' required>
  <br>
  <br> 
   
  <input type="submit" value="Enviar">
   <input type="reset" value="Resetar">

  </form>
</body>
</html>
