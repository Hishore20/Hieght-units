# Hieght-units



Many people think about their height in feet and inches, even in some countries that primarily use the metric system.

Write a program that reads a number of feet from the user, followed by a number of inches.

Once these values are read, your program should compute and display the equivalent number of centimeters.

Hint: One foot is 12 inches. One inch is 2.54 centimeters.
Logic Test Case 1

Input (stdin)
5

7

Expected Output

Your height in centimeters is 170.18
Logic Test Case 2

Input (stdin)
6

2

Expected Output

Your height in centimeters is 187.96











a=int(input())
b=int(input())
b+=a*12
c=(b*2.54)
print('Your height in centimeters is %.2f'%c)
