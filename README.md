# EnterNumbers

Write a method readNumber(int start, int end) that enters an integer number in a given range [start…end], excluding the numbers start and end. If an invalid number or a non-number text is entered, the method should throw an exception. Using this method, write a program that enters 10 numbers: a1, a2, … a10, such that 1 < a1 < … < a10 < 100. If the user enters an invalid number, continue while there are 10 valid numbers entered. Print the array elements, separated with comma and space ", ".

Hints
---------------

· When the entered input holds a non-integer value, print "Invalid Number!".

· When the entered input holds an integer that is out of range, print "Your number is not in range {currentNumber} - 100!".

Examples
--------------------

Input | Output
------|-----------
2|11 2, 3, 4, 5, 6, 7, 8, 9, 10, 11
3|
4|
5|
6|
7|
8|
9|
10|

Input | Output
------|-----------
1| 11 Your number is not in range (1 - 100)  
2|Your number is not in range (2 – 100)
1| Invalid Number!
3|2, 3, 4, 5, 6, 7, 8, 9, 10, 1
p|
4|
5|
6|
7|
8|
9|
10|

