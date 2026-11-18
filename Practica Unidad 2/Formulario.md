# Formulario.html

Yasmina El Masoudi

## Enuciado

Creamos un código html y lo abrimos con xampp desde un navegador web

## Solución

```html

<DOCTYPE hhtml>
<html lang="es">
	<head>
		<meta charset="utf-8"/>
	</head>
	<body>
		<form action="Formulario_de_contacto.php" method="get">
		<label>Formulario de contacto</label>
		<label>Nombre:</label><input type="text" name="nombre"><br>
		<label>Apellidos:</label><input type="text" name="apellido"><br>
		<label>eMail:</label><input type="text" name="eMail" maxlength="50"><br>
		<label>Sexo:</label>
		<label>Hombre</label><input type="radio" name="sexo" method="hombre">
		<label>Mujer</label><input type="radio" name="sexo" method="mujer">
		<label>NSNC</label><input type="radio" name="sexo" method="nsnc"><br>
		<label>Fecha de nacimiento</label><input type="date" name="fnac">
		<label>Transporte</label>
		<label>Coche</label><input type="checkbox" name="transporte" method="coche">
		<label>Moto</label><input type="checkbox" name="transporte" method="moto"><br>
		<label>Color favorito</label><input type="color" name="color_favorito"><br>
		<input type="reset">	
		<input type="submit">
		</form>
	</body>
</html>

```
