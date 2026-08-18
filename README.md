# python-practice
My first GitHub repository for Python learning


# Python Assignment 1

This repository contains solutions to basic Python programming assignments completed using **Google Colab**. These exercises focus on strengthening Python fundamentals, logical thinking, and problem-solving skills.

## Topics Covered

- Multiplication Table using Functions
- Filtering Odd Numbers using `filter()`
- Finding Prime Factors of a Number
- Product of Digits using Functions
- Using `map()` and `filter()` to Find Cubes of Even Numbers

## Concepts Practiced

- Python Functions
- For and While Loops
- Conditional Statements
- Modulo (`%`) and Floor Division (`//`)
- `filter()` Function
- `map()` Function
- List Operations
- Problem Solving

## File

- `assignment1.ipynb` – Google Colab notebook containing all assignment solutions.

## Learning Outcomes

Through this assignment, I learned to:

- Write reusable Python functions.
- Solve mathematical problems using loops.
- Apply `map()` and `filter()` effectively.
- Perform list and number operations.
- Improve logical thinking and programming skills.

## Tools Used

- Python 3
- Google Colab

---
⭐ Feel free to explore the notebook and provide feedback!


## Python Tuple

This notebook covers the fundamentals of Python tuples with practical examples.

### Topics Covered

- Creating tuples
- Empty tuples
- Tuples with different data types
- Nested tuples
- Single-element tuples
- Accessing tuple elements
- Positive and negative indexing
- Accessing elements from nested tuples
- Tuple slicing
- Tuple immutability
- Working with mutable elements inside a tuple
- Tuple concatenation
- Tuple repetition
- Deleting tuples
- `count()` method
- `index()` method
- Membership using `in`
- Built-in functions:
  - `len()`
  - `sorted()`
  - `max()`
  - `min()`
  - `sum()`


## Python Dictionary

This notebook covers Python dictionaries, including:

- Dictionary creation
- Accessing dictionary elements
- Adding and modifying elements
- Removing elements
- Dictionary methods
- Dictionary comprehension


## Python Set

This notebook covers the fundamentals of Python sets with practical examples.

### Topics Covered

- Set creation
- Creating sets using `set()`
- Adding elements using `add()` and `update()`
- Removing elements using `remove()`, `discard()`, `pop()`, and `clear()`
- Set indexing limitation
- Set operations:
  - Union
  - Intersection
  - Difference
  - Symmetric Difference
- Checking subsets using `issubset()`
- Frozen sets
- Frozen set operations


# Python Functions

This notebook contains practical examples of Python built-in functions, functional programming functions, and user-defined functions.

## 📚 Topics Covered

### 1. Built-in Functions

The notebook demonstrates the following Python built-in functions:

* `abs()` – Find the absolute value of a number
* `all()` – Check whether all elements in an iterable are truthy
* `dir()` – Display the attributes and methods of an object
* `divmod()` – Return quotient and remainder as a tuple
* `enumerate()` – Iterate over a sequence with index and value
* `isinstance()` – Check whether an object is an instance of a specific type

### 2. Functional Programming Functions

The notebook includes examples of:

* `filter()` – Filter elements based on a condition
* `map()` – Apply a function to each element
* `reduce()` – Reduce multiple values to a single result

The `map()` and `reduce()` examples also demonstrate traditional approaches for comparison.

### 3. User-Defined Functions

The notebook demonstrates how to create and use custom functions.

Examples include:

* Adding two numbers
* Subtracting two numbers
* Multiplying two numbers
* Dividing two numbers
* Calculating the product of two numbers

### 4. Simple Calculator

A simple calculator is implemented using user-defined functions.

The calculator provides four options:

```text
1. Addition
2. Subtraction
3. Multiplication
4. Division
```

It also handles division by zero using a condition inside the `division()` function.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook / Google Colab

## 🎯 Learning Objectives

After working through this notebook, you will be able to:

* Understand commonly used Python built-in functions.
* Use `enumerate()` to work with indexes and values.
* Use `filter()` to select elements based on a condition.
* Use `map()` to transform elements.
* Use `reduce()` to combine multiple values into one result.
* Create and call user-defined functions.
* Build a simple calculator using functions.
* Handle division-by-zero cases.

## 📂 File Structure

```text
function_type.ipynb
README.md
```

## ▶️ How to Run

1. Clone or download this repository.
2. Open `function_type.ipynb` using Jupyter Notebook or Google Colab.
3. Run the cells from top to bottom.
4. Experiment with the examples and change the input values.

## 👩‍💻 Author

**Binal Patel**

This notebook is part of my Python learning and practice journey.



# Computational Complexity & Searching Algorithms

This notebook contains Python practice examples to understand **time complexity, space complexity, and searching algorithms**.

## 📌 Topics Covered

### 1. Linear Search — `O(n)`

Searches for an element by checking each element one by one.

- **Time Complexity:** `O(n)`
- **Works with:** Sorted and unsorted lists

### 2. Binary Search — `O(log n)`

Binary Search is used to search for an element efficiently in a **sorted list**.

Two approaches are practiced:

- **Recursive Binary Search**
- **Iterative Binary Search**

- **Time Complexity:** `O(log n)`

### 3. Finding Common Elements — `O(n × m)`

A nested-loop approach is used to find common elements between two lists.

- **Time Complexity:** `O(n × m)`
- **Space Complexity:** `O(1)`
- Uses no additional data structure for searching.

### 4. Finding Common Elements Using a Hash Table

A dictionary/hash table is used to improve the searching process.

- **Time Complexity:** `O(n + m)`
- Approximately `O(n)` when `m < n`
- **Space Complexity:** `O(m)`
- Dictionary lookup takes approximately **`O(1)` average time**.

## 🧠 Complexity Summary

| Algorithm / Approach | Time Complexity | Space Complexity |
|---|---:|---:|
| Linear Search | `O(n)` | `O(1)` |
| Binary Search | `O(log n)` | `O(log n)` for recursive version |
| Common Elements using Nested Loops | `O(n × m)` | `O(1)` |
| Common Elements using Hash Table | `O(n + m)` | `O(m)` |

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- Lists
- Loops
- Functions
- Dictionaries / Hash Tables
- Time & Space Complexity

## 📂 Notebook

The complete Python implementations and practice examples are available in:

**`computational_complexity.ipynb`**

## 🎯 Learning Objective

The main goal of this notebook is to understand how different algorithms perform as the input size increases and how choosing an appropriate **algorithm and data structure** can improve efficiency.