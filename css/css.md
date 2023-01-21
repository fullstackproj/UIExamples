### :camel: CSS examples
---

#### Task1: css selector
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
p{  
    text-align: center;  
    color: blue;  
}   
</style>  
</head>  
<body>  
<p>This style will be applied on every paragraph.</p>  
<p id="para1">Me too!</p>  
<p>And me!</p>  
</body>  
</html> 

```
#### Task2: Id selector
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
#para1 {  
    text-align: center;  
    color: blue;  
}  
</style>  
</head>  
<body>  
<p id="para1">Hello NCodeIT</p>  
<p>This paragraph will not be affected.</p>  
</body>  
</html> 


```

#### Task3: Class Selector
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
.center {  
    text-align: center;  
    color: blue;  
}  
</style>  
</head>  
<body>  
<h1 class="center">This heading is blue and center-aligned.</h1>  
<p class="center">This paragraph is blue and center-aligned.</p>   
</body>  
</html> 

```
#### Task4: Universal Selector
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
* {  
   color: green;  
   font-size: 20px;  
}   
</style>  
</head>  
<body>  
<h2>This is heading</h2>  
<p>This style will be applied on every paragraph.</p>  
<p id="para1">Me too!</p>  
<p>And me!</p>  
</body>  
</html> 

```
#### Task5: Group Selector
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
h1, h2, p {  
    text-align: center;  
    color: blue;  
}  
</style>  
</head>  
<body>  
<h1>Hello NcodeIT</h1>  
<h2>Hello NcodeIT (In smaller font)</h2>  
<p>This is a paragraph.</p>  
</body>  
</html> 

```
#### Task6: External CSS
```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

* Below CSS should be in mystyle.css

```
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}
```

#### Task7: CSS background colour
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
h2,p{  
    background-color: #b0d4de;  
}  
</style>  
</head>  
<body>  
<h2>My first CSS page.</h2>  
<p>Hello NcodeIT. This is an example of CSS background-color.</p>  
</body>  
</html> 

```

#### Task8: CSS Font colour
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
body {  
    font-size: 100%;  
}  
h1 { color: red; }  
h2 { color: #9000A1; }   
p { color:rgb(0, 220, 98); }   
}  
</style>  
</head>  
<body>  
<h1>This is heading 1</h1>  
<h2>This is heading 2</h2>  
<p>This is a paragraph.</p>  
</body>  
</html> 
   
```

#### Task9: Font Family
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
body {  
font-size: 100%;  
}  
h1 { font-family: sans-serif; }  
h2 { font-family: serif; }   
p { font-family: monospace; }   
}  
</style>  
</head>  
<body>  
<h1>This heading is shown in sans-serif.</h1>  
<h2>This heading is shown in serif.</h2>  
<p>This paragraph is written in monospace.</p>  
</body>  
</html> 

```
#### Task9: Font Size
```
<html>  
<head>  
<title>Practice CSS font-size property</title>  
</head>  
<body>  
<p style="font-size:xx-small;">  This font size is extremely small.</p>    
<p style="font-size:x-small;">  This font size is extra small</p>    
<p style="font-size:small;">  This font size is small</p>    
<p style="font-size:medium;">  This font size is medium. </p>    
<p style="font-size:large;">  This font size is large. </p>    
<p style="font-size:x-large;">  This font size is extra large. </p>    
<p style="font-size:xx-large;">  This font size is extremely large. </p>    
<p style="font-size:smaller;">  This font size is smaller. </p>    
<p style="font-size:larger;">  This font size is larger. </p>    
<p style="font-size:200%;">  This font size is set on 200%. </p>    
<p style="font-size:20px;">  This font size is 20 pixels.  </p>    
</body>  
</html> 

```

#### Task10: Font style
```
<html>
<body>
<script>  
emp={id:102,name:"Shyam Kumar",salary:40000}  
document.write(emp.id+" "+emp.name+" "+emp.salary);  
</script>
</body>
</html>
```

#### Task11: Font Variant
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
p { font-variant: small-caps; }  
h3 { font-variant: normal; }  
</style>  
</head>  
<body>  
<h3>This heading is shown in normal font.</h3>  
<p>This paragraph is shown in small font.</p>  
</body>  
</html> 

```

#### Task12: Font Weight
```
<!DOCTYPE html>  
<html>  
<body>  
<p style="font-weight:bold;">This font is bold.</p>  
<p style="font-weight:bolder;">This font is bolder.</p>  
<p style="font-weight:lighter;">This font is lighter.</p>  
<p style="font-weight:100;">This font is 100 weight.</p>  
<p style="font-weight:200;">This font is 200 weight.</p>  
<p style="font-weight:400;">This font is 400 weight.</p>  
<p style="font-weight:500;">This font is 500 weight.</p>  
<p style="font-weight:900;">This font is 900 weight.</p>  
</body>  
</html> 
```

#### Task13: CSS Links
```
<html>
   <head>
      <style type = "text/css">
         a:link {color:#000000}
     </style>
   </head>

   <body>
      <a href = "">Link</a>
   </body>
</html> 

```