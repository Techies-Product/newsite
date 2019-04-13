---
layout: post
title:  "Conditions in Python"
author: sourabh
categories: [ jumpstart ]
image: ""
---

In programming and scripting languages, conditional statements are used to perform different computations or actions depending on whether a condition evaluates to true or false. The condition usually uses comparisons and arithmetic expressions with variables. These expressions are evaluated to the Boolean values True or False.

The general form of the if statement in Python looks like this:

if condition_1:

� � statement_block_1

elif condition_2:

� � statement_block_2

else:

� � statement_block_3

If the condition "condition_1" is True, the statements in the block statement_block_1 will be executed. If not, condition_2 will be executed. If condition_2 evaluates to True, statement_block_2 will be executed, if condition_2 is False, the statements in statement_block_3 will be executed.

<iframe src="https://repl.it/@Sumn/Conditions?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>

Python supports the usual logical conditions from mathematics:

Equals: a == b

Not Equals: a != b

Less than: a < b

Less than or equal to: a <= b

Greater than: a > b

Greater than or equal to: a >= b