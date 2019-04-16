---
layout: post
title:  "Keywords in Python"
author: sourabh
categories: [ Basic of Python ]
tag: [python,keywords,reserved words]
image: "/assets/images/demo1.jpg"
permalink: "/python-basic-tutorial/python-keywords"
isTutorial: true
---

**Introduction**

In this tutorial, we will learn about python keywords.

**Keywords**

Keywords are the reserved words in Python. We cannot use a keyword as a variable name, function name or any other identifier.

There are 33 keywords in Python, Which are listed in following table

|  |   | | | |
|--|--|--|--|--|
| False |   class  | finally | is     | return |
| None  |  Continue |     for |    lambda | try
| True  |  def |    from   | nonlocal |        while
| and   |  del  |   global | not |    with
| as    |  elif  |  if    |  or   |   yield
| assert |  else  |  import | pass     
| break  | except | in  |    raise    

*Description of Keywords*

**True**

This keyword is used to represent a boolean true. If a statement is a truth, "True" is printed.


**False**

This keyword is used to represent a boolean false. If a statement is False, "False" is printed.


**None**

This is a special constant used to denote a null value or void. It's important to remember, 0, any empty container(e.g empty list) do not compute to None.


**and**

This a logical operator in python. "and" returns true if both the operands are true. Else returns false.


**or**

This a logical operator in python. "or" returns true if any one of the operands is true. Else returns false.


**not**

This logical operator inverts the truth value.


**assert**

This function is used for debugging purposes. Usually used to check the correctness of code. If a statement evaluated to true, nothing happens, but when it is false, "AssertionError" is raised. One can also print a message with the error, separated by a comma.


**break**

"break" is used to control the flow of loop. The statement is used to break out of the loop and passes the control to the statement following immediately after the loop.


**continue**

"continue" is also used to control the flow of code. The keyword skips the current iteration of the loop but does not end the loop.


**class**

This keyword is used to declare user-defined classes.


**def**

This keyword is used to declare user-defined functions.


**if**

It is a control statement for decision making. Truth expression forces control to go in "if" statement block.


**else**

It is a control statement for decision making. False expression forces control to go in "else" statement block.


**elif**

It is a control statement for decision making. It is short for "else if".


**del**

del is used to delete a reference to an object. Any variable or list value can be deleted using del.


**try**

This keyword is used for exception handling, used to catch the errors in the code using the keyword except. The code in "try" block is checked if there is any type of error, except block, is executed.


**except**

As explained above, this works together with "try" to catch exceptions.


**raise**

Also used for exception handling to explicitly raise exceptions.


**finally**

No matter what is the result of the "try" block, block termed "finally" is always executed.


**for**

This keyword is used to control flow and for looping.


**while**

Has a similar working like "for", used to control flow and for looping.


**pass**

It is the null statement in python. Nothing happens when this is encountered. This is used to prevent indentation errors and used as a placeholder.


**import**

This statement is used to include a particular module into the current program.


**from**

Generally used with import, from is used to import particular functionality from the module imported.


**as**

This keyword is used to create the alias for the module imported. i.e giving a new name to the imported module.


**lambda**

creates a new anonymous function.


**return**

This keyword is used to return from the function.


**yield**

This keyword is used like return statement but is used to return a generator.


**with**

This keyword is used to wrap the execution of a block of code within methods defined by context manager.


**in**

This keyword is used to check if a container contains a value. This keyword is also used to loop through the container.


**is**

This keyword is used to test object identity, i.e to check if both the objects take same memory location or not.


**global**

This keyword is used to define a variable inside the function to be of a global scope.


**non**

This keyword works similar to the global, but rather than global, this keyword declares a variable to point to variable of outside enclosing function, in case of nested functions.
