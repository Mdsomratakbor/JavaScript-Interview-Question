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
  
        if (number == 100)  // Here Comparision between two values using ==. This will not check datatype irrespective of datatype it will                                  do comparision  
            $("#lblMessage").text("Both are equal");  
        else  
            $("#lblMessage").text("Both are not equal");  
  
      if(number == "100")  //Here Comparision between two values using ==. This will not check datatype irrespective of datatype it will                              do comparision  
            $("#lblMessage1").text("Both are equal");  
        else  
           $("#lblMessage1").text("Both are not equal");  
    }  
</script> 
</pre>
