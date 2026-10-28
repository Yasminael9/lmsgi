#Hola.html

Yasmina El Masoudi

##Enuciado

Creamos un código html y lo abrimos con xampp desde un navegador web

##Solución

```html

<html>
	<head>
	</head>
	<body>
		Ejemplo de formulario:<br>
		<form action="procesar_formulario.php" method="<?php
		var_dump($_REQUEST);?>">
		<label>Nombre: </label><input type="text" name ="nombre" /><br>
		<label>Apellido 1: </label><input type="text" name="apellido1" /><br>
		<label>Apellido 2: </label><input type="text" name="apellido2"/><br>
		<input type="submit"/>
		</form>
	</body>
</html>

```
