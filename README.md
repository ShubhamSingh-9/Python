# Python

## Function 
It's a mathematical concept that relates an input to an output. For any simple input to the function, there is a corresponding output that follows a certain rule or pattern. For example, the function f(x) = 2x takes any number x as an input and returns twice that number as an output.

## Data Type:
A program can handle different types of data depending on the programming language and the data structures used. Some common data types are integers, floats, strings, booleans, arrays, lists, dictionaries, and objects. Each data type has its properties and operations that can be performed on it. A program can handle multiple data types by using variables, constants, expressions, statements, functions, and classes.

### 1. Integers 
These are numbers that can be positive or negative, such as 1, -2, 3, -4, and so on. They do not have any fractional or decimal parts. Integers can be used to represent discrete quantities, such as the number of students in a class, the number of apples in a basket, or the score of a game. The maximum value that an integer can handle is 10^308, which is a very large number. Beyond this limit, the integer may overflow or cause an error.

### 2. Decimal or Float 
Data type is used to store numerical values that have fractional parts. For example, 3.14, 0.5, and -2.7 are all decimal or float values. The decimal or float data type can handle very large or very small numbers, up to 10^308 in magnitude. This means that the number can have up to 308 digits before the decimal point, or after the decimal point if it is negative.

## Operators in Python
### 1. Arithmetic Operators are symbols that perform mathematical operations on one or more operands. In this blog post, we will review some of the most common arithmetic operators in Python and how to use them.

The basic arithmetic operators are:

+: Addition. It adds the values of the operands and returns the result. For example, 3 + 5 = 8.
-: Subtraction. It subtracts the value of the right operand from the left operand and returns the result. For example, 10 - 7 = 3.
x: Multiplication. It multiplies the values of the operands and returns the result. For example, 4 x 6 = 24.
/: Division. It divides the value of the left operand by the right operand and returns the result. For example, 12 / 4 = 3.
//: Integer Division. It divides the value of the left operand by the right operand and returns the integer value of the quotient. For example, 15 // 4 = 3.

These operators can be used with different types of operands, such as integers, floats, strings, lists, etc. However, some operators may not work with certain types or combinations of types. For example, you cannot use x to multiply a string by a list. In such cases, you will get a TypeError.

To use these operators, you simply write them between the operands in an expression. For example:

a = 10
b = 3
c = a + b # c is 13
d = a - b # d is 7
e = a x b # e is 30
f = a / b # f is 3.3333333333333335
g = a // b # g is 3

You can also use parentheses to change the order of operations or to group expressions. For example:

h = (a + b) x c # h is 390
i = a + (b x c) # i is 49
j = (a + b) / (c - d) # j is 2.6
k = a + b / c - d # k is -2.769230769230769


### 2. Relatioanl Operators:
Relational operators are symbols that compare two values and return a boolean result (true or false). They are often used in conditional statements, such as if, while, or for, to control the flow of a program. Here are some common relational operators in most programming languages:

> : greater than. Returns true if the left operand is larger than the right operand, false otherwise. For example, 5 > 3 is true, but 2 > 4 is false.
< : less than. Returns true if the left operand is smaller than the right operand, false otherwise. For example, 2 < 4 is true, but 5 < 3 is false.
= : assignment. Assigns the value of the right operand to the left operand. For example, x = 10 means that the variable x now holds the value 10. This is not a relational operator, but it is often confused with one.
== : equal to. Returns true if the left and right operands have the same value, false otherwise. For example, 5 == 5 is true, but 5 == 3 is false.
!= : not equal to. Returns true if the left and right operands have different values, false otherwise. For example, 5 != 3 is true, but 5 != 5 is false.
>= : greater than or equal to. Returns true if the left operand is larger than or equal to the right operand, false otherwise. For example, 5 >= 3 is true, but 2 >= 4 is false.
<= : less than or equal to. Returns true if the left operand is smaller than or equal to the right operand, false otherwise. For example, 2 <= 4 is true, but 5 <= 3 is false.
These are some of the basic relational operators that you will encounter in programming. They can help you write more expressive and logical code that can handle different situations and inputs.

### 3. Logical operators:
Logical operators are symbols that allow us to combine or manipulate boolean values, which are either true (1) or false (0). In this blog post, we will explore three common logical operators: and, or, and not.
The and operator, denoted by &, returns true only when both operands are true. For example, 1 & 1 = 1, but 1 & 0 = 0, 0 & 1 = 0, and 0 & 0 = 0. We can think of the and operator as a way of checking if both conditions are satisfied.
The or operator, denoted by |, returns true when at least one operand is true. For example, 1 | 1 = 1, 1 | 0 = 1, 0 | 1 = 1, but 0 | 0 = 0. We can think of the or operator as a way of checking if either condition is satisfied.
The not operator, denoted by !, returns the opposite of the operand. For example, !1 = 0 and !0 = 1. We can think of the not operator as a way of negating or flipping the value.
Logical operators are useful for creating complex boolean expressions that can control the flow of a program. For example, we can use logical operators to check if a number is divisible by both 2 and 3, or if a user input is valid or not.

### 4. Bitwise Opeartors:
Bitwise operators are a powerful tool for manipulating bits in binary numbers. They can be used for various purposes, such as encryption, compression, error detection, and more. In this blog post, we will explore three common bitwise operators: AND, OR, and XOR.
The AND operator (&) takes two binary numbers and returns a new binary number that has a 1 in each bit position where both inputs have a 1.
For example, 2 in binary is 0010 and 3 in binary is 0011. If we apply the AND operator to them, we get 0010, which is 2 in decimal. The AND operator can be used to mask out certain bits or check if a bit is set.
The OR operator (|) takes two binary numbers and returns a new binary number that has a 1 in each bit position where either input has a 1.
For example, 2 in binary is 0010 and 3 in binary is 0011. If we apply the OR operator to them, we get 0011, which is 3 in decimal. The OR operator can be used to set certain bits or combine multiple flags.
The XOR operator (^) takes two binary numbers and returns a new binary number that has a 1 in each bit position where the inputs have different values.
For example, 2 in binary is 0010 and 3 in binary is 0011. If we apply the XOR operator to them, we get 0001, which is 1 in decimal. The XOR operator can be used to toggle certain bits or perform arithmetic operations.
These are just some of the applications of bitwise operators. They are very useful for low-level programming and optimization. 
