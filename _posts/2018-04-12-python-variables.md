---
layout: post
title:  "Python Variables"
author: sourabh
categories: [ Basic of Python ]
hashtag: [python,variables]
image: "/assets/images/demo1.jpg"
permalink: "/python-basic-tutorial/python-variables"
isTutorial: true
---

**Introduction**

In this article, we will learn, About variables and how we can create variables in python.

Variable is a named location used to store data in the memory. Each variable must have a unique name called identifier. Based on the data type of a variable, the interpreter allocates memory and decides what can be stored in the reserved memory.

By assigning different data types to variables, we can store integers, decimals or characters in these variables.

In Python, variables do not need a declaration, variable declaration or initialization happens automatically when we assign a value to a variable.

**Assigning a value to a Variable**

An assignment statement is written in the following general format:

{% highlight python %}
variable = expression
{% endhighlight %}

The equal sign (=) is known as the assignment operator. In the general format,

A variable is the name of a variable and expression is a value.

*Example*

{% highlight python %}
a=5
b=3.5
c='hello'
print(a)
print(b)
print(c)
{% endhighlight %}

In the above program, we assigned values 5,3.5 and hello. Then we print the assigned values using print function.

**Variable Naming Rules**

1. We cannot use one of Python's keywords as a variable name.

2. A variable name cannot contain spaces.

3. The first character must be one of the letters a through z, A through Z or an underscore character (-). After the first character, we may use the letters a through z or A through 2, the digits O through 9, or underscores.

4. Uppercase and lowercase characters are distinct. This means the variable name Salary and salary both are different.

Apart from that, we should always choose names for our variables that give an indication of what they are used for. For example, a variable that holds the temperature might be named temperature.

