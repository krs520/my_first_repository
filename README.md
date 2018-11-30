# my_first_repository

Kaitlin Slattery - Data Bootcamp Homework 1
https://github.com/krs520
1. Describe and explain what each of these expressions produces in basic Python:
2+5
Sum of 2 and 5
2 + 5
Sum of 2 and 5
2*5
Mutliplies 2 times 5
2/5
2 divided by 5
2**3
Raises 2 to the power of 3
In [1]:

print(2+5)
print(2 + 5)
print(2*5)
print(2/5)
print(2**3)
7
7
10
0.4
8
2. What is the value of x after running these statements in order? Why?
x = 7
x = x + 3
The value of x is 10. When coding in Python the last assignment to a variable is saved.
In [2]:

x = 7 
x = x +3
In [3]:

x
Out[3]:
10
3. What is the value of y after running these statements in order? Of x? Why?
x = 3
y = x
x = 10
The value of y is 3 and the value of x is '10' again because Python saves the last assignment to a variable. If I were to re-run y = x then the value of y would change.
In [4]:

x = 3 
y = x 
x = 10 
In [5]:

print(y)
print(x)
3
10
4. Does this code run without error? If so, what does it produce? If not, explain why.
x = 3
x = x/2
x will be stored as 1.5
y = 'abc'
z = y + y
you can add two strings together, will be stored as abcabc
print(x, z)
1.5 abcabc
In [6]:

x = 3 
x = x/2
y = 'abc'
z = y + y 
print(x,z)
1.5 abcabc
5. Does this code run without error? If so, what does it produce? If not, explain why.
x = 3
x = x/2
x will be stored as 1.5
y = 'abc'
z = x + y
Error, python can not add a string and a floating number together
print(x,z)
Will not run due to z error
In [7]:

x = 3 
x = x/2
y = 'abc'
z = x + y 
print(x, z)
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
<ipython-input-7-c66421ef3fa9> in <module>()
      2 x = x/2
      3 y = 'abc'
----> 4 z = x + y
      5 print(x, z)

TypeError: unsupported operand type(s) for +: 'float' and 'str'

6. Does this code run without error? If so, what does it produce? If not, explain why.
x = 3
y = 24
z = y / x
z will be stored as 8
print(x, y, z, sep=' | ')
3 | 24 | 8
In [10]:
