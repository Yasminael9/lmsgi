#Libros

Yasmina El Masoudi

##Enunciado

Crea un código html de una libreria y abrelo con xampp en un navegador web

##Solución

```html

<DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="utf-8 "/>
	</head>
	<body> 
		<form action="Libros.php" method="get">
			<fieldset>
				<legend>Libros</legend>
				<label>Título:</label><input type="text" name="titulo"><br>
				<label>Género:</label>
				<label>Acción</label><input type="checkbox" name="género" value="acción">
				<label>Aventura</label><input type="checkbox" name="género" value="aventura">
				<label>Drama</label><input type="checkbox" name="género" value="drama">
				<label>Romance</label><input type="checkbox" name="género" value="romance">
				<label>Terror<input type="checkbox" name="género" value="terror">
				<label>Educativo</label><input type="checkbox" name="género" value="educativo">
				<label>Misterio</label><input type="checkbox" name="género" value="misterio"><br>
				<label>Tamaño:</label>
				<label>Bolsillo</label><input type="radio" name="tamaño" value="bolsillo">
				<label>Estándar</label><input type="radio" name="tamaño" value="estándar">
				<label>Educativo</label><input type="radio" name="tamaño" value="educativo">
				<label>Ilustrado</label><input type="radio" name="tamaño" value="ilustrado"><br>
				<label>Encuadernacción:</label>
				<label>Tapa blanda</label><input type="radio" name="encuadernacción" value="tapa_blanda">
				<label>Tapa dura</label><input type="radio" name="encuadernacción" value="tapa_dura">
				<label>Espiral</label><input type="radio" name="encuadernacción" value="espiral">
				<label>Grapa</label><input type="radio" name="encuadernacción" value="grapa"><br>
			</fieldset>
			<input type="reset"/>
			<input type="submit"/>
		</form>
	</body>
</html>


```
