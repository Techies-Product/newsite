---
layout: post
title:  "Variables in Python"
author: sourabh
categories: [ jumpstart ]
image: ""
---

Variable is a named location used to store data in the memory. Each variable must have a unique name called identifier. Based on the data type of a variable, the interpreter allocates memory and decides what can be stored in the reserved memory.

By assigning different data types to variables, we can store integers, decimals or characters in these variables.

In Python, variables do not need a declaration, variable declaration or initialization happens automatically when we assign a value to a variable.

### Assigning a value to a Variable

An assignment statement is written in the following general format:

variable = expression

The equal sign (=) is known as the assignment operator. In the general format,

a variable is the name of a variable and expression is a value.

<iframe src="https://repl.it/@Sumn/variable-1?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>

In the above program, we assigned�values�5,3.5 and hello. Then we print the assigned values�using print function.

**Variable Naming Rules�**

1\. We cannot use one of Python's keywords as a variable name.

2\. A variable name cannot contain spaces.

3\. The first character must be one of the letters a through z, A through Z or an underscore character (-).

After the first character,�we may use the letters a through z or A through 2, the digits O through 9, or underscores.

4\. Uppercase and lowercase characters are distinct. This means the variable name Salary and salary both are different.

Apart from that, we should always choose names for our variables that give an indication of what they are used for. For example, a variable that holds the temperature might be named temperature.