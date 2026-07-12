# APC---Arbitrary-Precision-Calculator
Designed and implemented an Arbitrary Precision Calculator in C that performs arithmetic operations on very large integers using doubly linked lists. The project demonstrates dynamic memory allocation, pointer manipulation, sign handling, carry/borrow management, and modular programming to overcome built-in data type limitations


# Arbitrary Precision Calculator (APC) using C

The **Arbitrary Precision Calculator (APC)** is a Data Structures project developed in **C** to perform arithmetic operations on integers of unlimited length. Unlike standard calculators that are restricted by the size of built-in data types, this project uses **Doubly Linked Lists** to represent each digit as a separate node, enabling calculations on very large numbers without overflow. The calculator supports **addition, subtraction, multiplication, and division** while efficiently handling positive and negative integers.

The project follows a modular programming approach by separating the implementation into multiple source files, making the code organized, reusable, and easy to maintain. Each arithmetic operation is implemented using node-based algorithms that perform digit-by-digit calculations, including proper carry and borrow handling. Dynamic memory allocation is used to create and manage linked list nodes during runtime, ensuring efficient memory utilization.

Special attention is given to handling different sign combinations, removing leading zeros, comparing operands, and validating command-line arguments before performing calculations. The project demonstrates how fundamental data structure concepts can be applied to solve real-world computational problems that exceed the limitations of primitive data types.

This project significantly improved my understanding of **C programming, pointers, dynamic memory allocation, linked list operations, and algorithm design**. It also strengthened my debugging and problem-solving skills by implementing complex arithmetic logic using custom data structures instead of relying on built-in numerical types.

## Features

* Supports Addition, Subtraction, Multiplication, and Division.
* Performs arithmetic on integers of arbitrary length.
* Uses Doubly Linked Lists for efficient digit storage and manipulation.
* Handles positive and negative numbers correctly.
* Implements carry, borrow, and sign management.
* Removes leading zeros and validates user input.
* Modular and well-structured C implementation for better readability and maintenance.

## Technologies Used

* C Programming
* Doubly Linked Lists
* Dynamic Memory Allocation
* Pointers
* GCC Compiler
* Ubuntu/Linux
* Visual Studio Code (VS Code)

This project serves as an excellent demonstration of implementing arbitrary precision arithmetic using Data Structures and showcases practical applications of linked lists, memory management, and algorithm development in C.
