[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15423531&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   - Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
   - Easy-to-read syntax: Python emphasizes readability and simplicity.
Extensive standard library: Python comes with a vast collection of libraries for various tasks.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   - To install Python on your operating system:

Windows: Download the Python installer from python.org, run it, and ensure to add Python to PATH during installation.
macOS: Python is pre-installed on macOS. You can also install the latest version using Homebrew or download it from python.org.
Linux: Use the package manager of your distribution to install Python. For example, on Ubuntu, you can use sudo apt install python3.
To verify the installation, open a terminal (command prompt on Windows) and type python --version. To set up a virtual environment, use python -m venv myenv to create a virtual environment named myenv.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   - print("Hello, World!")
Basic syntax elements:
print(): Function to output text to the console.
"": Double quotes used to define a string.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types
   - Basic data types:

int: Integer numbers (e.g., 5)
float: Floating-point numbers (e.g., 3.14)
str: Strings (e.g., "Hello")
bool: Boolean values (True or False)
# Example script demonstrating variables of different data types
my_int = 5
my_float = 3.14
my_str = "Hello"
my_bool = True

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   - Conditional statements and loops:

if-else statement:
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is 5 or less")
for loop:
for i in range(5):
    print(i)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   - Functions: Functions in Python are blocks of code that only run when called. They can accept parameters and return values.

# Function to add two numbers
def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(3, 4)
print(result)  # Output: 7

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   - Lists vs. Dictionaries:

Lists are ordered collections of items accessed by index.
Dictionaries are unordered collections of key-value pairs.
# Creating a list and dictionary
my_list = [1, 2, 3, 4]
my_dict = {"name": "Alice", "age": 30}

# Basic operations
print(my_list[0])  # Accessing list element
print(my_dict["name"])  # Accessing dictionary value

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Exception Handling: Exception handling in Python allows you to manage errors gracefully.

try:
    x = 1 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Execution complete")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   - Modules and Packages:

Modules are Python files containing functions and variables.
Packages are directories of Python modules.
# Using the math module
import math

result = math.sqrt(16)
print(result)  # Output: 4.0

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.To read from a file and write to a file:

# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)

# Writing to a file
data = ["apple", "banana", "cherry"]
with open("fruits.txt", "w") as file:
    for item in data:
        file.write(item + "\n")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


