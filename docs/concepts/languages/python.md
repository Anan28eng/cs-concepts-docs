# Python

A guide to Python programming.

Python is a versatile and high-level programming language known for its readability and simplicity. It is widely used in various domains, including web development, data analysis, and artificial intelligence.

## Hello, World!

The most basic program in Python is the "Hello, World!" program, which outputs the string "Hello, World!" to the console.

```python
print("Hello, World!")
```

## Variables

In Python, variables are used to store data values. You don't need to declare the variable type explicitly, as Python is dynamically typed.

### Example of Variable Assignment

```python
# Example of variable assignment
name = "Alice"   # String variable
age = 30         # Integer variable
height = 5.7     # Float variable

print(name, age, height)
```

## Data Types

Python has several built-in data types, including:
- **Strings**: Textual data, e.g., `"Hello"`
- **Integers**: Whole numbers, e.g., `42`
- **Floats**: Decimal numbers, e.g., `3.14`
- **Lists**: Ordered collections, e.g., `[1, 2, 3]`
- **Dictionaries**: Key-value pairs, e.g., `{"key": "value"}`

## Example: Simple List

Here's how to create and manipulate a list in Python:

```python
# Creating a list
fruits = ["apple", "banana", "cherry"]

# Accessing list elements
print(fruits[0])  # Outputs: apple

# Adding an element
fruits.append("orange")

# Looping through the list
for fruit in fruits:
    print(fruit)
```


## Example: Function Definition

Functions in Python are defined using the `def` keyword. Here's a simple function that adds two numbers:

```python
def add_numbers(a, b):
    return a + b

result = add_numbers(5, 3)
print(result)  # Outputs: 8
```
##  Looping statements
Looping in python can be done using `for`and `while` keywords:

**For loop:Example**
Printing odd numbers from 1 to 10
```python
for i in range(1,11,2):
     print(i)
print("End of for loop") #Outputs: 1 3 5 7 9
```
**while loop:Example**
Printing 4 tables multiplication
```python
i=1
while i<=10:
   print(f"4 x{i}={4*i}")
   i+=1
print("end of while loop")
#Outputs:4 × 1 = 4    4 × 2 = 8    4 × 3 = 12   4 × 4 = 16   4 × 5 = 20   4 × 6 = 24   4 × 7 = 28   4 × 8 = 32   4 × 9 = 36   4 × 10 = 40

```


    





- Go back to [Languages](./index.md)
- Return to [Home](../../index.md)
