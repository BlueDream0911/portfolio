# Java-Portfolio
These are some challenging java programs and kind of awesome!

Welcome to [Rajesh's](http://www.rajeshsurana.com) Java Portfolio! Here is the list of some of the problem statement that I solved using Amazing Java!

## 1. Cracking the coding interview

This is a practice book on interview coding questions. I solved some of the problems from this book. Here is the list->

### 1. String Processing - [View Code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/crackingTheCodingInterview/StringPrac/src/stringprac/StringPrac.java)

* Implement an algorithm to determine if a string has all unique characters. What if you cannot use additional data structures?
* Given two strings, write a method to decide if one is a permutation of the other.
* Write a method to replace all spaces in a string with '%20'. You may assume that the string has sufficient space at the end of the string to hold the additional characters, and that you are given the "true" length of the string. (Note: if implementing in Java, please use a character array so that you can perform this operation in place.)
* Implement a method to perform basic string compression using the counts of repeated characters. For example, the string aabcccccaaa would become a2blc5a3. If the "compressed" string would not become smaller than the original string, your method should return the original string.
* Assume you have a method isSubstring which checks if one word is a substring of another. Given two strings, s1 and s2, write code to check if s2 is a rotation of s1 using only one call to isSubstring (e.g., "waterbottLe" is a rotation of "erbottLewat").

## 2. Hacker Rank

This is an online coding website. Here are some of the problems that I enjoyed solving->

### 1. Algorithm

These are the problems from algorithm section ->

* You are given a square matrix of size . Calculate the absolute difference of the sums across the two main diagonals. [Code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/HackerRank/HackerRank/src/hackerrank/DiagonalDiff.java)
* Your teacher has given you the task to draw the structure of a staircase. Being an expert programmer, you decided to make a program for the same. You are given the height of the staircase. You need to print a staircase as shown in the example. [Code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/HackerRank/HackerRank/src/hackerrank/StairCase.java)
* You are given time in AM/PM format. Convert this into a 24 hour format. Note Midnight is 12:00:00AM or 00:00:00 and 12 Noon is 12:00:00. [Code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/HackerRank/HackerRank/src/hackerrank/timeFormat24.java)

## 3. Miscellaneous

Coding practive around the internet.

### 1. Binary Tree [View Code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/BinaryTree/src/binarytree/BinaryTree.java)
* Returns true if given given target is in the binary tree.
* Insert given data into binary tree.
* Returns the number of nodes in the tree.
* Returns the max root-to-leaf depth of the tree. 
* Returns the min value in a non-empty binary search tree.
* Returns the max value in a non-empty binary search tree.
* Prints the node values in the "inorder" order.
* Given a tree and a sum, returns true if there is a path from the root down to a leaf, such that adding up all the values along the path equals the given sum.
* Changes the tree into its mirror image.
* Changes the tree by inserting a duplicate node on each nodes's .left.
* Compares the receiver to another tree to see if they are structurally identical. 
* Tests if a tree meets the conditions to be a binary search tree (BST).

### 2. Mixed Problems
* Given an array and target element, implement binary search. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/BinarySearchImpl.java)
* Given a number and its base, convert it to decimal number. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/DecimalConverter.java)
* Given graph and target element, search whether element presents in graph using depth-first search algorithm. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/DepthFirstSearch.java)
* Given number n, find nth number in Fibonacci sequence using recursion. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/Fibonacci.java) 
* Given two numbers, find GCD of those numbers using recursion. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/GCD.java) 
* Given maze in the form of two dimensional array, find if there is a path from starting position 'S' to end position 'E'. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/MazePathFinder.java)
* Given set of elements, find power set of that set i.e. all combinations of elements from set. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/PowerSet.java)
* Given number, check if its prime. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/PrimeChecker.java)
* Given number n, find all prime numbers up to n using Sieve of Eratosthenes algorithm [fastest till date]. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/PrimeSieve.java) 
* Assume that your language doesn't provide HashTable, implement one. [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/Miscellaneous/SimpleHashTable.java)

## 4. Creational Pattern [view code](https://github.com/rajeshsurana/Java-Portfolio/tree/master/CreationalPatterns_Eclipse)
This project implements **Singleton**, **Abstract Factory** and **Factory pattern**.

Write a program that creates and prints out the gradebook for a class.  The class consists of 2 kind of students: Graduate and Undergraduate and they have different grading criteria.  The source feed for these 2 students is also in different formats.  Graduate grades are store in an XML format and Undergraduate grades are in JSON format.

`Grades.xml – XML data file for the student’s grades`

`Grades.json – JSON data file for the student’s grades`

### After reading in the appropriate grades from the XML or JSON file, the full gradebook showing 

`•	Student Name`

`•	Student ID`

`•	Each Assigned work grouping with corresponding grades e.g., all Assignments together, all exams together, all quizzes together, …; in chronological order within the assigned work grouping`

`•	Final letter grade`

Note that he grade for an assigned work item can be numeric e.g., 88.5, or letter Grade e.g., A+.  More grading notations are expected.  To work out the final letter grade you need to get a numeric score.  If the original grade was numeric then return the numeric grade, if the score is a letter grade then return the median of the spread for that letter grade.  Use the class syllabus as the guide.

### Implementation Constraints:

•	You will need Factory Methods for reading in and outputting the Gradebook.  You will also need a Factory Method for the Grade.  More may be needed

•	A class is either an undergraduate class or a graduate class, so you will need an Abstract Factory (a.k.a Kit) Pattern to implement the creational classes/objects for the different class gradebooks.  

•	Your program can exploit knowledge of the project’s file structure, but cannot assume knowledge on the directory structure outside the project.  One thing this means is that you need to use relative addressing for the path to the input files rather than fixed addressing.  If you hardcode in a path specific to you machine you can be sure it will fail on my machine.

### How to run the project? 
Please refer this document (click on 'View Raw') for instructions. [[document](https://github.com/rajeshsurana/Java-Portfolio/blob/master/CreationalPatterns_Eclipse/Instructions_to_Run_Project.docx)]

### Snapshot of application GUI

![Creational Pattern](https://raw.githubusercontent.com/rajeshsurana/Java-Portfolio/master/Images/Creational_Pattern.png)

## 5. Algorithm Design by Jon Kleinberg & Éva Tardos

Here is my attempt to convert some of the interesting algorithms into java code. I tried to make them as much simple and optimal as possible.

### 1. Greedy Algorithms [4th chapter]
*  **Interval Scheduling** - [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/GreedyAlgorithms/IntervalScheduling.java)

We have a set of requests {1, 2 ..... n}; the ith request corresponds to an interval of time starting at s(i) and finishing at f(i). We’ll say that a subset of the requests is compatible if no two of them overlap in time, and our goal is to accept as large a compatible subset as possible. Compatible sets of maximum size will be called optimal.

* **All Interval Scheduling** - [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/GreedyAlgorithms/AllIntervalScheduling.java)

If we have many identical resources available and we wish to schedule all the requests’ using as few resources as possible. Goal here is to partition all intervals across multiple resources.
***
### 2. Dynamic Programming [6th chapter]
*  **Weighted Interval Scheduling** - [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/DynamicProgramming/WeightedIntervalScheduling.java)

The Weighted Interval Scheduling Problem is a strictly more general version, in which each interval has a certain
value (or weight), and we want to accept a set of maximum value.

*  **Knacksack Problem** - [view code](https://github.com/rajeshsurana/Java-Portfolio/blob/master/DynamicProgramming/KnapsackProblem.java) 

Consider a situation in which each item i has a nonnegative weight wi as before, and also a distinct value vi. Our goal is now to find a subset S of maximum value, subject to the restriction that the total weight of the set should not exceed W.


## 6. Threaded Design Pattern [[view code](https://github.com/rajeshsurana/Java-Portfolio/tree/master/ThreadedDesignPatterns_NetBeans)]
This project implements **Model-View-Controller**, **Intercepting Design Pattern**.

Background: many companies and applications have rules in place with respect to input/output data.  For example:
1. Call centers will often filter input messages for words they deem offensive
2. Companies will filter passwords to catch passwords that would be too easy to guess.  E.g., a Disney employee using Disney character names for their password
3. Salting a password.  This is the process of adding a known string to a user password to make it harder to break

Your assignment is to implement an MVC pattern that takes as input a password and will display the password and a message if it is valid or invalid according to a set of rules.  You input screen should be form based and allow the user the select the password filter to apply and in what order.
Your filter on the password check should use the Intercepting filter to insert the password checks between the Controller and the Model.

### How to run the project? 
Please refer this document for instructions. [[document](https://github.com/rajeshsurana/Java-Portfolio/blob/master/ThreadedDesignPatterns_NetBeans/Instructions_to_Run_Project.pdf)]

### Snapshot of application GUI

![Password Validator - Threaded Design Pattern](https://raw.githubusercontent.com/rajeshsurana/Java-Portfolio/master/Images/Threaded_Pattern.png)
