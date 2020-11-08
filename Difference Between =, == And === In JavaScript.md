# Difference Between =, == And === In JavaScript

`In this article, I am going to demonstrate the difference between =, == and === in javascript. I have chosen a small example to demonstrate the comparision of == and ===.`

- = is used for assigning values to a variable in JavaScript.
- == is used for comparison between two variables irrespective of the datatype of variable.
- === is used for comparision between two variables but this will check strict type, which means it will check datatype and compare two values.
`Let's take the example of each one by one.`

**Example of =**
<pre>var number = 100;  // Here number variable assigned using =</pre>

**Example of ==**
<pre>
if (number == 100)  // Here Comparision between two values using ==. It will compare irrespective of datatype of variable
   alert("Both are equal");    
else    
   alert("Both are not equal");   
   </pre>

**Example of ===**
<pre>
if (number === 100)  // Here Comparision between two values using ===. It will compare strict check means it will check datatype as well.
   alert("Both are equal");      
else      
   alert("Both are not equal"); 
</pre>

**Let's take an example below to understand how == and === do a comparison of two variable values.**


<pre>
<h2>Difference between =, == and === in Javascript</h2>  
<script type="text/javascript">  
    function Comparision() {  
        var number = 100;  // Here number variable assigned using =  
        debugger;  
  
        if (number == 100)  // Here Comparision between two values using ==. This will not check datatype irrespective of datatype it will do comparision  
            $("#lblMessage").text("Both are equal");  
        else  
            $("#lblMessage").text("Both are not equal");  
  
      if(number == "100")  //Here Comparision between two values using ==. This will not check datatype irrespective of datatype it will do comparision  
            $("#lblMessage1").text("Both are equal");  
        else  
           $("#lblMessage1").text("Both are not equal");  
    }  
</script> 
</pre>

<img src="https://www.c-sharpcorner.com/article/difference-between-and-in-javascript2/Images/image001.png"/>

`In the above example, both the comparisons return a true value irrespective of datatype. 100==100 means both are int values and the other condition, 100 == "100" means int comparison with "100" string type of variable still returns true. It means == is not doing a strict type check.`

<pre>
<h2>Difference between =, == and === in Javascript</h2>  
<script type="text/javascript">  
    function Comparision() {  
        var number = 100;  // Here number variable assigned using =  
        debugger;  
  
        if (number === 100)  // Here Comparision between two values using ==. This will not check datatype irrespective of datatype it 
                              will do comparision  
            $("#lblMessage").text("Both are equal");  
        else  
            $("#lblMessage").text("Both are not equal");  
  
        if (number === "100")  // Here Comparision between two values using ==. This will not check datatype irrespective of datatype it                                  will do comparision  
            $("#lblMessage1").text("Both are equal");  
        else  
           $("#lblMessage1").text("Both are not equal");  
    }  
</script>  
<table>  
    <tr>  
        <td>  
            100 === 100  
        </td>  
        <td>  
           <label id="lblMessage" runat="server" ></label>  
        </td>  
    </tr>  
    <tr>  
        <td>  
            100 === "100"  
        </td>  
        <td>  
           <label id="lblMessage1" runat="server" ></label>  
        </td>  
    </tr>  
      
</table>  
 <button id="btnSubmit" type="submit" onclick="Comparision();" class="btn btn-primary">  
         Submit</button>  
</pre>

<img src="https://www.c-sharpcorner.com/article/difference-between-and-in-javascript2/Images/image002.png"/>

`In the above code snippet, I have compared two variables using === operator. It returns true for 100 === 100 and it returns false for 100 === "100". It means === does a strict check for comparison. It checks datatype also and does a comparison based on it.`

**Consclusion**

`Here, I have tried to explain the concept of comparison of two varibale using == and === operator. The single = is used for assigning the value to variable and == , === are used for comparison purposes. == compares two variables irrespective of data type while === compares two variables in a strict check, which means it checks for data type also then it returns true or false.`
