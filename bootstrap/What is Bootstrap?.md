## Bootstrap intro:

[Bootstrap] is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.  
* It is just a single css and a single javascript file. Help us to make good looking websites quickly.  
* Go to the bootstrap website. You will see CSS, Components (Nav bar, Progress bar, bottons, dropdown manuels ...) and Javascript.  
* It is just a lot of classes.
* Find examples at: [Expo]
* Good grid system  
* Responsive (when you change the browser size, the contents change accordingly)  

### Two ways to use bootstrap:
1. download bootstrap file and save in the same folder with html, css and js files. The bootstrap.mini.css file loads faster since all the white spaces were removed to save space. Add a link to the head of html, rhef="bootstrap.mini.css"    
2. use a link tag for the CDN in the html file (i.e. the href in that case is the CDN file location).  

### Basic usage:
You can see difference with or without the bootstrap link tag.  
```html
<!doctype html>
<html>
<head>
	<title>Bootstrap</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	
</head>
<body>
	<h1>Bootstrap</h1>
	
</body>
</html>
```

### Add buttons:
Go to [btn-groups]:  
There are few examples to use bootstrap buttons:  

```html
<!doctype html>
<html>
<head>
	<title>Bootstrap</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

</head>
<body>
	<h1>Bootstrap</h1>
	<div>
		<!-- button without bootstrap -->
		<button>Click!</button>
		<!-- button with bootstrap -->
		<button class="btn btn-default">default!</button>
		<button class="btn btn-primary">primary!</button>
		<button class="btn btn-success">success!</button>
		<button class="btn btn-info">info!</button>
		<button class="btn btn-warning">warning!</button>
		<button class="btn btn-danger">danger!</button>
	</div>
</body>
</html>
```
Change button sizes:  
It is simple. Just add a class.
```html
<!doctype html>
<html>
<head>
	<title>Bootstrap</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

</head>
<body>
	<h1>Bootstrap</h1>
	<div>
		<!-- button with bootstrap -->
		<button class="btn btn-default btn-lg">Large</button>
		<button class="btn btn-default">Default</button>
		<button class="btn btn-default btn-sm">Small</button>
		<button class="btn btn-default btn-xs">Extra small</button>
	</div>
</body>
</html>
```
### Use button on \<a> element 
Here use button to setup a link to google.  
```html
<!doctype html>
<html>
<head>
	<title>Bootstrap</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

</head>
<body>
	<h1>Bootstrap</h1>
	<div>
		<!-- button with bootstrap -->
		<a href="https://www.google.com" class= "btn btn-warning btn-lg">Google</a>
	</div>
</body>
</html>
```




[Expo]:https://expo.getbootstrap.com
[Bootstrap]:http://getbootstrap.com
[btn-groups]:http://getbootstrap.com/components/#btn-groups

