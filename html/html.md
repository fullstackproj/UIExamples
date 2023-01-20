### :camel: HTML examples
---
* __*this workshop needs ncodeit custom ubuntu server*__

#### Task1: Basic html tags 
```
<!DOCTYPE html>  
<html>  
 <head>  
    <title>Heading elements</title>  
 </head>  
 <body>  
     <h1>This is main heading of page. </h1>  
      <p>h1 is the most important heading, which is used to display the keyword of page </p>  
     <h2>This is first sub-heading</h2>  
      <p>h2 describes the first sub heading of page. </p>  
     <h3>This is Second sub-heading</h3>  
      <p>h3 describes the second sub heading of page.</p>  
      <p>We can use h1 to h6 tag to use the different sub-heading with their paragraphs if         
                     required.   
                </p>  
   </body>  
</html>


```
#### Task2: Anchor tag
* docker can search and pull images from dockerhub 
```
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
<p>Click on <a href="https://www.gmail.com/" target="_blank"> this-link </a>to go on home page of Gmail.</p>
</body>
</html>

```

#### Task3: Image tag
```
<!DOCTYPE>
<html>  
<body>  
<h2>HTML Image Example</h2>  
<img src="good-morning.jpg" alt="Good Morning Friends"/> 
</body>  
</html>  


```
#### Task4: table
```
<!DOCTYPE>
<html>  
<body>  
<table>  
<tr><th>First_Name</th><th>Last_Name</th><th>Marks</th></tr>  
<tr><td>Sonoo</td><td>Jaiswal</td><td>60</td></tr>  
<tr><td>James</td><td>William</td><td>80</td></tr>  
<tr><td>Swati</td><td>Sironi</td><td>82</td></tr>  
<tr><td>Chetna</td><td>Singh</td><td>72</td></tr>  
</table>  
</body>
</html>  
```
#### Task5: ordered list
```
<!DOCTYPE html>
<html>
<body>
<ol>  
 <li>HTML</li>  
 <li>Java</li>  
 <li>JavaScript</li>  
 <li>SQL</li>  
</ol>  
</body>
</html>

```
#### Task6: unordered list 
```
<!DOCTYPE html>  
<html>  
<body>  
<ul>  
 <li>HTML</li>  
 <li>Java</li>  
 <li>JavaScript</li>  
 <li>SQL</li>  
</ul>   
</body>  
</html> 
```

#### Task7: definition list
```
<!DOCTYPE html>  
<html>  
<body>  
<dl>  
  <dt>HTML</dt>  
  <dd>is a markup language</dd>  
  <dt>Java</dt>  
  <dd>is a programming language and platform</dd>  
 <dt>JavaScript</dt>  
 <dd>is a scripting language</dd>  
  <dt>SQL</dt>  
  <dd>is a query language</dd>   
</dl>  
</body>  
</html> 
```

#### Task8: Html Form
```
<!DOCTYPE html>  
 <html>  
 <head>  
  <title>Form in HTML</title>  
</head>  
 <body>  
     <h2>Registration form</h2>  
    <form>  
     <fieldset>  
        <legend>User personal information</legend>  
        <label>Enter your full name</label><br>  
        <input type="text" name="name"><br>  
         <label>Enter your email</label><br>  
         <input type="email" name="email"><br>  
         <label>Enter your password</label><br>  
         <input type="password" name="pass"><br>  
         <label>confirm your password</label><br>  
         <input type="password" name="pass"><br>  
         <br><label>Enter your gender</label><br>  
         <input type="radio" id="gender" name="gender" value="male"/>Male  <br>  
         <input type="radio" id="gender" name="gender" value="female"/>Female <br/>    
         <input type="radio" id="gender" name="gender" value="others"/>others <br/>   
          <br>Enter your Address:<br>  
         <textarea></textarea><br>  
         <input type="submit" value="sign-up">  
     </fieldset>  
  </form>  
 </body>  
</html>  
```