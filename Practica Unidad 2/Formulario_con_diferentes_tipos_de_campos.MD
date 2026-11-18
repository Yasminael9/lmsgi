# Formulario_con_diferentes_tipos_de_campos.html

Yasmina El Masoudi

## Enuciado

Creamos un código html y lo abrimos con xampp desde un navegador web

## Solución

```html

<DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="utf-8"/>
	</head>
	<body>
		<form action="Formulario_con_diferentes_tipos_de_campos.php" method="get">
		<h1 center>Formulario con diferentes tipos de campos</h1><br>
		<label>Nombre:</label><input type="text" name="nombre"/><br>
		<label>Apellidos:</label><input type="text" name="apellido"/><br>
		<label>e-mail:</label><input type="email" name="e-mail"/><br>
		<label>Contraseña</label><input type="password" name="contraseña"/><br>
		<table>
			<thead></thead>
			<tbody>
				<tr>
				<td>Sexo:</td>
				<td>Profesión:</td>
				<td>Aficiones:</td>
				<td rowspan="2">Elija la herramienta de diseño web que prefiera:</td>
				</tr>
				<tr>  
				<td><input type="radio" name="sexo" method="hombre"/><label>Hombre</label></td>
				<td><input type="radio" name="profesión" method="profesor"/><label>Profesor</label></td>
				<td><input type="checkbox" name="aficiones" method="ciencia"/><label>Ciencia</label></td>
				</tr>
				<tr>
				<td><input type="radio" name="sexo" method="mujer"/><label>Mujer</label></td>
				<td><input type="radio" name="profesión" method="programador"/><label>Programador</label></td>
				<td><input type="checkbox" name="aficiones" method="libros"/><label>Libros</label></td>
				<td rowspan="2"><select name="elija_la_herramienta_de_diseño_web_que_prefiera"/></td> 
				</tr>
				<tr>
				<td></td>
				<td><input type="radio" name="profesión" method="diseñador_gráfico"/><label>Diseñador gráfico</label></td>
				<td><input type="checkbox" name="aficiones" method="deportes"/><label>Deportes</label></td>
				</tr>
			</tbody>
			<tfoot></tfoot>
		</table>
		<label>Indique sus comentarios:</label><br><textarea>Comentario:</textarea><br>
		<input type="submit"/>
		<input type="reset"/>
		</form>
	</body>
</html>

```
