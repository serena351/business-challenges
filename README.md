[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/h7t5eS6i)
![Digital Futures Logo](https://github.com/digital-futures-academy/DataScienceMasterResources/blob/main/Resources/datascience-notebook-header.png?raw=true)

# Python Business Challenges

These are a series of challenges designed to test your Python skills in a business context. They are challenging and test your ability to think critically and creatively. They are not designed to be easy, but they are designed to be fun!

## How to approach the challenges

- Work through the challenges in order - Basic; Medium; Advanced;
- Look at the requirement, the test cases and the actual test code to understand what is required
- Think about creating a Kanban board with a set of corresponding user stories and tasks to help you manage your progress (remember about the *Definition of Done*!)
- Try and approach the challenges in a test-driven way, imagining that your pair-programmer has written a test and you must write the code to pass it.
  - You can use the test code provided (with a few tweaks) to test your code
    - Put the test code in a separate file and add the code you have written to pass it to the same file - DO NOT ADD AND COMMIT THESE FILES!
- Once you have the code to pass the test, make sure you add and commit this to your local git repository (its just good practice!)
- Once you reach the end of the challenge, you can push you code to your remote repository - you can then check the results of the auto-grading through the GitHub Actions tab in the repo

## Passing the Challenge

Any pushes to your remote repository will trigger the auto-grading process.

You should receive a total of 80% or more to pass the challenge.

- ***Basic***: 13 tests - 10 points each - 130 points
- ***Medium***: 11 tests - 10 points each - 110 points
- ***Advanced***: 10 tests - 10 points each - 100 points
- ***Total***: 34 tests - 340 points (80% ~ ***270 points***)

## How to Run Tests

If you decide to make a file to run the tests, you can use the following command to actually run the tests:

```bash
python -m unittest test_<challenge_name>.py
```

For example, if you have a file called `test_basic.py` you would run the following command:

```bash
python -m unittest test_basic.py
```

## Submission

Any pushes to your remote repository are classed as a submission - the number of submissions is unlimited and the last push before the deadline will be graded.

Submissions will be cut off by the deadline given by your trainer and no further pushes will be graded.

---

## Skills Assessed

### Basics - Exercise 1

- **Function Definition:** Creating functions to encapsulate logic.
- **List Manipulation:** Accessing and iterating through list elements.
- **Conditional Statements:** Using `if`-`elif`-`else` to handle different operations.
- **Arithmetic Operations:** Performing addition, subtraction, multiplication, and division.
- **String Handling**: Comparing strings to determine the operation.
- **Error Handling**: Managing potential errors such as division by zero.
- **Return Values**: Returning the correct type (`integer` or `float`) based on the operation.

### Basics - Exercise 2

- **String Manipulation**: Checking and modifying string formats.
- **Conditional Statements**: Using `if`-`elif`-`else` to handle different responses.
- **String Methods**: Utilizing methods like `str.capitalize()`, `str.islower()`, and `str.isupper()`.
- **Formatted Strings**: Using f-strings or `str.format()` for output messages.
- **Basic Input/Output**: Understanding function inputs and outputs.
- **Error Handling**: Managing unexpected inputs or invalid responses.

### Basics - Exercise 3

- **String Manipulation**: Checking and modifying string contents.
- **Conditional Statements**: Using `if`-`elif`-`else` to handle different conditions.
- **Loops**: Iterating through characters in a string.
- **String Methods**: Utilizing methods like `str.isupper()`, `str.islower()`, `str.isalpha()`, etc.
- **Arithmetic Operations**: Performing calculations to adjust the score.
- **Basic Input/Output**: Understanding function inputs and outputs.
- **Error Handling**: Managing unexpected inputs or invalid characters.

---

### Medium - Exercise 1

- **Function Definition**: Creating functions to encapsulate the logic for calculating earnings and taxes.
- **List Handling**: Managing and validating lists, including checking the length and types of elements.
- **Conditional Statements**: Using `if-elif-else` statements to handle different tax brackets and validate inputs.
- **Arithmetic Operations**: Performing calculations to determine the tax for each bracket and compute the total earnings.
- **Loops**: Iterating through the list of earnings to apply the tax calculations for each family member.
- **Error Handling**: Detecting and handling invalid inputs, such as non-numeric values or incorrect list lengths.
- **Type Conversion**: Converting data types as necessary, such as ensuring inputs are numeric and outputs are floats or strings.
- **Formatted Strings**: Using formatted strings to return error messages.

### Medium - Exercise 2

- **Function Definition**: Creating functions to encapsulate the logic for analysing phone numbers.
- **String Handling**: Manipulating and analysing strings to check for specific patterns and properties.
- **Conditional Statements**: Using `if-elif-else` statements to handle different conditions and validate inputs.
- **Loops**: Iterating through the digits of the phone number to check for specific properties.
- **Regular Expressions**: Using regular expressions to identify patterns such as consecutive digits.
- **Error Handling**: Detecting and handling invalid inputs, such as incorrect length or invalid starting digits.
- **Formatted Strings**: Using formatted strings to generate the output messages.
- **List and** Set Operations: Using lists and sets to check for the presence of all digits or multiple occurrences of a digit.

### Medium - Exercise 3

This task assesses the following Python skills:

- **Function Definition**: Creating functions to encapsulate the logic for generating usernames.
- **Tuple Handling**: Extracting and manipulating data from tuples.
- **List Handling**: Managing and processing lists, including handling elements in random order.
- **String Manipulation**: Modifying strings to create the desired username format.
- **Conditional Statements**: Using `if-elif-else` statements to handle different input scenarios.
- **Type Checking**: Identifying the types of elements in the list to correctly process them.
- **Formatted Strings**: Using formatted strings to generate the output username.

---

### Advanced - Exercise 1

- **Function Definition**: Creating functions to encapsulate the logic for validating and correcting names.
- **String Handling**: Manipulating and analysing strings to check for specific patterns and properties.
- **Conditional Statements**: Using `if-elif-else` statements to handle different validation scenarios.
- **Regular Expressions**: (Optional) Using regular expressions to identify patterns such as capital letters and name lengths.
- **Error Handling**: Detecting and handling invalid inputs, such as missing names or incorrect formats.
- **Formatted Strings**: Using formatted strings to generate the output messages.
- **List and String Operations**: Splitting strings into components and checking their properties (e.g., length, capitalization).

### Advanced - Exercise 2

- **Function Definition**: Creating functions to encapsulate the logic for validating login credentials.
- **String Handling**: Manipulating and analysing strings to check for specific patterns and properties.
- **Tuple Handling**: Extracting and validating data from tuples.
- **Conditional Statements**: Using `if-elif-else` statements to handle different validation scenarios.
- **Regular Expressions**: (Optional) Using regular expressions to identify patterns such as special characters, digits, and uppercase letters.
- **Error Handling**: Detecting and handling invalid inputs, such as incorrect password formats or invalid key-value pairs.
- **Formatted Strings**: Using formatted strings to generate the output messages.
- **Type Conversion**: Converting data types as necessary, such as ensuring values are integers within a specified range.
- **List and String Operations**: Counting occurrences of specific character types and checking their properties (e.g., length, starting character).

---
