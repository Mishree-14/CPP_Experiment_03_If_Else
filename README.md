# C++ Experiment 3: Understanding and Using Decision-Making Statements

## Aim
To learn how decision-making works in C++ using if, else if, and else.

To check conditions using relational and logical operators.

## Objectives
Use if, else if, and else to write programs for:

  Checking if a number is positive, negative, or zero.

  Giving grades to a student based on average marks.

  Finding the quadrant of a point (x, y) in coordinate system.

Understand the use of relational operators like >, <, >=, <=.

Use logical operators like &&, ||, ==.

## Theory
Decision-making statements help the program decide what to do based on a condition (true or false).

The most common statements used are if, else if, and else.

if statement runs a block of code only if the condition is true.

else if statement checks another condition if the first if is false.

else statement runs when none of the if or else if conditions are true.

Conditions are written inside parentheses () after if, else if.

Code to run under each condition is placed inside curly braces {}.

We can compare values using relational operators:
 > (greater than), < (less than), >=, <=, == (equal), != (not equal)

Logical operators help join conditions:
&& (AND), || (OR), ! (NOT)

These statements help create flexible programs that can behave differently for different inputs.

Used in real-life examples like:

Checking grades

Classifying numbers

Finding coordinate positions (like quadrant)

These decision-making statements are essential for all programs that need to make choices.

## Program Description
### Syntax and Flow
First, we declare variables to store user inputs like marks, x, y, etc.

The condition is checked inside parentheses ( ) after if.

The code block that should run when the condition is true is written inside curly braces { }.

If one condition is false, it checks the next using else if. If none match, the else part runs.

### Using If-Else
C++ checks whether a condition is true (1) or false (0).

If it is true, the if block runs.

If false, the next option (else if or else) runs.

## Concepts Used
If-Else statements

Relational Operators: >, <, >=, <=

Logical Operators: && (AND), || (OR), == (equal to) 

## Sample Output

#### Finding whether the number is positive or negative
```
Value of a: 17
Value of b: -8
A is a +ve number.
B is a -ve number.
```
#### Grade calculator 
```
Marks of subject 1 : 24
Marks of subject 2 : 76
Marks of subject 3 : 65
Marks of subject 4 : 89
Marks of subject 5 : 94
Grade A+
```
#### Quadrant Finder
```
Value for x: 7
Value for y: -4
4th Quadrant
```
```
Value for x: 0
Value for y: 0
Origin
```
