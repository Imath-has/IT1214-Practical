Introduction to Java
Student: 2022/ICT/111 IMATH HASAN M.A.
Submitted on: Thursday, 06 May 2025, 11:49 PM

Objectives:
To understand:

How to pass and read command line arguments in Java.

The difference between print() and println().

How Java supports inheritance and how to create multiple objects with different values.

 Theory/Concept:
Command line arguments are passed while running the Java program using:

bash
Copy
Edit
java ClassName arg1 arg2 ...
The values are stored in args[] as strings, which can be printed or converted.

System.out.print() keeps printing on the same line, while System.out.println() moves the cursor to the next line.

Inheritance in Java allows one class to inherit properties and methods from another using the extends keyword.

Constructors can be used to assign values and print them through object creation.

 Algorithm:
Write a main class that accepts command line arguments.

Read the arguments using args[0], args[1], etc.

Use print() and println() to understand output differences.

Create a base class (e.g., ClassOne) and derived class (e.g., ClassTwo) with constructors.

Instantiate multiple objects with different values and print the properties.

Source Code:
View on GitHub

 Sample Output:
(a) Command Line Program Output:
Command:

bash
Copy
Edit
java MySecondClass zero one two Hi Ann
Output:

vbnet
Copy
Edit
The first argument is zero  
The second argument is one  
The third argument is two  
hi Ann i'm
(b) Print and Println Program Output:
Command:

bash
Copy
Edit
java MyFirstClass
Output:

pgsql
Copy
Edit
This is IT1214 Practical session 1This prints next in a new line  
This is a new line
(c) Inheritance Program Output:
Command:

bash
Copy
Edit
java App
Output:

vbnet
Copy
Edit
From Class One a =10  
From Class One b =100  
From Class Two a =10  
From Class Two b =100  
From Class Two a =20  
From Class Two b =200
 Observation:
All command line arguments were passed and accessed correctly.

The behavior of print() and println() was demonstrated as expected.

Object creation and value assignment through constructors worked as per inheritance logic.

 Conclusion:
This session demonstrated how to:

Accept command line inputs.

Use print formatting techniques.

Apply object-oriented programming concepts such as inheritance in Java.

It showed how different features of Java work together to create flexible and structured programs.
