README
Introduction
This repository contains a set of Python scripts and a C program designed to demonstrate basic programming concepts. Each script or program addresses specific tasks related to conditional statements, loops, functions, and linked lists.

Files
0-positive_or_negative.py: Assigns a random signed number to a variable and prints whether the number is positive, negative, or zero.

1-last_digit.py: Assigns a random signed number to a variable and prints the last digit along with certain conditions.

2-print_alphabet.py: Prints the ASCII alphabet in lowercase without a new line.

3-print_alphabt.py: Prints the ASCII alphabet in lowercase excluding the letters 'q' and 'e'.

4-print_hexa.py: Prints numbers from 0 to 98 in both decimal and hexadecimal.

5-print_comb2.py: Prints numbers from 0 to 99, separated by commas and spaces.

6-print_comb3.py: Prints all possible combinations of two digits in ascending order.

7-islower.py: Defines a function islower(c) that checks if a character is lowercase.

8-uppercase.py: Defines a function uppercase(str) that prints a string in uppercase.

9-print_last_digit.py: Defines a function print_last_digit(number) that prints the last digit of a number.

10-add.py: Defines a function add(a, b) that adds two integers and returns the result.

11-pow.py: Defines a function pow(a, b) that computes a to the power of b.

12-fizzbuzz.py: Defines a function fizzbuzz() that prints numbers from 1 to 100 with specific conditions.

linked_lists.c: Contains functions for working with singly linked lists, including printing, adding nodes at the end, and freeing the list.

lists.h: Header file for the linked list functions.

13-insert_number.c: Defines a function insert_node to insert a number into a sorted singly linked list.

13-main.c: Main program to test the insertion of a number into a sorted singly linked list.

How to Use
To run the Python scripts, use the command python <filename.py>. For the C program, compile it using gcc -Wall -Werror -Wextra -pedantic -std=gnu89 <main.c> linked_lists.c 13-insert_number.c -o insert and execute the compiled program
