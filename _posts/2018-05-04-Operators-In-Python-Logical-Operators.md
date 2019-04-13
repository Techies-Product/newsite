---
layout: post
title:  "Python Logical Operators"
author: sourabh
categories: [ jumpstart ]
image: 
---

### **Python Logical Operators**

Logical operators are the **<span style="background-color: #ccffff;">and</span>**, <span style="background-color: #ccffff;">**or**</span>, <span style="background-color: #ccffff;">**not** </span>operators.

Now we will see different Logical Operators and how to implement Logical operations in python.

<table style="width: 100%; border-collapse: collapse; border-style: solid;" border="1">

<tbody>

<tr style="height: 18px;">

<td style="width: 15.6556%; text-align: center; height: 18px;">**Symbol � � �**</td>

<td style="width: 19.5127%; text-align: center; height: 18px;">**Operator Name**</td>

<td style="width: 64.724%; text-align: center; height: 18px;">**Description**</td>

</tr>

<tr style="height: 18px;">

<td style="width: 15.6556%; height: 18px; text-align: center;">and�</td>

<td style="width: 19.5127%; height: 18px;">Logical AND</td>

<td style="width: 64.724%; height: 18px;">

If both the operands are true, then the condition is true.

</td>

</tr>

<tr style="height: 18px;">

<td style="width: 15.6556%; height: 18px; text-align: center;">or</td>

<td style="width: 19.5127%; height: 18px;">Logical OR</td>

<td style="width: 64.724%; height: 18px;">

If any of the two operands is true or non-zero, then the condition is true.

</td>

</tr>

<tr style="height: 18px;">

<td style="width: 15.6556%; height: 18px; text-align: center;">not�</td>

<td style="width: 19.5127%; height: 18px;">Logical NOT</td>

<td style="width: 64.724%; height: 18px;">

It is used to reverse the logical state of the operand (true if an operand is false).

</td>

</tr>

</tbody>

</table>

Now we will see <span style="background-color: #ccffff;">Truth</span> <span style="background-color: #ccffff;">Table</span> of logical operations <span style="background-color: #ccffff;">and</span>, <span style="background-color: #ccffff;">or</span>, <span style="background-color: #ccffff;">not�</span>so we can easily understand the working of logical operators.

Only if both the operands are <span style="background-color: #ccffff;">True</span> then <span style="background-color: #ccffff;">and</span> will result in <span style="background-color: #ccffff;">True</span>.

#### The Truth table for <span style="background-color: #ccffff;">and</span>

<table style="border-collapse: collapse; width: 100%;" border="1">

<tbody>

<tr style="height: 16px;">

<td style="width: 2.1692%; height: 16px; text-align: center;">**A**</td>

<td style="width: 2.1692%; height: 16px; text-align: center;">**�B**</td>

<td style="width: 2.1692%; height: 16px; text-align: center;">**A and B**</td>

</tr>

<tr style="height: 18px;">

<td style="width: 2.1692%; height: 18px;">True</td>

<td style="width: 2.1692%; height: 18px;">True</td>

<td style="width: 2.1692%; height: 18px;">True</td>

</tr>

<tr style="height: 18px;">

<td style="width: 2.1692%; height: 18px;">True</td>

<td style="width: 2.1692%; height: 18px;">False</td>

<td style="width: 2.1692%; height: 18px;">False</td>

</tr>

<tr style="height: 18px;">

<td style="width: 2.1692%; height: 18px;">False</td>

<td style="width: 2.1692%; height: 18px;">True</td>

<td style="width: 2.1692%; height: 18px;">False</td>

</tr>

<tr style="height: 18px;">

<td style="width: 2.1692%; height: 18px;">False</td>

<td style="width: 2.1692%; height: 18px;">False</td>

<td style="width: 2.1692%; height: 18px;">False</td>

</tr>

</tbody>

</table>

If any of the operands is <span style="background-color: #ccffff;">True</span>, then <span style="background-color: #ccffff;">or</span> will result in <span style="background-color: #ccffff;">True</span>.

#### **The Truth table for <span style="background-color: #ccffff;">or�</span>**

<table style="border-collapse: collapse; width: 100%;" border="1">

<tbody>

<tr>

<td style="width: 1.09649%; text-align: center;">**A**</td>

<td style="width: 1.09649%; text-align: center;">**B**</td>

<td style="width: 1.09649%; text-align: center;">**A or B**</td>

</tr>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px;">True</td>

<td style="width: 1.09649%; height: 18px;">True</td>

<td style="width: 1.09649%; height: 18px;">True</td>

</tr>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px;">True</td>

<td style="width: 1.09649%; height: 18px;">False</td>

<td style="width: 1.09649%; height: 18px;">True</td>

</tr>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px;">False</td>

<td style="width: 1.09649%; height: 18px;">True</td>

<td style="width: 1.09649%; height: 18px;">True</td>

</tr>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px;">False</td>

<td style="width: 1.09649%; height: 18px;">False</td>

<td style="width: 1.09649%; height: 18px;">False</td>

</tr>

</tbody>

</table>

The <span style="background-color: #ccffff;">not</span> operator inverts the truth value.

**The Truth table for <span style="background-color: #ccffff;">not</span>**

<table style="border-collapse: collapse; width: 100%;" border="1">

<tbody>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px; text-align: center;">**A**</td>

<td style="width: 1.09649%; height: 18px; text-align: center;">**not A**</td>

</tr>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px;">True</td>

<td style="width: 1.09649%; height: 18px;">False</td>

</tr>

<tr style="height: 18px;">

<td style="width: 1.09649%; height: 18px;">False</td>

<td style="width: 1.09649%; height: 18px;">True</td>

</tr>

</tbody>

</table>

### **Example**

Now we will see the implementation of Logical Operators by the following example.

<iframe src="https://repl.it/@ShailiDashora/Logical-Operator?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>