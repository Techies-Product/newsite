---
layout: post
title:  "Dictionary In Python"
author: sourabh
categories: [ Basic of Python ]
hashtag: [python,dictionary]
image: "/assets/images/demo1.jpg"
permalink: "/python-basic-tutorial/dictionary-in-python"
isTutorial: true
---
**Introduction**
Dictionary is an unordered mapping from unique, immutable keys to mutable values and delimited by { and }. 

*properties*
- The dictionary contains key-value pairs. Keys are like a list’s indexes.
- Variables hold references to dictionary values, not the dictionary value itself.
- In a dictionary, key-value pairs are comma separated.
- Corresponding keys and values are joined by a colon.
- In dictionary Keys must be unique and immutable.
- keyword arguments -requires keys are valid Python identifiers.
- d.copy() for copying dictionaries 
- The keys(), values() and item() methods will return list-like values of a dictionary’s keys, values and both keys and values, respectively.
- The get() method can return a default value if a key doesn’t exist.
- Use values() for an iterable view onto the series of values.
- Use items() for an iterable view onto the series of key-value tuples.

**Example**

{% highlight python %} 
dict = {'Name': 'Vijay', 'Age': 15, 'Class': 'First'}
print ("dict['Name']: ", dict['Name']) #accessing dictionary value 
print ("dict['Age']: ", dict['Age'])
dict['Name']='Rinky' #Updating dictionary value 
print("dict['Name']",dict['Name'])
dict.clear()     # remove all entries in dict
{% endhighlight %}