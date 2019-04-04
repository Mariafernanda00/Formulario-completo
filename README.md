# Formulario-completo
<!DOCTYPE html>
<html>
<head>
	<meta charset= "utf-8" />
	<title>Formulário</title>
</head>
<body>
<form>
Nome:<input type="text"name="Sobrenome"><br/>
Senha:<input type="password" name="Senha"><br/>
<input type="radio" name="Refeição" value="Almoço">Almoço<br/>
<input type="radio" name"Refeição" value="Janta">Janta<br/>
<input type="checkbox" name="Complementos" value="Refrigerante">Refrigerante<br/>
<input type="checkbox" name="Complementos" value="Molho">Molho<br/>
<input type="submit" value="Submit">
</form>
<select name="Prato principal">
<optgroup label="Massas">
<option value="1">Estrogonofe</option>
<option value="2">Lasanha</option>
</optgroup>
<option value="3" selected>Churrasco</option>
<option value="4">Salada</option>
</select> <br/>
<textarea rows="10" cols="30">
Perguntar se o cliente quer sobremesa
</textarea><br/>
<input type="button" value="Finalizar venda">
</form>
