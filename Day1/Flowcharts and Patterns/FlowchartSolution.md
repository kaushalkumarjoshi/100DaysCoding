**A1. Assuming that the numbers are passed as individual parameters.
Write a function that takes three integer numbers, adds them and divides by 3 and returns the resulting value.**

### Steps:

1. Start.
2. Declare varibles num1, num2 and num3.
3. Take input for the above variables.
4. Declare variable sum = num1 + num2 + num3.
5. Declare variable avg = sum / 3.
6. Print average.
7. Stop.

**A2. Print 1 if number is positive. Print -1 if number is negative. Print 0, if it's equal to 0.**

### Steps:

1. Start.
2. Declare variable num.
3. Take input for the num variable.
4. Check if num is greater than 0. If true print 1.
5. Check if num is less than 0, if true print -1.
6. Else print 0.
7. Stop.

**A3. Check if 3 numbers which represent length of a line can form a valid triangle. Print true if true else print false.**

### Steps:

1. Start.
2. Declare three variables num1, num2 and num3.
3. Take input for the above variables.
4. Check if condition num1 + num2 > num3. if false print false and go to step 8 else go to step 5.
5. Check if condition num2 + num3 > num1, if false print false and go to step 8 else go to step 6.
6. Check if condition num3 + num1 > num2, if false print false and go to step 8 else go to step 7.
7. Print true.
8. Stop.

**A4. Factorial of a non-negative number.**

### Steps:

1. Start.
2. Declare a variable num.
3. Take input for num.
4. Create a variable, result initialized to 1
5. Check if num is zero. go to step 10 if true. Else move to next step.
6. Check if num is 1. go to step 10 if true. Else move to next step.
7. If num is greater than 1, result *= num
8. Decrease num by 1
9. Go to step 6.
10. Print result.
11. Stop.

**A5. Print Even numbers between 1 and N (all inclusive).**

### Steps:

1. Start.
2. Declare a variable num.
3. Take input for num.
4. Check num <= 1. If true, go to step 9 else go to next step.
5. Create a variable i and initialize to 2.
6. Print i.
7. Add 2 to i.
8. Check i <= num. If true, go to step 6. Else go to next step.
9. Stop.

**A6. Given length of three sides of a triangle, print 1 if it is equilateral. print 0 of it is isosceles, print -1 if it is scalene.**

1. Start.
2. Declare three variables num1, num2 and num3.
3. Take input for the above variables.
4. If num1 == num2 && num2 == num3, if true, print 1 and go to step 7 else go to next step.
5. If num1 == num2 || num2 == num3, if true, print 0 and go to step 7 else go to next step.
6. If num1 != num2 && num2 != num3, if true, print -1 and go to next step.
7. Stop

**A7. Print Sum of Even numbers between 1 and N (all inclusive).**

### Steps:

1. Start.
2. Declare a variable num.
3. Take input for num.
4. Check num <= 1. If true, go to step 9 else go to next step.
5. Create a variable i and initialize to 2.
6. Create a variable sum and initialize to 0.
7. Add sum and i.
8. Add 2 to i.
8. Check i <= num. If true, go to step 7. Else go to next step.
9. Print sum.
10. Stop.