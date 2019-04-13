---
layout: post
title:  "Keywords in Python"
author: sourabh
categories: [ jumpstart ]
image: ""
---
<span style="color: #252830;"><span style="font-size: 15.3333px;">Keywords are the reserved words in Python.We cannot use a keyword as a variable name, function name or any other identifier.</span></span> There are 33 keywords in Python

<table style="height: 119px; width: 47.6923%; border-collapse: collapse; border-color: #e3e3e3; border-style: solid; margin-left: auto; margin-right: auto;" border="1" cellpadding="2">

<tbody>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">False</td>

<td style="width: 11.4835%; height: 17px;">class</td>

<td style="width: 9.94507%; height: 17px;">finally</td>

<td style="width: 9.9725%; height: 17px;">is</td>

<td style="width: 7.99451%; height: 17px;">return</td>

</tr>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">None</td>

<td style="width: 11.4835%; height: 17px;">Continue</td>

<td style="width: 9.94507%; height: 17px;">for</td>

<td style="width: 9.9725%; height: 17px;">lambda</td>

<td style="width: 7.99451%; height: 17px;">try</td>

</tr>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">True</td>

<td style="width: 11.4835%; height: 17px;">def</td>

<td style="width: 9.94507%; height: 17px;">from</td>

<td style="width: 9.9725%; height: 17px;">nonlocal</td>

<td style="width: 7.99451%; height: 17px;">while</td>

</tr>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">and�</td>

<td style="width: 11.4835%; height: 17px;">del</td>

<td style="width: 9.94507%; height: 17px;">global</td>

<td style="width: 9.9725%; height: 17px;">not</td>

<td style="width: 7.99451%; height: 17px;">with</td>

</tr>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">as</td>

<td style="width: 11.4835%; height: 17px;">elif</td>

<td style="width: 9.94507%; height: 17px;">if�</td>

<td style="width: 9.9725%; height: 17px;">or</td>

<td style="width: 7.99451%; height: 17px;">yield</td>

</tr>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">assert</td>

<td style="width: 11.4835%; height: 17px;">else</td>

<td style="width: 9.94507%; height: 17px;">import</td>

<td style="width: 9.9725%; height: 17px;">pass</td>

<td style="width: 7.99451%; height: 17px;">�</td>

</tr>

<tr style="height: 17px;">

<td style="width: 8.2967%; height: 17px;">break</td>

<td style="width: 11.4835%; height: 17px;">except</td>

<td style="width: 9.94507%; height: 17px;">in</td>

<td style="width: 9.9725%; height: 17px;">raise</td>

<td style="width: 7.99451%; height: 17px;">�</td>

</tr>

</tbody>

</table>

<span style="color: #252830; font-family: Verdana, sans-serif; font-size: 12pt;"></span>Description of Keywords 1\. **True** This keyword is used to represent a boolean true. If a statement is a truth, "True" is printed. 2\. **False�** This keyword is used to represent a boolean false. If a statement is False, "False" is printed. 3\. **None** This is a special constant used to denote a null value or void. It's important to remember, 0, any empty container(e.g empty list) do not compute to None. 4\. **and�** This a logical operator in python. "and" returns true if both the operands are true. Else returns false. 5\. **or** This a logical operator in python. "or" returns true if any one of the operands is true. Else returns false. 6\. **not�** This logical operator inverts the truth value. 7\. **assert**� This function is used for debugging purposes. Usually used to check the correctness of code. If a statement evaluated to true, nothing happens, but when it is false, "AssertionError" is raised. One can also print a message with the error, separated by a comma. 8\. **break** "break" is used to control the flow of loop. The statement is used to break out of the loop and passes the control to the statement following immediately after the loop. 9\. **continue** "continue" is also used to control the flow of code. The keyword skips the current iteration of the loop but does not end the loop. 10\. **class**� This keyword is used to declare user-defined classes. 11\. **def** This keyword is used to declare user-defined functions. 12\. **if** It is a control statement for decision making. Truth expression forces control to go in "if" statement block. 13\. **else** It is a control statement for decision making. False expression forces control to go in "else" statement block. 14\. **elif** It is a control statement for decision making. It is short for "else if". 15\. **del**� del is used to delete a reference to an object. Any variable or list value can be deleted using del. 16\. **try** This keyword is used for exception handling, used to catch the errors in the code using the keyword except. The code in "try" block is checked if there is any type of error, except block, is executed. 17\. **except** As explained above, this works together with "try" to catch exceptions. 18\. **raise** Also used for exception handling to explicitly raise exceptions. 19\. **finally** No matter what is the result of the "try" block, block termed "finally" is always executed. 20\. **for** This keyword is used to control flow and for looping. 21\. **while** Has a similar working like "for", used to control flow and for looping. 22\. **pass** It is the null statement in python. Nothing happens when this is encountered. This is used to prevent indentation errors and used as a placeholder. 23\. **import** This statement is used to include a particular module into the current program. 24\. **from** Generally used with import, from is used to import particular functionality from the module imported. 25\. **as** This keyword is used to create the alias for the module imported. i.e giving a new name to the imported module. 26\. **lambda** creates a new anonymous function. 27\. **return** This keyword is used to return from the function. 28\. **yield** This keyword is used like return statement but is used to return a generator. 29\. **with** This keyword is used to wrap the execution of a block of code within methods defined by context manager. 30\. **in** This keyword is used to check if a container contains a value. This keyword is also used to loop through the container. 31\. **is** This keyword is used to test object identity, i.e to check if both the objects take same memory location or not. 32\. **global** This keyword is used to define a variable inside the function to be of a global scope. 33\. **non-local** This keyword works similar to the global, but rather than global, this keyword declares a variable to point to variable of outside enclosing function, in case of nested functions.