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
<body></body> 
</html>
</pre>


### 11. What are global variables? How are these variable declared and what are the problems associated with using them?

`Global variables are those that are available throughout the length of the code, that is, these have no scope. The var keyword is used to declare a local variable or object. If the var keyword is omitted, a global variable is declared.`

**Example:**

`// Declare a global globalVariable = "Test";`

`The problems that are faced by using global variables are the clash of variable names of local and global scope. Also, it is difficult to debug and test the code that relies on global variables.`

### 12. What is a prompt box?

`A prompt box is a box which allows the user to enter input by providing a text box. Label and box will be provided to enter the text or number.`

### 13. What is 'this' keyword in JavaScript?

`'This' keyword refers to the object from where it was called.`

### 14. Explain the working of timers in JavaScript? Also elucidate the drawbacks of using the timer, if any?


`Timers are used to execute a piece of code at a set time or also to repeat the code in a given interval of time. This is done by using the functions setTimeout, setInterval and clearInterval.`

`The setTimeout(function, delay) function is used to start a timer that calls a particular function after the mentioned delay. The setInterval(function, delay) function is used to repeatedly execute the given function in the mentioned delay and only halts when cancelled. The clearInterval(id) function instructs the timer to stop.`

`Timers are operated within a single thread, and thus events might queue up, waiting to be executed.`

15. Which symbol is used for comments in Javascript?

<pre>// for Single line comments and

/* Multi

Line

Comment

*/</pre>


### 16. What is the difference between ViewState and SessionState?

`'ViewState' is specific to a page in a session.`

`'SessionState' is specific to user specific data that can be accessed across all pages in the web application.`


### 17. What is === operator?
`=== is called as strict equality operator which returns true when the two operands are having the same value without any type conversion.`

### 18. Explain how can you submit a form using JavaScript?

`To submit a form using JavaScript use document.form[0].submit();`
<pre>
document.form[0].submit();
</pre>

### 19. Does JavaScript support automatic type conversion?

`Yes JavaScript does support automatic type conversion, it is the common way of type conversion used by JavaScript developers`

### 20. How can the style/class of an element be changed?

**It can be done in the following way:**

<pre>
document.getElementById("myText").style.fontSize = "20";
</pre>

**or**

<pre>
document.getElementById("myText").className = "anyclass";
</pre>


### 21. Explain how to read and write a file using JavaScript?

**There are two ways to read and write a file using JavaScript**

- `Using JavaScript extensions`
- `Using a web page and Active X objects`

### 22. What are all the looping structures in JavaScript?

**Following are looping structures in Javascript:**

- `For`
- `While`
- `do-while loops`

### 23. What is called Variable typing in Javascript?

**Variable typing is used to assign a number to a variable and the same variable can be assigned to a string.**

Example
<pre>
i = 10;
i = "string";
</pre>
**This is called variable typing.**

### 24. How can you convert the string of any base to integer in JavaScript?

`The parseInt() function is used to convert numbers between different bases. parseInt() takes the string to be converted as its first parameter, and the second parameter is the base of the given string.`

**In order to convert 4F (of base 16) to integer, the code used will be -**

<pre>parseInt ("4F", 16);</pre>

### 25. Explain the difference between "==" and "==="?

`"==" checks only for equality in value whereas "===" is a stricter equality test and returns false if either the value or the type of the two variables are different.`

### 26. What would be the result of 3+2+"7"?

`Since 3 and 2 are integers, they will be added numerically. And since 7 is a string, its concatenation will be done. So the result would be 57.`

### 27. Explain how to detect the operating system on the client machine?

`In order to detect the operating system on the client machine, the navigator.platform string (property) should be used.`

### 28. What do mean by NULL in Javascript?

`The NULL value is used to represent no value or no object. It implies no object or null string, no valid boolean value, no number and no array object.`

### 29. What is the function of delete operator?

`The delete keyword is used to delete the property as well as its value.`

**Example**

<pre>var student= {age:20, batch:"ABC"};
delete student.age;
</pre>

### 30. What is an undefined value in JavaScript?

`Undefined value means the`

- **Variable used in the code doesn't exist**
- **Variable is not assigned to any value**
- **Property doesn't exist**

### 31. What are all the types of Pop up boxes available in JavaScript?

- `Alert`
- `Confirm and`
- `Prompt`

### 32. What is the use of Void(0)?

`Void(0) is used to prevent the page from refreshing and parameter "zero" is passed while calling.`

`Void(0) is used to call another method without refreshing the page.`

### 33. How can a page be forced to load another page in JavaScript?

**The following code has to be inserted to achieve the desired effect:**

<pre>
<script language="JavaScript" type="text/javascript" >

<!-- location.href="http://newhost/newpath/newfile.html"; //--></script>
</pre>

### 34. What is the data type of variables of in JavaScript?

`All variables in the JavaScript are object data types.`


### 35. What is the difference between an alert box and a confirmation box?

`An alert box displays only one button which is the OK button.`

`But a Confirmation box displays two buttons namely OK and cancel.`

### 36. What are escape characters?

`Escape characters (Backslash) is used when working with special characters like single quotes, double quotes, apostrophes and ampersands. Place backslash before the characters to make it display.`

**Example:**
<pre>
document.write "I m a "good" boy"
document.write "I m a \"good\" boy"
</pre>

### 37. What are JavaScript Cookies?

`Cookies are the small test files stored in a computer and it gets created when the user visits the websites to store information that they need. Example could be User Name details and shopping cart information from the previous visits.`

### 38. Explain what is pop()method in JavaScript?

The pop() method is similar as the shift() method but the difference is that the Shift method works at the start of the array. Also the pop() method take the last element off of the given array and returns it. The array on which is called is then altered.

**Example:**
<pre>
let students = ["somrat","akbor","moazzam","hossain"]; 
console.log(students); 
students.pop();
console.log(students); 
</pre>

### 39. Whether JavaScript has concept level scope?

`No. JavaScript does not have concept level scope. The variable declared inside the function has scope inside the function.`

### 40. What is break and continue statements?

`Break statement exits from the current loop.`

`Continue statement continues with next statement of the loop.`

### 41. What are the two basic groups of dataypes in JavaScript?

**They are as –**

- **Primitive**
- **Reference types.**
- **Primitive types are number and Boolean data types. Reference types are more complex types like strings and dates.**
