### [Jumbotron]
**A lightweight, flexible component that can optionally extend the entire viewport to showcase key content on your site.**  
Start with class jumbotron in a *div* tag:  
```html
<!doctype html>
<html>
<head>
	<title>Jumbotron</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

</head>
<body>
	<div class="jumbotron">
		<h1>Jumbotron</h1>
		<p>Hello world!</p>
		<button class="btn btn-info">Contact us!</button>
	</div>
</body>
</html>
```
However, now everything aligns to the left.  
Add jumbotron to a container.  
*Note: class=jumbotron then class=container or class=container then class=jumbotron gives different result*  
```html
<!doctype html>
<html>
<head>
	<title>Jumbotron</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

</head>
<body>
	<div class="container">
		<div class="jumbotron">
			<h1>Jumbotron</h1>
			<p>Hello world!</p>
			<button class="btn btn-info">Contact us!</button>
		</div>
	</div>
</body>
</html>
```

[Jumbotron]:http://getbootstrap.com/components/#jumbotron
