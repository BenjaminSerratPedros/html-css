# HTML5 and CSS3
![Imagen HTML](http://www.paginaswebs.com/wp-content/uploads/2015/12/html-on-sheet.jpg)
- Estructura básica de una página web
- [HTML Video](https://www.youtube.com/watch?v=cqMfPS8jPys)

``` html
<!DOCTYPE html>
<html>

	<head>
		<meta charset="utf-8">
		<title>My website</title>
		<style type="text/css">
			* {
				border: 1px solid black;
			}

			html {
				margin: 0px;
				padding: 0px;
			}

			body {
				font-family: Arial;Sans-Serif;
				color:#666666;
				padding: 0px;
				margin: 0px;
			}
			h1,h2,h3,h4,h5 {
				color:#0000CC;
			}
			h1 {
				font-size:3em;
			}
			header {
				background-color:#7CBACF;
				color: #FFFFFF;
				margin: 0px;
				padding: 15px;
			}
			header h1 {
				color: #FFFFFF;
				margin: 0px;
				padding: 0px;
			}
			article {
				padding: 15px;
			}
			footer {
				margin: 0px;
				padding: 15px;
			}
		</style>
		<script type="text/javascript">
			// alert("Error")
		</script>
	</head>

	<body>
		<header>
			<h1>Título principal</h1>
			<nav>Navegación</nav>
		</header>
		<aside>
			
		</aside>
		<section>

		<article>
			<h2>Título secundario</h2>
			<p><strong>Lorem Ipsum</strong> is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
		</article>
		<article>
			<h3>Otro artículo</h3>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
		</article>
		</section>
		<footer>
			Contacto: bimyamim15@gmail.com - All rights reserved

		</footer>
	</body>

</html>
```
