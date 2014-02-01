Todo lo relacionado con archivos css por favor ponganse en la carpeta
style para tener un estándar de acceso sencillo.

Por favor hagan el css lo mas ordenado posible y por orden de prioridades
en cuanto a los atributos, y en cuanto a bloques de estilos, por
el momento, en orden alfabetico, una herramienta muy buena
que puede hacer ese trabajo por nosotros es CSScomb que se puede
instalar en Sublime Text, el sublime tambien nos puede ordenar los bloques
de codigo css por orden alfabetico de manera muy sencilla, una herramienta realmente poderosa.

La carpeta model,view,controller las usaremos para el patron de disenio
MVC (MODEL,VIEW,CONTROLLER)+(MODELO,VISTA,CONTROLADOR),
por lo tanto los archivos html que son para visualizacion en el navegador, 
por favor ponganlos en la carpeta view.





GIT para carga y actualizacion del repositorio.
===========================================

1) git add . //Para aniadir los cambio al commit

2) git commit -a 
Or
2) git commit -m "texto historia del commit"  

// Para agregar la historia del commit con todos los elementos aniadidos

3) git pull origin master // Para sincronizar el repositorio y actualizarlo en caso de cambios

4) git log // Para ver la historia de commits en caso de cambios para nuestro push, si hay cambios guardamos adecuadamente, y empezamos desde 1), si no continuamos a 5)

5) git push origin master // Para sincronizar el repositorio remoto con nuestros cambios.






Assigner
========


Evitar al maximo el uso de Id como selectores nos dara un buen reciclaje
de codigo css, por favor a la hora de crear una clase nueva
en lo posible usen nombres en ingles y que los nombres hagan referencia a lo
que se van a dedicar, no usen nombres muy cortos, ni abreviaciones, usen 
nombres no muy largos pero si lo suficiente como entender y dar una idea para que son ejemplo:

foo_stl_bottom <-- por favor nombres entendibles y no usen _ Usen - para
separar palabras, la forma correcta para nuestro estandar sera

footer-style-bottom




Documentacion de como usar estilos form.css
=========
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title></title>
	<link rel="stylesheet" href="form.css">
</head>
<body>

	<form>

		<p>Ejemplo uso de las clases con types textuales</p>
		<input type="text" class="field-style">

		<br><br>

		<input type="password" class="field-style" required>

		<br><br>

		<p>Ejemplo uso de las clases con textarea</p>
		<textarea name="" class="field-style"></textarea>

		<br><br>

		<p>Ejemplo uso de las clases con radio button</p>
		<input id = "radio-15" type="radio" name="edad">
		<label for="radio-15" >15</label>
		<input id = "radio-16" type="radio" name="edad">
		<label for="radio-16" >16</label>
		<input id = "radio-25" type="radio" name="edad">
		<label for="radio-25" >25</label>
		<input id = "radio-38" type="radio" name="edad">
		<label for="radio-38" >38</label>
		<input id = "radio-50" type="radio" name="edad">
		<label for="radio-50" >50</label>

		<br><br>

		<p>Ejemplo uso de las clases con checkbox</p>
		<input id = "checkbox-15" type="checkbox" name="edad">
		<label for="checkbox-15" >15</label>
		<input id = "checkbox-16" type="checkbox" name="edad">
		<label for="checkbox-16" >16</label>
		<input id = "checkbox-25" type="checkbox" name="edad">
		<label for="checkbox-25" >25</label>
		<input id = "checkbox-38" type="checkbox" name="edad">
		<label for="checkbox-38" >38</label>
		<input id = "checkbox-50" type="checkbox" name="edad">
		<label for="checkbox-50" >50</label>

	</form>
	
</body>
</html>

===========================================================