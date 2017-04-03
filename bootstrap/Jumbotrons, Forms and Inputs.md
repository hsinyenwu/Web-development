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
### [Forms]
The following is an example from getbootstrap.com:

```html
<!doctype html>
<html>
<head>
	<title>Forms</title>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

</head>
<body>
	<div class="container">
		<form>
		  <div class="form-group">
		    <label for="exampleInputEmail1">Email address</label>
		    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Email">
		  </div>
		  
		  <div class="form-group">
		    <label for="exampleInputPassword1">Password</label>
		    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
		  </div>
		  
		  <div class="form-group">
		    <label for="exampleInputFile">File input</label>
		    <input type="file" id="exampleInputFile">
		    <p class="help-block">Example block-level help text here.</p>
		  </div>
		  
		  <div class="checkbox">
		    <label>
		      <input type="checkbox"> Check me out
		    </label>
		  </div>
		  
		  <button type="submit" class="btn btn-default">Submit</button>
		</form>
	</div>
</body>
</html>

```

[Jumbotron]:http://getbootstrap.com/components/#jumbotron
[Forms]:http://getbootstrap.com/css/#forms
