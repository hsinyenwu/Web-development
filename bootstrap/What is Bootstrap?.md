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

[Expo]:https://expo.getbootstrap.com
[Bootstrap]:http://getbootstrap.com
