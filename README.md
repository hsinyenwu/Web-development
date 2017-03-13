# Web-development
Note from an udemy course  
a nice and simple [example] 

1. type **html** and hit **tab** to show the format
```html
<html>
<head>
	<title></title>
</head>
<body>
</body>
</html>
```

 "title" will show up in the tab of the web browser. It will not show up in the web browser, but important for web search. "body" is where we add the content.
 
```html
<html>
<head>
	<title></title>
</head>
<body>
</body>
</html>
```

2. add comment by
 * type <!-- comment here blah blah blah -->
 * select a line and hit **command+/** in sublime

3. add header
```html
<html>
<head>
	<title>test title</title>
</head>
<body>
	<h1> Header level 1 </h1>
	<h2> Header level 2 </h2>
	<h6> Header level 6 </h6>
</body>
</html>
```
Note: Header is a block level element: meaning each one of them get their own lines.

4. add text
text is an inline element, NOT a block level element. Need to add the paragraph tag. The follow
```html
<html>
<head>
	<title>test title</title>
</head>
<body>
	<h1> Header level 1 </h1>
	<h2> Header level 2 </h2>
	<h6> Header level 6 </h6>
	<p>Art is a diverse range of human activities in creating visual, auditory or performing artifacts (artworks), expressing the author's imaginative or technical skill, intended to be appreciated for their beauty or emotional power. In their most general form these activities include the production of works of art, the criticism of art, the study of the history of art, and the aesthetic dissemination of art.</p>
	<p>The oldest documented forms of art are visual arts, which include creation of images or objects in fields including painting, sculpture, printmaking, photography, and other visual media. Architecture is often included as one of the visual arts; however ...</p>
</body>
</html>
```

5. make bold font or italicized
Use <strong></strong> to make words bold.
Use <em></em> to make words italicized. **em** means emphasis

```html
<html>
<head>
	<title>test title</title>
</head>
<body>
	<h1> Header level 1 </h1>
	<h2> Header level 2 </h2>
	<h6> Header level 6 </h6>
	<p> <strong>Art is a diverse range of human activities in creating visual, auditory or performing artifacts (artworks), expressing the author's imaginative or technical skill, intended to be appreciated for their beauty or emotional power.</strong> In their <em>most general form</em> these activities include the production of works of art, the criticism of art, the study of the history of art, and the aesthetic dissemination of art. </p>
	<p> The oldest documented forms of art are visual arts, which include creation of images or objects in fields including painting, sculpture, printmaking, photography, and other visual media. Architecture is often included as one of the visual arts; however ... </p>
</body>
</html>
```





[example]:http://codepen.io/Colt/pen/WQQVvE

