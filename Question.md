### 1. What is JavaScript?

`JavaScript is a client-side as well as server side scripting language that can be inserted into HTML pages and is understood by web browsers. JavaScript is also an Object based Programming language`

### 2. Enumerate the differences between Java and JavaScript?

`Java is a complete programming language. In contrast, JavaScript is a coded program that can be introduced to HTML pages. These two languages are not at all inter-dependent and are designed for the different intent. Java is an object - oriented programming (OOPS) or structured programming language like C++ or C whereas JavaScript is a client-side scripting language.`

### 3. What are JavaScript Data Types?

**Following are the JavaScript Data types:**

- **Number**
- **String**
- **Boolean**
- **Object**
- **Undefined**

### 4. What is the use of isNaN function?

`isNan function returns true if the argument is not a number otherwise it is false.`

### 5. Between JavaScript and an ASP script, which is faster?

`JavaScript is faster. JavaScript is a client-side language and thus it does not need the assistance of the web server to execute. On the other hand, ASP is a server-side language and hence is always slower than JavaScript. Javascript now is also a server side language (nodejs).`

### 6. What is negative infinity?

`Negative Infinity is a number in JavaScript which can be derived by dividing negative number by zero.`

### 7. Is it possible to break JavaScript Code into several lines?

`Breaking within a string statement can be done by the use of a backslash, '\', at the end of the first line`

**Example:**

**document.write("this is \a program")**

`And if you change to a new line when not within a string statement, then javaScript ignores break in line.`

**Example:**

<pre>var x=1, y=2,
z=
x+y;</pre>


`The above code is perfectly fine, though not advisable as it hampers debugging.`

### 8. Which company developed JavaScript?

`Netscape is the software company who developed JavaScript.`

### 9. What are undeclared and undefined variables?

`Undeclared variables are those that do not exist in a program and are not declared. If the program tries to read the value of an undeclared variable, then a runtime error is encountered.`

`Undefined variables are those that are declared in the program but have not been given any value. If the program tries to read the value of an undefined variable, an undefined value is returned.`

### 10. Write the code for adding new elements dynamically?
<pre>
<html> 
<head> 
<title>t1</title> 
<script type="text/javascript"> 
	function addNode() { var newP = document.createElement("p"); 
	var textNode = document.createTextNode(" This is a new text node"); 
	newP.appendChild(textNode); document.getElementById("firstP").appendChild(newP); } 
</script> </head> 
<body> <p id="firstP">firstP<p> </body> 
</html>
</pre>

