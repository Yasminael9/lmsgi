# Elementos_de_formularios.html

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
		<form action="Elementos de formularios.php" method="get">
		<label>Elementos de formularios</label>
		<label>Nombre:</label><input type="button" name="nombre"><br>
		<label>Apellidos:</label><input type="url" name="apellido"><br>
		<label>eMail:</label><input type="text" name="eMail" maxlength="50"><br>
		<label>Sexo:</label>
		<label>Hombre</label><input type="email" name="sexo" method="hombre">
		<label>Mujer</label><input type="file" name="sexo" method="mujer">
		<label>NSNC</label><input type="radio" name="sexo" method="nsnc"><br>
		<label>Fecha de nacimiento</label><input type="date" name="fnac">
		<label>Transporte</label>
		<label>Coche</label><input type="hidden" name="transporte" method="coche">
		<label>Moto</label><input type="checkbox" name="transporte" method="moto"><br>
		<label>Color favorito</label><input type="color" name="color_favorito"><br>
		<input type="reset">	
		<input type="submit">
		</form>
	</body>
</html>

```
