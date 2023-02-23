# Class 7: Programming with JavaScript

1. **What is control flow?**

- The control flow is the order in which the computer executes statements in a script.
    Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
    <br>

2. **What is a JavaScript function?**

- A JavaScript function is a block of code designed to perform a particular task.
    A JavaScript function is executed when "something" invokes it (calls it).

### **Ex.**  

        // Function to compute the product of p1 and p2
        function myFunction(p1, p2) {
          return p1 * p2;
        }

    JavaScript function is defined with the **function** keyword, followed by a **name**, followed by parentheses **()**.

    Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

    The parentheses may include parameter names separated by commas:
    **(parameter1, parameter2, ...)**

    The code to be executed, by the function, is placed inside curly brackets: {}

### **Ex.**

        function name(parameter1, parameter2, parameter3) {
         // code to be executed
        }

<br>

3. **What does it mean to invoke - or call - a function?**

- The code inside the function will execute when "something" invokes (calls) the  function:

        - When an event occurs (when a user clicks a button)  
        - When it is invoked (called) from JavaScript code  
        - Automatically (self invoked)
<br>

4. **What are the parenthesis () for when you define a function?**

    - They are used to contain a list of parameters passed to functions and control structures and they are used to group expressions to control the order of execution. Some functions have no parameters and in this case, the space between parentheses is blank.
