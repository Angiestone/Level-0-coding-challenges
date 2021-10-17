Python 3.9.7 (tags/v3.9.7:1016ef3, Aug 30 2021, 20:19:38) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> x = 0
>>> y = 1
>>> print (x)
0
>>> print (y)
1
>>> x = x + 3
>>> y = y + x
>>> print (x)
3
>>> print (y)
4
>>>
>>>
>>> x = 1 + 1 * 2
>>> y = (1 + 1) * 2
>>> z = 1 + ( 1 * 2 )
>>> a = 1 + 1 * 2 / 2
>>> b = (1 + 1 * 2 ) /  2
>>> print (x)
3
>>> Print (y)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'Print' is not defined
>>> print (y)
4
>>> print (z)
3
>>> print (a)
2.0
>>>
>>> print (b)
1.5
>>>
>>>
>>> name = input("Enter your name: ")
Enter your name: Angie
>>> print("Hello", name + "!")
Hello Angie!
>>>
>>>
>>> even_or_odd = int(input("Enter a number: "))
Enter a number: 8
>>> if (even_or_odd % 2) == 0:
... print(" Even")
  File "<stdin>", line 2
    print(" Even")
    ^
IndentationError: expected an indented block
>>> print(" Odd ")
 Odd
>>>
>>>
>>> a = float(input('Enter first side: '))
Enter first side: 3
>>> b = float(input('Enter second side: '))
Enter second side: 5
>>> c = float(input('Enter third side: '))
Enter third side: 3
>>> # calculate the semi-perimeter
>>> s = (a + b + c) / 2
>>>
>>> # calculate the area
>>> area = (s * (s - a) * (s - b) * (s - c)) ** 0.5
>>> print(' area of the triangle is %0.2f' % area)
 area of the triangle is 4.15
>>>
>>>
>>> a =  int(input('Enter number: '))
Enter number: 7
>>> b =  int(input('Enter number: '))
Enter number: 8
>>> c =  int(input('Enter number: '))
Enter number: 9
>>> print("Maximum number is", max(a, b, c))
Maximum number is 9
>>>
>>>
>>> celsius = float(input("Enter temperature in celsius: "))
Enter temperature in celsius: 24
>>> fahrenheit = (celsius * 9/5) + 32
>>> print('%.2f Celsius is: %0.2f Fahrenheit' %(celsius, fahrenheit))
24.00 Celsius is: 75.20 Fahrenheit
>>> fahrenheit = float(input("Enter temperature in fahrenheit: "))
Enter temperature in fahrenheit: 24
>>> celsius = (fahrenheit - 32) * 5/9
>>> print('%.2f Fahrenheit is: %0.2f Celsius' %(fahrenheit, celsius))
24.00 Fahrenheit is: -4.44 Celsius
>>>
>>>
>>> total_time = int(input("Enter a number for time: "))
Enter a number for time: 97
>>> hours = int(total_time) / 60
>>> minutes = int(total_time % hours)
>>> print("Time is %d hours" % (hours),", "  "%d minutes" %(minutes))
Time is 1 hours , 1 minutes
>>>
