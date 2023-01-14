# when-will-they-stop

Marked Pogramming Assignment 2 for the "More C# Programming and Unity" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

## Description

Assignment Description  

You want to develop a program that takes in as many positive integers as the user wants to enter and then tells them how many integers they entered and the mean (average) of those numbers. This will also give you more practice implementing while loops!

In this assignment, you'll get integer numbers until you get a -1, at which point you’ll print how many numbers you processed (not including the -1) and the mean of those numbers (not including the -1).

Requirements

The code I’ve provided in the Program.cs file reads in a set of integers that ends with -1. Your code must call the GetValue method and store the int the method returns in a variable, then process that number as appropriate. 

Your solution must print the following on a single line:

    The count of the numbers you processed (not including the -1)

    A space

    The mean of the numbers you processed (not including the -1)

For example, if the set of numbers you process is 1 2 3 4 -1, your output should be the following on a single line:

4 2.5

We’d typically label our output to tell the user what the output means, but that will just confuse the automated grader. You must print ONLY the values described above in your output, with the values appearing on a single line with a single space between them.

Note: For the special case when -1 is the first number, your count and mean should both be set to 0.

Running Your Code

Because of the code I included to work with the automated grader on Coursera, when you run your program the command prompt window will open and it will sit there doing nothing. To make your code run, type in a set of integers, ending with -1, with a space between each integer, and press the <Enter> key; your code should then run so you can check your output. For example, your input could be: 

1 2 3 4 -1

You can actually run your code again if you want to by typing in a set of integers, ending with -1, with a space between each integer, and pressing the <Enter> key again. When you’re ready to stop running your code, type q (for quit).

Here's what running the code multiple times with different inputs should look like (remember, you're including a newline at the end of each of your output lines). The first line is the integer input, the second line is your output line, and so on:

1 2 3 4 -1

4 2.5

-2 0 -1

2 -1

q

Test Case Inputs

The automated grader uses the following set of test case inputs to test your code (1 test case per line):

1 2 3 4 -1

-1

-2 0 -1

1 1 1 1 1 -1

2 1 0 1 2 -1

-1

-2 -3 -4 -1

-2 0 2 -1

5 5 5 5 5 5 5 5 5 1 -1

1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 -1

You should figure out what the expected results are for each test case input and make sure your code is generating those expected results in the required format before submitting your code for grading.

## Getting Started

n/a

### Dependencies

* Windows 10
+ Microsoft Visual Studio
+ .NET

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/when-will-they-stop)

### Executing program

1. Open the project's root folder
2. Open the _ProgrammingAssigment2_ folder
2. Open the _ProgrammingAssignment2.sln_ file in Microsoft Visual Studio
3. Run _Program.cs_

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## License

n/a

## Acknowledgments

Problem provided by the _University of Colorado_ and _Coursera_
