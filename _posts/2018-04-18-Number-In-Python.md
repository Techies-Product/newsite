---
layout: post
title:  "Number in Python"
author: sourabh
categories: [ Basic of Python ]
hashtag: [python,number]
image: "/assets/images/demo1.jpg"
permalink: "/python-basic-tutorial/numbers-to-python"
isTutorial: true
---

Number In Python
Integers, floating point and complex come under numbers.

We can use the type() function to know which class a variable or a value belongs to and the isinstance() function to check if an object belongs to a particular class

**Integer**

An Integer type holds an integer value or a whole number that can be a negative or positive value, like -5, -4, 0, 8, 9, 10 and so on. In the Python you can declare an integer value such as in the following:

*Example*

{% highlight python %}
a=15
print(a)
{% endhighlight %}

*Output*

But in the preceding example, you cannot determine the type of the variable. So in Python, we have a function by which we can get the type of a variable. The function is as in the following:

type(variable)
Example

a=15
print(type(a))

Output

We can represent any integer variable in Decimal or Octal or Hexa-Decimal format.

In Decimal
In decimal you can write directly your Python variable as in the following:
a=12

In Octal
In Octal you can represent such as in the following:
a=0O14
or
a=0o14

Example
a=0O14
print(a)

Output

In Hexa-Decimal
You can represent any integer variable as a Hexa-decimal such as in the following:
a=0XC
or
a=0xC

Example
a=0xC
print(a)

Output

Float
They represent real numbers and are written with a decimal point dividing the integer and fractional parts.

Example
PI=3.14
print(“Type of PI is: \n”)
print(type(PI)) #This will print type of PI
print("\n\nValue of PI is : %f" %PI)
Output

We can also represent a floating point number in E notation.

Fraction
In Python, you can also create a type that can hold fractional numbers, like 1/2, 3/5 and so on. To create a Fractional type of number you must import the “fractions” module. Then you need to create a fraction object.

Example
import fractions
x = fractions.Fraction(1, 3)
print(x)

Output

Not only that, you can also operate fractional numbers.

Example
import fractions
x = fractions.Fraction(1, 5)
y = fractions.Fraction(2, 5)
print("%s + %s = %s"%(x,y,(x+y)))

Output

Complex
In Python, you can create a Complex type variable that will have a real part as well as an imaginary part, like 3 + 5i. Here the real part is 3 and the imaginary part is 5.
To create the complex type of variable in Python we have a function called complex(real_part, imaginary_part) that takes two arguments, a real part and an imaginary part.

Example
x = complex(3,5)
print(x)

Output
