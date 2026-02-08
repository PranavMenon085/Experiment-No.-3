EXPERIMENT NO. 3

Name: Pranav Menon

PRN No.: 25070123085

Branch: ENTC

Batch: B1

AIM: Study of Tuple in Python

THEORY:

Topics Covered:

1. Introduction to Tuple

A tuple in Python is an ordered collection of elements that cannot be modified once created. Tuples belong to the category of immutable sequences, meaning their contents remain fixed throughout program execution. They are useful when data should remain constant, such as coordinates, configuration values, or records.

- Definition: A tuple is an ordered, immutable collection of elements.
- Immutable sequences: Unlike lists, tuples do not allow insertion, deletion, or modification of elements.
- Tuple creation: Tuples are created using parentheses () with elements separated by commas.
- Difference from lists: Lists are mutable and allow modifications, while tuples are immutable and more memory-efficient.

Syntax:
- my_tuple = (element1, element2, element3)
- single_tuple = (element,)   # Note the comma
- empty_tuple = ()

2. Tuple Operations

Tuples support indexing, concatenation, and repetition. Elements can be accessed using both positive and negative indices.

- Indexing: Access elements by position.
  tpl[1]   → positive indexing (returns "banana")
  tpl[-2]  → negative indexing (returns "banana")

- Concatenation: Combine two tuples.
  tpl1 = (1, 2, 3)
  tpl2 = (4, 5, 6)
  result = tpl1 + tpl2   # (1, 2, 3, 4, 5, 6)

- Multiplication (Repetition): Repeat elements.
  tpl = (10,) * 5   # (10, 10, 10, 10, 10)

3. Memory Location Analysis

Tuples demonstrate immutability through memory addresses. When a tuple is modified, a new object is created with a different memory location, unlike lists which reuse the same memory.

Syntax:
tpl = ("apple", "banana", "orange")
print(id(tpl))   # Displays memory address

- Tuples: New memory location after modification.
- Lists: Same memory location reused after changes.
- This highlights immutability of tuples.

4. Tuple Methods and Functions

Tuples support several built-in functions for analysis and computation:

- max(), min(), len(), sum(), sorted()
- Statistical calculations: average, maximum, minimum
- Sorting: Tuples can be sorted using sorted(), which returns a list (immutability preserved).

Example:
tpl = (5, 2, 9, 1)
print(max(tpl))   # 9
print(sorted(tpl)) # [1, 2, 5, 9]

5. Tuple Unpacking

Tuple unpacking allows assigning elements to individual variables in a single step.

Example:
student = ("John", 21, "CS")
name, age, dept = student
print(name, age, dept)

6. Practice Questions

- Store student marks in a tuple and calculate average.
- Track employee attendance using tuples.
- Validate data using conditional statements on tuple elements.
     
7. PRACTICAL APPLICATIONS:

Use tuples for: database records, coordinates, function returns, dictionary keys, configuration data, RGB values, dates

Use lists for: dynamic data, frequent modifications, sorting in place


KEY DIFFERENCES: LIST vs TUPLE

Lists:

- Mutability: Mutable (can be modified), elements can be changed after creation, can add or remove elements dynamically
  
- Memory Usage: Consume more memory, requires additional memory for dynamic resizing, memory overhead for mutability support
  
- Built-in Methods: Several methods available - append(), insert(), remove(), pop(), extend(), clear(), etc.
  
- Performance: Iteration is time-consuming, slower operations due to mutability overhead
  
- Memory Address: Remains same after modification, modifications happen in-place
  
- Syntax: Defined using square brackets: [item1, item2, item3]
  
- Use case: When data needs frequent modification, suitable for dynamic collections

Tuples:

- Mutability: Immutable (cannot be modified), elements cannot be changed after creation, fixed size and content
  
- Memory Usage: Consume less memory, no memory overhead for dynamic operations, efficient utilization
  
- Built-in Methods: Only two methods: count() and index(), limited functionality reinforces immutability
  
- Performance: Iteration is faster, faster operations due to fixed size, better with large datasets
  
- Memory Address: Changes after modification, creates new tuple for any change, new memory allocation required
  
- Syntax: Defined using parentheses: (item1, item2, item3)
  
- Use case: When data should remain constant, suitable for fixed collections, ideal for data integrity

ALGORITHMS:

1. Display Student Marks Statistics

Step 1: Start - Begin the process

Step 2: Initialize marks tuple
   - Command: marks = (90, 82, 66, 76, 33)
   - Built-in Python tuple structure (no import required)

Step 3: Find and display maximum marks
   - Command: print("The Maximum Marks are : ", max(marks))
   - max() - Built-in function, returns largest item

Step 4: Find and display minimum marks
   - Command: print("The Minimum Marks are : ", min(marks))
   - min() - Built-in function, returns smallest item

Step 5: Count and display number of students
   - Command: print("The Number of Students are : ", len(marks))
   - len() - Built-in function, returns number of items

Step 6: Calculate and display sum of marks
   - Command: print("The Sum of marks of students are : ", sum(marks))
   - sum() - Built-in function, returns sum of all items

Step 7: Calculate and display average marks
   - Command: print("The Average marks of students are : ", sum(marks)/len(marks))
   - Division operator (/) - Built-in arithmetic operator
   - sum(marks)/len(marks) - Average marks

Step 8: Sort and display marks
   - Command: print("Sorted array of marks are : ", sorted(marks))
   - sorted() - Built-in function, returns new sorted list

Step 9: Stop - End the algorithm


2. Unpack Tuple Data

Step 1: Start - Begin the process

Step 2: Initialize result tuple
   - Command: result = ("Maths", 82, "A")
   - Built-in Python tuple structure (no import required)

Step 3: Unpack tuple into variables
   - Command: subject, marks, grade = result
   - Tuple unpacking - Built-in Python feature

Step 4: Display subject, marks, and grade
   - Commands: 
     print("Subject : ", subject)
     print("Marks : ", marks)
     print("Grade : ", grade)
   - print() - Built-in function for console output

Step 5: Check distinction condition
   - Command: if marks >= 75:
   - Conditional statement with >= operator - Built-in

Step 6: Display distinction message (if condition true)
   - Command: print("The Student has achieved Distinction in the Subject ")
   - Executed only when marks ≥ 75

Step 7: Stop - End the algorithm


3. Employee Attendance Analysis

Step 1: Start - Begin the process

Step 2: Initialize attendance tuple
   - Command: attendance = ("p", "a", "p", "p", "a", "p")
   - Built-in Python tuple ('p'=present, 'a'=absent)

Step 3: Count and display present days
   - Command: print("The Number of days the Employee was Present : ", attendance.count("p"))
   - count() - Built-in tuple method, counts occurrences

Step 4: Count and display absent days
   - Command: print("The Number of days the Employee was Absent : ", attendance.count("a"))
   - count() - Built-in tuple method

Step 5: Check absence condition
   - Command: if attendance.count("a") >= 1:
   - Conditional statement - Built-in

Step 6: Display absence message
   - Command: print("The Employee was absent atleast once ")

Step 7: Verify using membership operator (nested condition)
   - Command: if "a" in attendance:
   - in operator - Built-in membership operator
   - Provides alternative verification method

Step 8: Display confirmation message
   - Command: print("The Employee was absent atleast once ")

Step 9: Stop - End the algorithm

CONCLUSION:

The study of Tuple in Python was successfully completed
