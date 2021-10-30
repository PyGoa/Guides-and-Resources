# Beginner's Guide to Python

## List of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. Getting Started
4. [Variables](#variables)
5. Data types
6. Operators
7. Strings
8. Lists
9. IF statements
10. FOR statements
11. Functions
12. Built-in Functions
13. Objects
14. Data Structures
15. File Handling



## Introduction
Python is a high-level, general purpose programming language. It promotes simplicity and code readability.

## Installation
### For Linux
On linux python may be installed by default depending on your distribution. To check if it is installed you can run ```python -v``` in your terminal. If you get a version number it is installed, otherwise you will get a command not found error. In case it is not installed by default you can install it using your package manager:
1. On Arch linux: ```sudo pacman -S python```
1. On Debian based distros: ```sudo apt-get install python3```
1. On RHEL : ```sudo dnf install python3 ```
### For Windows
Download and run the python3 installer for the latest release from the official [python website](https://www.python.org/downloads/windows/)


## Variables
**What is a Variable in Python?**

A Python variable is a reserved memory location to store values. In other words, a
variable in a python program gives data to the computer for processing.
Every value in Python has a datatype. Different data types in Python are Numbers,
List, Tuple, Strings, Dictionary, etc. Variables can be declared by any name or even
alphabets like a, aa, abc, etc

**Variable Naming Rules in Python**
1. Variable name should start with letter(a-zA-Z) or underscore (_).

Valid : age , _age , Age

Invalid : 1age

2.In variable name, no special characters allowed other than underscore (_).

Valid : age_ , _age

Invalid : age_*

3.Variables are case sensitive.

age and Age are different, since variable names are case sensitive.

4.Variable name can have numbers but not at the beginning.

Example: Age1

5.Variable name should not be a Python keyword.Keywords are also called as reserved
words.

Example

pass, break, continue.. etc are reserved for special meaning in Python. So, we should
not declare keyword as a variable name.

**How to Declare and use a Variable**

Let see an example. We will declare variable "a" and print it.
```
a=100
print (a)
 ```
**Re-declare a Variable**

You can re-declare the variable even after you have declared it once.
```
a=100
print(a)
a=’AECS Jaduguda’
print(a)
 ```
**Concatenate Variables**
```
a='AECS'
b=1
print(a+b)
 ```
will throw error , as we cannot concatenate two different datatypes. But
```
a='AECS'
b=1
print(a+str(b))
 ```
will display
```
AECS1
 ```

**Delete a variable**

You can also delete variable using the command del "variable name".

