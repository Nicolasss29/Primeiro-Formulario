<html lang "pt-br"> 
<head>
<title>Cadastro</title>
<meta charset="UTF-8">
</head>
<body>
<h1><b><i>Cadastro</h1></b></i>
<br>
<div class = "box">
	<form action="gravarCliente.php" 
		  method="post"
		  enctype="multipart/form-data">
		  <fieldset>
<label for = "nome"><b>Nome:</b></label> 
<div class ="inputBox">
<input      type = "text"
			name = "nome"
			maxlength= "50"
			size = "50"	
			placeholder = "Digite seu nome"
			class = "inputUser"></div>
<br>
<label for ="data_nascimento"><b>Data de nascimento:</b></label> 
<div class ="inputBox">
<input      type = "date"
            name = "nascimento"
			id = "data_nascimento"
			class = "inputUser"
			placeholder = "aaaa - mm - dd"
            ></div>
<br>
<div class ="inputBox">
<label for ="genero"><b>Sexo:</b></label>
<input type = "radio" name ="genero" id = "masculino" value = "M" required>
<label for ="masculino">Masculino</label>
<input type = "radio" value = "F" name = "genero" id = "feminino" required> 
<label for ="feminino">Feminino</label>
</div>
<br><br>
<div class ="inputBox">
<label for ="eCivil"><b>Estado Civil:</b></label>
<select name = "eCivil">
<option>Escolha</option>
<option value =	"S">Solteiro</option>
<option value =	"C">Casado</option>
<option value =	"SE">Separado</option>
<option value =	"D">Divorciado</option>
<option value =	"V">Viúvo</option>
</select>
</div>
<br>
<h1><b><i>Dados para contato</h1></b></i>
<br><br>
<div class ="inputBox">
<label for = "email"><b>E-mail:</b></label>
<input type ="email"
       name = "email"
       maxlength="50"
       placeholder="Até 50 caracteres"
	   size="50">
	  </div> 
<br><br>
<div class ="inputBox">
<input type="checkbox" 
       name="rEmail" 
       value="1">Deseja receber e-mails
</div>
<br><br>
<div class ="inputBox">
<label for = "tel1"><b>Telefone:</b></label>
(<input type = "tel"
       name = "dd1"
	   maxlength="2"
	     size="2">)	 
<input type = "tel"
       name = "tel1"
	   maxlength="9"
	     size="9"
		 >
<label for ="tipo1"><b>Tipo:</b></label>
<select name = "tipo1" >
<option value =	"a"> </option>
<option value =	"R">Residencial</option>
<option value =	"C">Celular</option>
<option value =	"CO">Comercial</option>
<option value =	"RC">Recados</option>
</select>
</div>
<br>
<div class ="inputBox">		 
<label for = "tel2"><b>Telefone:</b></label>
(<input type = "tel"
       name = "dd2"
	   maxlength="2"
	     size="2">) 
<input type = "tel"
       name = "tel2"
	   maxlength="9"
	   size="9">
	   <label for ="tipo2"><b>Tipo:</b></label>
<select name = "tipo2">
<option value =	"a"> </option>
<option value =	"R">Residencial</option>
<option value =	"C">Celular</option>
<option value =	"CO">Comercial</option>
<option value =	"RC">Recados</option>
</select>
</div>
<br>
<div class ="inputBox">
<label for = "tel3"><b>Telefone:</b></label>
(<input type = "tel"
       name = "dd3"
	   maxlength="2"
	     size="2">)	 
<input type = "tel"
       name = "tel3"
	   maxlength="9"
	   size="9">
	   <label for ="tipo3"><b>Tipo:</b></label>
<select name = "tipo3">
<option value =	"a"> </option>
<option value =	"R">Residencial</option>
<option value =	"C">Celular</option>
<option value =	"CO">Comercial</option>
<option value =	"RC">Recados</option>
</select>
</div>
<hr>
<div class ="inputBox">
<label for ="observacoes"><b>Observações</b></label>
<br>
<textarea name="observacoes" rows="5" cols="80" placeholder = "Digite sua observação aqui"re></textarea>
<br>
</div>
<div class ="inputBox">
<input type="submit" value="Enviar dados">
</div>
</form>
</fieldset>
</body>

</html>
