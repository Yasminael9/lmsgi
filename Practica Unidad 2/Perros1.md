#Perros1

Yasmina El Masoudi

##Enunciado

Crea un formulario de una veterinaria y abrelo con xampp en un navegador web

##Solución

```html

<DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="utf-8"/>
	</head>
	<body>
		<h1>Perrunos y ceros</h1>
		<form action="perrunos_y_ceros.php" method="get"><br>
			<label>Nombre:</label><input type="text" name="nombre"><br>
			<label>Apellido:</label><input type="text" name="apellido"><br>
			<label>DNI:</label><input type="text" name="DNI"><br>
			<label>Tipo: </label>
			<label>Perro</label><input type="radio" name="mascota" value="perro">
			<label>Gato</label><input type="radio" name="mascota" value="gato"><br>
			
			<fieldset><legend>Color: </legend >
			<label>Negro</label><input type="checkbox" name="color" value="negro">
			<label>Blanco</label><input type="checkbox" name="color" value="blanco">
			<label>Gris</label><input type="checkbox" name="color" value="gris">
			<label>Café</label><input type="checkbox" name="color" value="café">
			<label>Naranja</label><input type="checkbox" name="color" value="naranja"><br>
			</fieldset>
			<input type="submit"/>
			<input type="reset"/>
		</form>
	</body>
</html>

```
