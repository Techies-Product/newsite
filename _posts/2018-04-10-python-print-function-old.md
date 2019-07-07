---
permalink: "/learn/Python-Jumpstart/Python-print-function"
redirect_from: "/python-basic-tutorial/Python-print-function"
---

**Introduction**

In this tutorial we will learn about python print function

**Syntax**

{% highlight python %}
print(*objects, sep=' ', end='\n', file=sys.stdout, flush=False)
{% endhighlight %}

**Parameters of the print() function**

As you can see into the syntax, there are five parameters which we can pass to the print() function

- ***Object**

&nbsp;&nbsp;&nbsp;&nbsp;Whatever object which you want to print on the screen or to the file. Here you can see the print function prefixed with the asterisk (*). Which says that you can pass more than one object.

- **sep**

&nbsp;&nbsp;&nbsp;&nbsp;sep means separator which default value you can see one space.

- **end**

&nbsp;&nbsp;&nbsp;&nbsp;After every print statement what you want to print that you will define in end parameter. The default value of the print statements is Newline (\n)

- **file**

&nbsp;&nbsp;&nbsp;&nbsp;By using file parameter you can write your output into the file stream. By default its value is sys.stdout, It means output will be printed onto system's standard output stream, means will be printed on the console.

- **flush**

&nbsp;&nbsp;&nbsp;&nbsp;It takes either True or False. When the value will be true stream will forcefully flushed. By default its value is False.

*Example: Simple Print Function*

{% highlight python %}
# Passing string object  
print("Hello Python Babu") # It will print simple Hello Python Babu

{% endhighlight %}

*Example: multiple objects passing in print() without the separator*

{% highlight python %}

# Passing multiple object with space 
# Because "sep" parameters default values is space (" ")
print(2,3,4) # It will print 2 3 4

{% endhighlight %}



*Example: Using "sep" parameter*

{% highlight python %}
# Changing the value of the "sep" parameter
print("Python","Babu",sep="-")
{% endhighlight %}

*Example: Understanding "end" parameter*

{% highlight python %}
'''-------------Example 1-------------'''

# Print without any object
print("Hello")
print() # There is no object but default value of the end parameter is '\n'
print("Welcome to Python Babu")

'''-------------Example 2-------------'''

print("Hello",end='! ') # It will print Hello! 
print("Python",end='-') # It will print Python-
print("Babu",end='.') #It will print Babu.
# So the Complete output will be Hello! Python-Babu
{% endhighlight %}

*Example: Writing file using print()*

{% highlight python %}
# Writing file using print function
myfile = open('PythoBabuFile.txt', 'w')
print('Welcome to https://www.pythonbabu.com', file = myfile)
myfile.close()
{% endhighlight %}

**What python print() function returns?**

Python print() function returns `None`

*Example: returning value from the print function*

{% highlight python %}
result=print("Hello") #return value will be save into result
print(result) # It will print none because print returs None
{% endhighlight %}
