EXPERIMENT NO. 3

Name: Pranav Menon

PRN No.: 25070123085

Branch: ENTC

Batch: B1

AIM: Study of Tuple in Python

THEORY:

Topics Covered:

1. Introduction to Tuple

   - Understanding immutable sequences in Python
     
   - Tuple creation and basic operations
     
   - Difference between tuples and lists

3. Tuple Operations
   
   - Indexing 
     
   - Tuple multiplication and concatenation
     
   - Accessing elements using positive and negative indices

5. Memory Location Analysis
   
   - Determining memory location of tuples before and after modification
     
   - Comparing memory behavior of tuples vs lists
     
   - Understanding immutability through memory addresses

6. Tuple Methods and Functions
   
   - Built-in functions: max(), min(), len(), sum(), sorted()
     
   - Calculating statistics: average, maximum, minimum
     
   - Sorting tuples while maintaining immutability

8. Tuple Unpacking
   
   - Assigning tuple elements to individual variables
     
   - Practical applications in data extraction
     
   - Conditional operations on unpacked data

10. Practical Applications
    
   - Working with student marks data
     
   - Employee attendance tracking
     
   - Data validation using conditional statements

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
  
- PRACTICAL APPLICATIONS:

Use tuples for: database records, coordinates, function returns, dictionary keys, configuration data, RGB values, dates

Use lists for: dynamic data, frequent modifications, sorting in place

ALGORITHMS:

1. Display Student Marks Statistics

Step 1: Start - Begin the process

Step 2: Initialize marks tuple
   - Command: marks = (90, 82, 66, 76, 33)
   - Built-in Python tuple structure (no import required)

Step 3: Find and display maximum marks
   - Command: print("The Maximum Marks are : ", max(marks))
   - max() - Built-in function, returns largest item
   - Output: 90

Step 4: Find and display minimum marks
   - Command: print("The Minimum Marks are : ", min(marks))
   - min() - Built-in function, returns smallest item
   - Output: 33

Step 5: Count and display number of students
   - Command: print("The Number of Students are : ", len(marks))
   - len() - Built-in function, returns number of items
   - Output: 5

Step 6: Calculate and display sum of marks
   - Command: print("The Sum of marks of students are : ", sum(marks))
   - sum() - Built-in function, returns sum of all items
   - Output: 347

Step 7: Calculate and display average marks
   - Command: print("The Average marks of students are : ", sum(marks)/len(marks))
   - Division operator (/) - Built-in arithmetic operator
   - Output: 69.4

Step 8: Sort and display marks
   - Command: print("Sorted array of marks are : ", sorted(marks))
   - sorted() - Built-in function, returns new sorted list
   - Output: [33, 66, 76, 82, 90]

Step 9: Stop - End the algorithm


2. Unpack Tuple Data

Step 1: Start - Begin the process

Step 2: Initialize result tuple
   - Command: result = ("Maths", 82, "A")
   - Built-in Python tuple structure (no import required)

Step 3: Unpack tuple into variables
   - Command: subject, marks, grade = result
   - Tuple unpacking - Built-in Python feature
   - Result: subject="Maths", marks=82, grade="A"

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
   - Output: 4

Step 4: Count and display absent days
   - Command: print("The Number of days the Employee was Absent : ", attendance.count("a"))
   - count() - Built-in tuple method
   - Output: 2

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

Tuples provide efficient, safe storage for fixed collections in Python. Their immutability ensures data integrity while offering performance benefits over lists. This experiment successfully demonstrated tuple operations, memory behavior, and real-world applications.
