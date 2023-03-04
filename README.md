
## Tutorial para Desarrollo en HTML5 - CSS3 y JavaScript
# Día 1

Introducción a HTML5 HTML (HyperText Markup Language) es un lenguaje de marcado utilizado para crear páginas web. HTML5 es la última versión del lenguaje y proporciona nuevas características y mejoras. En este primer día, aprenderás lo básico de HTML5.

Una etiqueta en HTML5 es una unidad básica de código que define la estructura y el contenido de una página web. Las etiquetas se utilizan para crear elementos como encabezados, párrafos, imágenes, formularios y enlaces, entre otros.


HTML (HyperText Markup Language) es un lenguaje de marcado que se utiliza para crear páginas web. En su última versión, HTML5, se han introducido nuevas características y mejoras que permiten una mayor flexibilidad y facilidad de uso en el diseño de páginas web.

HTML5 incluye nuevas etiquetas que permiten la creación de contenido multimedia, como la etiqueta de video y audio, que permiten la incorporación de videos y audios directamente en las páginas web sin necesidad de plug-ins adicionales. Además, HTML5 también ofrece nuevas formas de crear formularios, incluyendo opciones para la validación de campos y la selección de fechas.

Otra de las características destacadas de HTML5 es su capacidad para crear listas ordenadas y no ordenadas de forma más fácil y con una mayor flexibilidad en su diseño y presentación.

En resumen, HTML5 ofrece una serie de nuevas características y mejoras que hacen que la creación de páginas web sea más fácil y eficiente. Con su uso, se pueden crear páginas web más interactivas, atractivas y accesibles para el usuario.
## A continuación, se muestran algunas de las etiquetas más comunes en HTML5 y su propósito:

-	<html>: Define el inicio y fin del documento HTML.
-	<head>: Define la sección de encabezado del documento HTML.
-	<title>: Define el título del documento HTML.
-	<body>: Define el cuerpo del documento HTML.
-	<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Define encabezados de diferentes tamaños y niveles de importancia.
-	<p>: Define un párrafo.
-	<img>: Define una imagen.
-	<a>: Define un enlace.
-	<ul>, <ol>, <li>: Define listas sin ordenar, listas ordenadas y elementos de lista, respectivamente.
-	<form>, <input>, <label>, <button>: Define un formulario y sus elementos, como campos de entrada de texto, etiquetas y botones.
-	<div>, <span>: Define contenedores genéricos para organizar y dar formato al contenido.
-	<table>, <tr>, <th>, <td>: Define una tabla y sus elementos, como filas, encabezados de columna y celdas.

Es importante tener en cuenta que HTML5 es una especificación en constante evolución, por lo que pueden existir nuevas etiquetas en el futuro. Además, es posible que algunas etiquetas se vuelvan obsoletas o dejen de ser compatibles con los estándares actuales. Por lo tanto, es importante mantenerse actualizado en las últimas tendencias y estándares en el desarrollo web.



## Ejercicio No. 1

Crea una página web básica usando HTML5. Incluye una estructura básica, títulos, párrafos, imágenes y enlaces.

```html
 <!DOCTYPE html>
<html>
<head>
	<title>Mi primera página web</title>
</head>
<body>
	<h1>Bienvenido a mi sitio web</h1>
	<p>Este es un sitio web básico.</p>
	<img src="imagen.jpg" alt="Una imagen">
	<a href="https://www.google.com">Ir a Google</a>
</body>
</html>

```

## Día 2

Avanzando en HTML5 En este día, aprenderás sobre las características más avanzadas de HTML5, como la creación de formularios, la inclusión de videos y audios, y la creación de listas.

HTML5 es una versión mejorada del lenguaje de marcado de hipertexto, HTML, que introduce nuevas características y funcionalidades que facilitan la creación de contenido web moderno y rico en multimedia. En este día de aprendizaje, se explorarán algunas de las características avanzadas de HTML5, como la creación de formularios, la inclusión de videos y audios, y la creación de listas.

Una de las características más útiles de HTML5 son los formularios avanzados, que permiten a los usuarios interactuar con el contenido de manera más eficiente. Estos formularios pueden incluir campos de entrada de texto, botones de radio, casillas de verificación, menús desplegables, calendarios y mucho más. Además, HTML5 introduce nuevos tipos de entrada de formulario, como los campos de búsqueda, las entradas de correo electrónico y las entradas de teléfono, lo que permite una experiencia de usuario más intuitiva y mejorada.

Otra característica avanzada de HTML5 es la capacidad de incluir videos y audios en el contenido de la página web. Esto se logra mediante la etiqueta de video y la etiqueta de audio, respectivamente. Estas etiquetas permiten a los desarrolladores web incrustar videos y audios en el contenido de la página web de manera más fácil y accesible para el usuario final.

Por último, HTML5 también ofrece características avanzadas para la creación de listas, como la lista de definiciones, la lista de términos y la lista de tareas. Estas listas se pueden utilizar para organizar el contenido de la página web de manera más efectiva, lo que permite una mejor accesibilidad y experiencia de usuario.

En resumen, HTML5 es una versión mejorada del lenguaje de marcado de hipertexto que ofrece muchas características avanzadas para la creación de contenido web moderno y rico en multimedia. Algunas de estas características incluyen formularios avanzados, inclusión de videos y audios, y la creación de listas. Con HTML5, los desarrolladores web pueden crear experiencias de usuario más intuitivas y mejoradas para el contenido de sus páginas web.
## Ejercicio No. 2

Crea un formulario de contacto utilizando HTML5. Incluye campos para el nombre, correo electrónico, mensaje y un botón de envío. También agrega un video y un audio a la página.

```html
 <!DOCTYPE html>
<html>
<head>
	<title>Formulario de contacto</title>
</head>
<body>
	<h1>Contacto</h1>
	<form>
		<label for="name">Nombre:</label>
		<input type="text" id="name" name="name"><br>

		<label for="email">Correo electrónico:</label>
		<input type="email" id="email" name="email"><br>

		<label for="message">Mensaje:</label>
		<textarea id="message" name="message"></textarea><br>

		<input type="submit" value="Enviar">
	</form>

	<video controls>
		<source src="video.mp4" type="video/mp4">
		<source src="video.ogg" type="video/ogg">
		Tu navegador no soporta videos.
	</video>

	<audio controls>
		<source src="audio.mp3" type="audio/mp3">
		<source src="audio.ogg" type="audio/ogg">
		Tu navegador no soporta audios.
	</audio>
</body>
</html>


```
## Dia 3
Introducción a CSS3 CSS (Cascading Style Sheets) es un lenguaje de hojas de estilo utilizado para dar estilo a páginas web. CSS3 es la última versión del lenguaje y proporciona nuevas características y mejoras. En este tercer día, aprenderás los conceptos básicos de CSS3.

CSS (Cascading Style Sheets) es un lenguaje utilizado para dar estilo a páginas web escritas en HTML. Con CSS, los diseñadores pueden controlar el diseño, la presentación y la apariencia visual de un sitio web. CSS3 es la última versión del lenguaje y ha introducido muchas características avanzadas que permiten a los diseñadores crear diseños más sofisticados y animaciones.

Una de las principales características de CSS3 es la capacidad de aplicar estilos y efectos a elementos individuales de una página web. Esto se logra mediante la creación de selectores que apuntan a elementos específicos del código HTML. Por ejemplo, los selectores pueden apuntar a elementos específicos de un menú de navegación o a una imagen en particular.

Otra característica interesante de CSS3 es la capacidad de crear transiciones y animaciones. Con CSS3, los diseñadores pueden crear efectos de transición suaves y animaciones dinámicas que hacen que las páginas web parezcan más interactivas y atractivas.

CSS3 también ha mejorado la capacidad de diseño responsivo, lo que significa que los sitios web pueden adaptarse y ajustarse automáticamente a diferentes tamaños de pantalla. Esto es especialmente importante en la era actual de dispositivos móviles, ya que las personas acceden a los sitios web desde una amplia variedad de dispositivos con diferentes tamaños de pantalla.

En general, CSS3 ha mejorado en gran medida la capacidad de los diseñadores para crear diseños de alta calidad y visualmente atractivos para sitios web. Con su amplia gama de características y mejoras, CSS3 es una herramienta esencial para cualquier diseñador web que desee crear sitios web modernos y profesionales.
## Ejercicio No. 3

Crea una página web utilizando HTML5 y agrega estilos utilizando CSS3. Cambia el color de fondo, el color del texto y los márgenes.

```html
 <!DOCTYPE html>
<html>
<head>
	<title>Mi primera página con estilos</title>
	<style>
		body {
			background-color: #F5F5F5;
			color: #333;
			margin: 20px;
		}
	</style>
</head>
<body>
	<h1>Bienvenido a mi sitio web</h1>
	<p>Este es un sitio web básico.</p>
	<img src="imagen.jpg" alt="Una imagen">
	<a href="https://www.google.com">Ir a Google</a>
</body>
</html>



```
## Dia 4

Avanzando en CSS3 En este día, aprenderás sobre las características más avanzadas de CSS3, como las animaciones, las transformaciones y las transiciones.


## Ejercicio No.4

Agrega una animación a una imagen utilizando CSS3. También agrega una transformación y una transición.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Animación con CSS3</title>
	<style>
		img {
			transition: transform 0.5s;
		}

		img:hover {
			transform: rotate(360deg);
		}
	</style>
</head>
<body>
	<h1>Bienvenido a mi sitio web</h1>
	<img src="imagen.jpg" alt="Una imagen">
</body>
</html>




```
## Dia 5

Introducción a JavaScript JavaScript es un lenguaje de programación utilizado para crear interactividad en páginas web. En este quinto día, aprenderás los conceptos básicos de JavaScript.


## Ejercicio No. 5

Agrega un botón a tu página web y crea una función que se ejecute cuando el usuario haga clic en el botón.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Botón con función en JavaScript</title>
	<script>
		function mostrarMensaje() {
			alert("¡Hola! Bienvenido a mi sitio web.");
		}
	</script>
</head>
<body>
	<h1>Bienvenido a mi sitio web</h1>
	<button onclick="mostrarMensaje()">Haz clic aquí</button>
</body>
</html>




```
## Dia 6

Avanzando en JavaScript En este día, aprenderás sobre las características más avanzadas de JavaScript, como los eventos, los arrays y las funciones.

## Ejercicio No. 6

Agrega una función que muestre un mensaje de alerta cuando el usuario haga clic en un enlace. También agrega un array y una función que itere sobre el array y muestre sus elementos.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Calculadora en JavaScript</title>
	<script>
		function sumar() {
			var num1 = parseInt(document.getElementById("num1").value);
			var num2 = parseInt(document.getElementById("num2").value);
			var resultado = num1 + num2;
			document.getElementById("resultado").innerHTML = resultado;
		}

		function restar() {
			var num1 = parseInt(document.getElementById("num1").value);
			var num2 = parseInt(document.getElementById("num2").value);
			var resultado = num1 - num2;
			document.getElementById("resultado").innerHTML = resultado;
		}

		function multiplicar() {
			var num1 = parseInt(document.getElementById("num1").value);
			var num2 = parseInt(document.getElementById("num2").value);
			var resultado = num1 * num2;
			document.getElementById("resultado").innerHTML = resultado;
		}

		function dividir() {
			var num1 = parseInt(document.getElementById("num1").value);
			var num2 = parseInt(document.getElementById("num2").value);
			var resultado = num1 / num2;
			document.getElementById("resultado").innerHTML = resultado;
		}
	</script>
</head>
<body>
	<h1>Calculadora</h1>
	<label for="num1">Número 1:</label>
	<input type="number" id="num1"><br>

	<label for="num2">Número 2:</label>
	<input type="number" id="num2"><br>

	<button onclick="sumar()">Sumar</button>
	<button onclick="restar()">Restar</button>
	<button onclick="multiplicar()">Multiplicar</button>
	<button onclick="dividir()">Dividir</button>

	<p>Resultado: <span id="resultado"></span></p>
</body>
</html>




```
## Dia 7

Integración de HTML5, CSS3 y JavaScript En este séptimo día, aprenderás a integrar HTML5, CSS3 y JavaScript para crear páginas web interactivas y dinámicas.


## Ejercicio No. 7

Crea una página web utilizando HTML5, CSS3 y JavaScript. Agrega un formulario de contacto con validación de campos y una animación que se active cuando el usuario haga clic en el botón de envío.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Botón con función en jQuery</title>
	<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
	<script>
		$(document).ready(function() {
			$("button").click(function() {
				alert("¡Hola! Bienvenido a mi sitio web.");
			});
		});
	</script>
</head>
<body>
	<h1>Bienvenido a mi sitio web</h1>
	<button>Haz clic aquí</button>
</body>
</html>





```
## Dia 8

Proyecto final En este último día, tendrás la oportunidad de aplicar todo lo que has aprendido en un proyecto final.


## Proyecto FInal

Crea una página web utilizando HTML5, CSS3 y JavaScript. El objetivo es crear una página para llevar una lista de tareas, con las funciones de Agregar, Actualizar y Eliminar.



