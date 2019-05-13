---
layout: post
title:  "Python Input Function"
author: sourabh
categories: [ Basic of Python ]
tag: [python, input, function, input function]
image: "/assets/images/demo1.jpg"
permalink: "/python-basic-tutorial/python-input-function"
isTutorial: true
---

**Introduction**

In this tutorial, we will learn input function of the python function

**Python input() function**

Python `input` function is used to take input from the console. The input() method reads the line from **sys.stdin** and returns it with the trailing newline stripped. It raises EOFError if the input is terminated prematurely.

**Syntax**

Syntax of the input() method is as follows

```python
input([prompt])
```
*prompt*

In the syntax you can see, python input function takes **prompt** argument. This argument is option argument.

*Example*

{% highlight python %} 
name = input("What is your name? \n")
print("Hello"+name)
{% endhighlight %}
