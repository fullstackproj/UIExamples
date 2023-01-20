### :camel: Javascript examples
---

#### Task1: External JS file
```
<html>  
<head>  
<script type="text/javascript" src="message.js"></script>  
</head>  
<body>  
<p>Welcome to JavaScript</p>  
<form>  
<input type="button" value="click" onclick="msg()"/>  
</form>  
</body>  
</html> 


```
#### Task2: Variable
```
<html>
<body>
<script>  
var data=200;//gloabal variable  
function a(){  
document.writeln(data);  
}  
function b(){  
document.writeln(data);  
}  
a();//calling JavaScript function
b();
  
</script>  
</body>
</html>

```

#### Task3: if else
```
<html>
   <body>     
      <script type = "text/javascript">
         <!--
            var age = 20;
         
            if( age > 18 ) {
               document.write("<b>Qualifies for driving</b>");
            }
         //-->
      </script>      
      <p>Set the variable to different value and then try...</p>
   </body>
</html> 


```
#### Task4: switch
```
<html>
   <body>   
      <script type = "text/javascript">
         <!--
            var grade = 'A';
            document.write("Entering switch block<br />");
            switch (grade) {
               case 'A': document.write("Good job<br />");
               break;
            
               case 'B': document.write("Pretty good<br />");
               break;
            
               case 'C': document.write("Passed<br />");
               break;
            
               case 'D': document.write("Not so good<br />");
               break;
            
               case 'F': document.write("Failed<br />");
               break;
            
               default:  document.write("Unknown grade<br />")
            }
            document.write("Exiting switch block");
         //-->
      </script>      
      <p>Set the variable to different value and then try...</p>
   </body>
</html> 
```
#### Task5: for loop
```
<!DOCTYPE html>
<html>
<body>
<script>  
for (i=1; i<=5; i++)  
{  
document.write(i + "<br/>")  
}  
</script>  
</body>
</html>


```
#### Task6: function
```
<html>
<body>
<script>  
function msg(){  
alert("hello! this is message");  
}  
</script>  
<input type="button" onclick="msg()" value="call function"/>  
</body>
</html>
```

#### Task7: window methods
```
<html>
<body>
<script>  
<script type="text/javascript">  
function msg(){  
 alert("Hello Alert Box");  
}  
</script>     
<input type="button" value="click" onclick="msg()"/>   
</body>
</html>
```

#### Task8: Document Object
```
<script type="text/javascript">  
function printvalue(){  
var name=document.form1.name.value;  
alert("Welcome: "+name);  
}  
</script>  
  
<form name="form1">  
Enter Name:<input type="text" name="name"/>  
<input type="button" onclick="printvalue()" value="print name"/>  
</form>   
```

#### Task9: class
```
<!DOCTYPE html>
<html>
<body>

<script>
//Declaring class
class Employee
  {
//Initializing an object
    constructor(id,name)
    {
      this.id=id;
      this.name=name;
    }
//Declaring method
    detail()
    {
  document.writeln(this.id+" "+this.name+"<br>")
    }
  }
//passing object to a variable 
var e1=new Employee(101,"Martin Roy");
var e2=new Employee(102,"Duke William");
e1.detail(); //calling method
e2.detail();
</script>

</body>
</html>
```
#### Task9: class
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

#### Task9: Object
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

#### Task10: Array
```
<html>
<body>
<script>  
var emp=["Sonoo","Vimal","Ratan"];  
for (i=0;i<emp.length;i++){  
document.write(emp[i] + "<br/>");  
}  
</script>  
</body>
</html>
```