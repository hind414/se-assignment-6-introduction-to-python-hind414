[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15359320&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
  
 Python is a high-level, interpreted programming language known for its simplicity, versatility, and readability. It was created by Guido van Rossum and first released in 1991. Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming styles.

Key Features of Python:
Simple and Easy to Learn:

Python has a clean and readable syntax that emphasizes code readability and simplicity. This makes it accessible for beginners and allows developers to express concepts in fewer lines of code compared to other languages.
Expressive and Concise:

Python's language constructs and built-in data structures (such as lists, dictionaries, and sets) allow developers to write expressive and concise code. This reduces development time and enhances productivity.
Cross-platform:

Python is available on various platforms (Windows, macOS, Linux) and can run seamlessly across different operating systems without requiring changes to the code.
Extensive Standard Library:

Python comes with a large standard library that provides modules and packages for tasks ranging from file I/O to web development, networking, and data manipulation. This reduces the need for external libraries for many common tasks.
Dynamically Typed:

Python is dynamically typed, meaning you don't need to explicitly declare variable types. This allows for faster development cycles and easier maintenance of code.
Support for Third-party Libraries:

Python has a vibrant ecosystem with a vast collection of third-party libraries and frameworks (e.g., NumPy, pandas, Django, Flask) that extend its capabilities for specific domains such as data science, web development, machine learning, and more.
Integration Capabilities:

Python can easily integrate with other languages and tools, making it suitable for building complex systems and integrating with existing software infrastructure.
Use Cases and Examples:
Web Development: Python frameworks like Django and Flask are popular choices for building web applications due to their simplicity and robustness. Django is used by companies like Instagram and Pinterest for their backend systems.

Data Analysis and Visualization: Python's libraries such as NumPy, pandas, and Matplotlib are widely used in data science and analytics for data manipulation, statistical analysis, and visualization tasks. For example, Jupyter Notebooks use Python extensively for interactive data exploration.

Machine Learning and Artificial Intelligence: Python's libraries such as TensorFlow, PyTorch, and scikit-learn are dominant in the field of machine learning and AI. Python's simplicity and readability make it easier to prototype and deploy machine learning models.

Scripting and Automation: Python's scripting capabilities and cross-platform support make it ideal for writing automation scripts, system administration tasks, and building command-line tools.

Education and Learning: Python's readability and ease of learning make it a popular choice for introductory programming courses and educational purposes, helping beginners grasp programming concepts quickly.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

To install Python on your Windows operating system, follow these steps. We'll cover installing Python, verifying the installation, and setting up a virtual environment using `venv`.

### Installing Python:

1. **Download Python Installer:**
   - Visit the official Python website at [python.org](https://www.python.org/downloads/) and download the latest version of Python for Windows. Choose either the 32-bit or 64-bit installer based on your system architecture.

2. **Run Python Installer:**
   - Once downloaded, run the Python installer (`python-<version>.exe`). Make sure to check the box that says "Add Python to PATH" during the installation process. This option ensures that Python is added to your system's PATH environment variable, allowing you to run Python from the command line.

3. **Complete Installation:**
   - Follow the prompts in the Python installer to complete the installation. Python will be installed in a default directory (`C:\Users\YourUsername\AppData\Local\Programs\Python\Python<version>`).

### Verifying the Installation:

1. **Open Command Prompt:**
   - Open the Command Prompt by pressing `Win + R`, typing `cmd`, and pressing Enter.

2. **Check Python Version:**
   - To verify that Python is installed correctly, type the following command in the Command Prompt:
     ```bash
     python --version
     ```
   - This command should display the installed Python version (e.g., `Python 3.9.7`).

3. **Check Python Interpreter:**
   - You can also launch the Python interpreter by typing:
     ```bash
     python
     ```
   - This opens the Python REPL (Read-Eval-Print Loop), where you can execute Python code interactively. Exit the interpreter by typing `exit()` or pressing `Ctrl + Z` followed by Enter.

### Setting Up a Virtual Environment (Using venv):

1. **Create a Directory for Your Project:**
   - Choose or create a directory where you want to work on your Python project. Open Command Prompt and navigate (`cd`) to this directory.

2. **Create a Virtual Environment:**
   - In the Command Prompt, use the following command to create a virtual environment named `venv` (you can choose any name):
     ```bash
     python -m venv venv
     ```
   - This command creates a new directory `venv` within your project directory, containing a isolated Python environment.

3. **Activate the Virtual Environment:**
   - To activate the virtual environment, run the activation script located in the `Scripts` directory inside `venv`:
     ```bash
     venv\Scripts\activate
     ```
   - You should see `(venv)` appear at the beginning of your command prompt, indicating that the virtual environment is active.

4. **Install Packages (Optional):**
   - While the virtual environment is active, any Python packages installed using `pip` will be isolated to that environment. For example, you can install packages like Flask:
     ```bash
     pip install Flask
     ```

5. **Deactivate the Virtual Environment:**
   - To deactivate the virtual environment and return to the global Python environment, simply type:
     ```bash
     deactivate
     ```
   - The `(venv)` prefix should disappear from the command prompt.


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
  
  # Simple Python program to print "Hello, World!"

# Print statement
print("Hello, World!")

### Explanation of Basic Syntax Elements:

1. **Comments (`#`)**:
   - Comments in Python start with the `#` symbol and are used to annotate code. They are ignored by the Python interpreter and are helpful for adding explanations or notes within the code.

2. **Print Statement (`print("Hello, World!")`)**:
   - The `print()` function in Python is used to output text (or other data) to the console. In this case, `print("Hello, World!")` prints the string `"Hello, World!"` to the console.
   - **`print`**: This is the name of the built-in function in Python used for outputting data.
   - **`()`**: Parentheses are used to enclose the arguments passed to the `print` function. Here, `"Hello, World!"` is the argument (or parameter) passed to `print`.
   - **`"Hello, World!"`**: This is a string literal, enclosed in double quotes (`"`). String literals are sequences of characters that are treated as text by Python.
   - **`;` (Optional)**: In Python, unlike some other languages, a semicolon (`;`) at the end of the statement is optional. It can be used to separate statements on the same line, but it's typically not necessary or commonly used in Python.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

  In Python, there are several basic data types that are fundamental for storing and manipulating data. Here are the main basic data types along with descriptions and a short script demonstrating their usage:

### Basic Data Types in Python:

1. **Integer (`int`)**:
   - Represents whole numbers without any decimal point.
   - Example: `x = 10`

2. **Float (`float`)**:
   - Represents real numbers with a decimal point.
   - Example: `y = 3.14`

3. **String (`str`)**:
   - Represents sequences of characters, enclosed in single (`'`) or double (`"`) quotes.
   - Example: `name = "John"`

4. **Boolean (`bool`)**:
   - Represents truth values `True` or `False`.
   - Example: `is_student = True`

5. **List (`list`)**:
   - Represents ordered collections of items, mutable (modifiable).
   - Example: `numbers = [1, 2, 3, 4, 5]`

6. **Tuple (`tuple`)**:
   - Represents ordered collections of items, immutable (cannot be modified after creation).
   - Example: `coordinates = (10, 20)`

7. **Dictionary (`dict`)**:
   - Represents collections of key-value pairs, where each key is unique.
   - Example: `person = {'name': 'Alice', 'age': 30}`

### Example Script Demonstrating Different Data Types:

```python
# Define variables of different data types
x = 10              # integer
y = 3.14            # float
name = "John"       # string
is_student = True   # boolean

numbers = [1, 2, 3, 4, 5]                   # list
coordinates = (10, 20)                      # tuple
person = {'name': 'Alice', 'age': 30}       # dictionary

# Print out the variables and their types
print(f"Variable x: {x}, type: {type(x)}")
print(f"Variable y: {y}, type: {type(y)}")
print(f"Variable name: {name}, type: {type(name)}")
print(f"Variable is_student: {is_student}, type: {type(is_student)}")

print(f"Variable numbers: {numbers}, type: {type(numbers)}")
print(f"Variable coordinates: {coordinates}, type: {type(coordinates)}")
print(f"Variable person: {person}, type: {type(person)}")
```
Explanation:
Variables: Variables (x, y, name, is_student, numbers, coordinates, person) are declared and assigned values of different data types.
Printing: The print() function is used to output the values of variables along with their respective data types using type() function.
Types: Each variable is followed by its type using the type() function to demonstrate the dynamic typing nature of Python.
Output:
When you run this script, it will output:

python
Copy code
Variable x: 10, type: <class 'int'>
Variable y: 3.14, type: <class 'float'>
Variable name: John, type: <class 'str'>
Variable is_student: True, type: <class 'bool'>
Variable numbers: [1, 2, 3, 4, 5], type: <class 'list'>
Variable coordinates: (10, 20), type: <class 'tuple'>
Variable person: {'name': 'Alice', 'age': 30}, type: <class 'dict'>


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

### Conditional Statements and Loops in Python

#### Conditional Statements (`if-else`)

Conditional statements in Python allow you to execute certain blocks of code based on whether a condition is true or false. The most common conditional statement is the `if-else` statement.

**Example of an `if-else` statement:**

```python
# Example of an if-else statement
x = 10

if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

**Explanation:**
- In this example, `x = 10` is assigned.
- The `if` statement checks if `x` is greater than 5 (`x > 5`). If this condition evaluates to `True`, the indented block under `if` (`print("x is greater than 5")`) is executed.
- If the condition `x > 5` is `False`, the block under `else` (`print("x is not greater than 5")`) is executed.
- In this case, since `x = 10` and `10 > 5` is `True`, the output will be `x is greater than 5`.

#### Loops ( `for` loop)

Loops in Python are used to iterate over a sequence of elements or execute a block of code repeatedly until a certain condition is met. One of the most commonly used loops is the `for` loop.

**Example of a `for` loop:**

```python
# Example of a for loop
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

**Explanation:**
- In this example, `fruits` is a list containing three strings (`"apple"`, `"banana"`, `"cherry"`).
- The `for` loop iterates over each element (`fruit`) in the `fruits` list.
- During each iteration, the current element (`fruit`) is printed using the `print()` function.
- Therefore, the output will be:
  ```
  apple
  banana
  cherry
  ```

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

### Functions in Python

**Functions** in Python are blocks of code that are designed to do one specific job. They allow you to write reusable code, improve readability, and organize your program into logical units. Functions can take inputs (arguments), perform operations, and optionally return a result.

#### Why are Functions Useful?

1. **Modularity:** Functions allow you to break down a complex problem into smaller, manageable pieces. Each function can focus on a specific task, making your code easier to understand and maintain.

2. **Code Reusability:** Once defined, functions can be called multiple times from different parts of your program without rewriting the code, promoting code reuse and reducing redundancy.

3. **Abstraction:** Functions provide a level of abstraction by hiding the implementation details. Users of the function only need to know what inputs are required and what output to expect, without needing to understand how the function achieves its task internally.

4. **Testing and Debugging:** Functions make it easier to test and debug your code. You can isolate specific functionality within a function and test it independently, ensuring that each part of your program behaves as expected.

#### Example: Python Function to Calculate Sum

Here's an example of a Python function that takes two arguments (numbers) and returns their sum:

```python
# Function to calculate the sum of two numbers
def calculate_sum(a, b):
    return a + b

# Example of calling the function
num1 = 5
num2 = 3
result = calculate_sum(num1, num2)
print(f"The sum of {num1} and {num2} is: {result}")
```

**Explanation:**
- **Function Definition (`def calculate_sum(a, b):`):**
  - `def` keyword is used to define a function named `calculate_sum`.
  - `calculate_sum` is the function name.
  - `(a, b)` are the parameters (inputs) that the function expects. These parameters act as placeholders for the values passed into the function when it is called.
  - `:` indicates the start of the function body.
- **Function Body (`return a + b`):**
  - Inside the function, `a + b` calculates the sum of the parameters `a` and `b`.
  - `return` statement returns the computed result back to the caller.
- **Function Call (`result = calculate_sum(num1, num2)`):**
  - `calculate_sum(num1, num2)` is called with `num1` and `num2` as arguments.
  - The function computes the sum of `num1` and `num2` (which are `5` and `3`, respectively) and returns `8`.
  - The returned value (`8`) is stored in the variable `result`.
- **Output (`print(f"The sum of {num1} and {num2} is: {result}")`):**
  - Finally, the `print()` function outputs the result `"The sum of 5 and 3 is: 8"`.


7. Lists and Dictionaries:
   -Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

### Lists vs. Dictionaries in Python

#### Lists:
- **Definition:** Lists are ordered collections of items that can contain elements of different data types.
- **Characteristics:**
  - Elements are indexed by integers starting from 0.
  - Accessed using square brackets `[]`.
  - Mutable (can be modified after creation).
  - Elements can be added, removed, or modified.
- **Use Cases:**
  - Useful for storing sequences of items where the order matters.
  - Iterating over elements in a specific sequence.
  
#### Dictionaries:
- **Definition:** Dictionaries are unordered collections of key-value pairs.
- **Characteristics:**
  - Elements are accessed using keys.
  - Accessed using curly braces `{}`.
  - Mutable (values associated with keys can be changed).
  - Keys are unique within the dictionary.
- **Use Cases:**
  - Ideal for storing data that needs to be looked up quickly using a unique identifier (key).
  - Storing configuration settings, mapping relationships, etc.
  
### Example Script Demonstrating Lists and Dictionaries:

```python
# Creating a list of numbers
numbers = [1, 2, 3, 4, 5]

# Creating a dictionary with key-value pairs
person = {
    'name': 'Alice',
    'age': 30,
    'city': 'New York'
}

# Accessing elements in the list
print("Elements in the list:")
for num in numbers:
    print(num)

# Accessing elements in the dictionary
print("\nElements in the dictionary:")
print(f"Name: {person['name']}")
print(f"Age: {person['age']}")
print(f"City: {person['city']}")

# Adding elements to the list
numbers.append(6)
print("\nList after adding a new element:")
print(numbers)

# Adding a new key-value pair to the dictionary
person['email'] = 'alice@example.com'
print("\nDictionary after adding a new key-value pair:")
print(person)

# Modifying an element in the list
numbers[0] = 10
print("\nList after modifying an element:")
print(numbers)

# Modifying a value in the dictionary
person['age'] = 31
print("\nDictionary after modifying a value:")
print(person)

# Removing an element from the list
removed_number = numbers.pop(2)  # Remove the element at index 2
print(f"\nList after removing element at index 2 ({removed_number}):")
print(numbers)

# Removing a key-value pair from the dictionary
del person['city']
print("\nDictionary after removing a key-value pair:")
print(person)
```

**Explanation:**

- **Creating Lists and Dictionaries:**
  - `numbers` is a list containing integers `[1, 2, 3, 4, 5]`.
  - `person` is a dictionary with keys `'name'`, `'age'`, and `'city'` mapping to values `'Alice'`, `30`, and `'New York'`, respectively.

- **Accessing Elements:**
  - Lists are accessed using index (`numbers[0]`, `numbers[1]`, ...).
  - Dictionaries are accessed using keys (`person['name']`, `person['age']`, ...).

- **Basic Operations:**
  - **Adding:** `append()` for lists, assignment for dictionaries (`person['email'] = 'alice@example.com'`).
  - **Modifying:** Direct assignment (`numbers[0] = 10`, `person['age'] = 31`).
  - **Removing:** `pop()` for lists (`numbers.pop(2)` removes the element at index 2), `del` keyword for dictionaries (`del person['city']` removes the `'city'` key-value pair).

### Output:

When you run this script, it will output:

```
Elements in the list:
1
2
3
4
5

Elements in the dictionary:
Name: Alice
Age: 30
City: New York

List after adding a new element:
[1, 2, 3, 4, 5, 6]

Dictionary after adding a new key-value pair:
{'name': 'Alice', 'age': 30, 'city': 'New York', 'email': 'alice@example.com'}

List after modifying an element:
[10, 2, 3, 4, 5, 6]

Dictionary after modifying a value:
{'name': 'Alice', 'age': 31, 'city': 'New York', 'email': 'alice@example.com'}

List after removing element at index 2 (3):
[10, 2, 4, 5, 6]

Dictionary after removing a key-value pair:
{'name': 'Alice', 'age': 31, 'email': 'alice@example.com'}
```


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

### Exception Handling in Python

**Exception handling** in Python is a mechanism that allows you to handle runtime errors (exceptions) gracefully. It helps you to anticipate and deal with possible errors that may occur during the execution of your program.

#### Components of Exception Handling:

1. **`try` block:**
   - The `try` block is used to enclose the code that may raise an exception. It is followed by one or more `except` blocks.
   
2. **`except` block:**
   - `except` blocks are used to handle specific exceptions that are raised in the `try` block. You can have multiple `except` blocks to handle different types of exceptions.
   
3. **`finally` block:**
   - The `finally` block is optional and is used to execute cleanup code, whether an exception occurs or not. It is executed irrespective of whether an exception is raised or not.

#### Example of Exception Handling:

```python
# Example of exception handling with try, except, and finally blocks

# Function to divide two numbers and handle ZeroDivisionError
def divide_numbers(a, b):
    try:
        result = a / b
    except ZeroDivisionError:
        print("Error: Division by zero!")
    else:
        print(f"{a} divided by {b} is {result}")
    finally:
        print("Division operation completed.")

# Example 1: Handling division by zero
print("Example 1:")
divide_numbers(10, 0)  # This will trigger ZeroDivisionError

# Example 2: Normal division
print("\nExample 2:")
divide_numbers(10, 2)  # This will execute normally
```

**Explanation:**

- **`try` block (`try:`):**
  - The `try` block contains code that might raise an exception. In the example, `result = a / b` is inside the `try` block.

- **`except` block (`except ZeroDivisionError:`):**
  - If an exception of type `ZeroDivisionError` occurs (e.g., dividing by zero), the corresponding `except` block is executed. In this case, `"Error: Division by zero!"` is printed.

- **`else` block (`else:`):**
  - The `else` block is executed if no exceptions occur in the `try` block. Here, `print(f"{a} divided by {b} is {result}")` will be executed if division is successful.

- **`finally` block (`finally:`):**
  - The `finally` block is always executed, whether an exception is raised or not. It is used for cleanup actions, such as closing files or releasing resources.

### Output:

When you run the above script, it will output:

```
Example 1:
Error: Division by zero!
Division operation completed.

Example 2:
10 divided by 2 is 5.0
Division operation completed.
```

- In **Example 1**, `divide_numbers(10, 0)` raises a `ZeroDivisionError`, and the corresponding `except` block is executed. The `finally` block is also executed after handling the exception.
  
- In **Example 2**, `divide_numbers(10, 2)` executes successfully without raising any exceptions. Both the `else` block and the `finally` block are executed.

  
9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

 ### Modules and Packages in Python

#### Modules:

- **Definition:** Modules in Python are files containing Python code. They can define functions, classes, and variables that you can use in other Python scripts by importing them.

- **Purpose:** Modules help in organizing Python code into reusable units. They facilitate code reusability, maintainability, and isolation of functionality.

#### Packages:

- **Definition:** Packages are namespaces that contain multiple modules and sub-packages. They allow you to structure Python projects hierarchically.

- **Purpose:** Packages help in organizing and managing larger Python projects. They provide a way to group related modules together and avoid naming conflicts.

### Importing and Using Modules in Python:

You can import modules in Python using the `import` statement. Once imported, you can use functions, classes, and variables defined in the module.

#### Example Using the `math` Module:

The `math` module in Python provides access to mathematical functions. Here's how you can import and use it in your script:

```python
# Example: Using the math module

# Importing the math module
import math

# Using functions from the math module
print("Value of pi:", math.pi)
print("Square root of 16:", math.sqrt(16))
print("Factorial of 5:", math.factorial(5))
print("Sine of 0.5 radians:", math.sin(0.5))

# Using constants and variables from the math module
radius = 5
area = math.pi * radius ** 2
print(f"Area of a circle with radius {radius}: {area}")
```

**Explanation:**

- **Importing the `math` module (`import math`):**
  - The `import math` statement imports the entire `math` module into the current namespace, making all its functions and variables accessible.

- **Using functions from the `math` module:**
  - `math.pi`: Accesses the constant value of π (pi).
  - `math.sqrt(16)`: Calculates the square root of 16.
  - `math.factorial(5)`: Computes the factorial of 5.
  - `math.sin(0.5)`: Calculates the sine of 0.5 radians.

- **Using constants and variables from the `math` module:**
  - `math.pi` is used to calculate the area of a circle with radius `5` (`area = math.pi * radius ** 2`).

### Output:

When you run the script, it will output:

```
Value of pi: 3.141592653589793
Square root of 16: 4.0
Factorial of 5: 120
Sine of 0.5 radians: 0.479425538604203
Area of a circle with radius 5: 78.53981633974483
```

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

### Reading from and Writing to Files in Python

#### Reading from a File:

To read from a file in Python, you typically follow these steps:

1. **Open the File:** Use the `open()` function with the file path and mode (`'r'` for reading) to open the file.
2. **Read from the File:** Use methods like `read()`, `readline()`, or `readlines()` to read content from the file.
3. **Close the File:** Always close the file using the `close()` method after reading to free up system resources.

#### Example: Reading from a File and Printing to Console

Assume you have a file named `example.txt` with the following content:

```
Hello, this is line 1.
This is line 2.
And this is line 3.
```

Here's a script that reads the content of `example.txt` and prints it to the console:

```python
# Reading from a file and printing its content

# Open the file for reading
file_path = 'example.txt'
file = open(file_path, 'r')

# Read and print the content line by line
print("Content of the file:")
for line in file.readlines():
    print(line.strip())  # Use strip() to remove any extra newline characters

# Close the file
file.close()
```

**Explanation:**
- **Opening the File (`open(file_path, 'r')`):**
  - `open()` function is used to open the file `example.txt` in read mode (`'r'`).
- **Reading and Printing the Content:**
  - `file.readlines()` reads all lines from the file and returns them as a list of strings.
  - `for line in file.readlines():` iterates over each line in the list of lines.
  - `print(line.strip())` prints each line after removing any leading or trailing whitespace (including newline characters).
- **Closing the File (`file.close()`):**
  - Always close the file using `close()` to release resources and ensure data integrity.

#### Writing to a File:

To write to a file in Python, follow these steps:

1. **Open the File:** Use `open()` with the file path and mode (`'w'` for writing).
2. **Write to the File:** Use methods like `write()` or `writelines()` to write content to the file.
3. **Close the File:** Always close the file using `close()` after writing to save the changes.

#### Example: Writing a List of Strings to a File

Here's a script that writes a list of strings to a file named `output.txt`:

```python
# Writing a list of strings to a file

# List of strings to write to file
lines_to_write = [
    "This is line 1.",
    "This is line 2.",
    "And this is line 3."
]

# Open the file for writing
output_file_path = 'output.txt'
file = open(output_file_path, 'w')

# Write each line from the list to the file
for line in lines_to_write:
    file.write(line + '\n')  # Add newline character to separate lines

# Close the file
file.close()

print(f"Lines have been written to {output_file_path}.")
```

**Explanation:**
- **List of Strings (`lines_to_write`):**
  - Contains three strings, each representing a line of text to be written to the file.
- **Opening the File for Writing (`open(output_file_path, 'w')`):**
  - `open()` function is used to open the file `output.txt` in write mode (`'w'`).
- **Writing to the File (`file.write(line + '\n')`):**
  - `file.write(line + '\n')` writes each line from `lines_to_write` to the file, adding a newline character (`'\n'`) after each line.
- **Closing the File (`file.close()`):**
  - Closing the file ensures that all data is written to the file and frees up system resources.


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


