# Mola.html

Yasmina El Masoudi

## Enunciado

Crear un formulario

## Solución

```html

<DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="utf-8"/>
		<title>Mi Formulario</title>
	</head>
	<body>
		<form action="procesar_formulario.php" method="post">
			<fieldset>
				<legend>Datos:</legend>
				<label for="nombre">Nombre:</label><input type="text" name="nombre"/><br>
				<label for="apellido">Apellido:</label><input type="text" name="apellido"/><br>
				<!--  Comentario de linea    -->
				<label >Sexo:&nbsp;&nbsp;</label>
				<input type="radio" name="sexo" id="sexo_mujer"/><label for="sexo">Mujer</label>
				<input type="radio" name="sexo" id="sexo_hombre"/><label for="sexo_hombre">Hombre</label>
				<input type="radio" name="sexo" id="sexo_terian"/><label for="sexo_terian">Terian</label>
				<input type="radio" name="sexo" id="sexo_otro"/><label for="sexo_otro">Otro</label><br>
				
				<label for="email">eMail:</label><input type="email" name="email"/><br>
				<label for="contraseña">Contraseña:</label><input type="password" name="contraseña"/><br>
				
				<label for="fnac">Fecha de nacimiento:</label><input type="date" name="fnac"/><br>
				
				<label for="avatar">Avatar:</label><input type="file" name="avatar" accept=".jpg"/>
				
			</fieldset>
			<input type="reset"/>
			<input type="submit"/>
		</form>
	</body>
</html>
```
