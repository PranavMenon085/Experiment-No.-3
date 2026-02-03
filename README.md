================================================================================
                            EXPERIMENT NO. 3
================================================================================

Name: Pranav Menon
PRN No.: 25070123085
Branch: ENTC
Batch: B1

================================================================================
AIM: Study of Tuple in Python
================================================================================

================================================================================
THEORY:
================================================================================

Topics Covered:

1. Introduction to Tuple
   - Understanding immutable sequences in Python
   - Tuple creation and basic operations
   - Difference between tuples and lists

2. Tuple Operations
   - Indexing and slicing
   - Tuple multiplication and concatenation
   - Accessing elements using positive and negative indices

3. Memory Location Analysis
   - Determining memory location of tuples before and after modification
   - Comparing memory behavior of tuples vs lists
   - Understanding immutability through memory addresses

4. Tuple Methods and Functions
   - Built-in functions: max(), min(), len(), sum(), sorted()
   - Calculating statistics: average, maximum, minimum
   - Sorting tuples while maintaining immutability

5. Tuple Unpacking
   - Assigning tuple elements to individual variables
   - Practical applications in data extraction
   - Conditional operations on unpacked data

6. Practical Applications
   - Working with student marks data
   - Employee attendance tracking
   - Data validation using conditional statements

--------------------------------------------------------------------------------
KEY DIFFERENCES: LIST vs TUPLE
--------------------------------------------------------------------------------

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

--------------------------------------------------------------------------------
ALGORITHM:
--------------------------------------------------------------------------------

1. Display Student Marks Statistics
   Input: Tuple containing student marks
   Process: Read marks tuple, apply max() for maximum, min() for minimum, len() for count, sum() for total, calculate average using sum()/len(), use sorted() for ascending order
   Output: Display all calculated statistics

2. Unpack Tuple Data
   Input: Tuple containing subject, marks, and grade
   Process: Read result tuple, unpack into individual variables, apply conditional check for distinction (marks >= 75)
   Output: Display subject, marks, grade, and distinction status

3. Employee Attendance Analysis
   Input: Tuple containing attendance data ('p' for present, 'a' for absent)
   Process: Read attendance tuple, use count("p") and count("a"), check if absent at least once
   Output: Display attendance statistics and absence status

--------------------------------------------------------------------------------
OBSERVATIONS AND RESULTS:
--------------------------------------------------------------------------------

1. Tuple Operations
   - Multiplication: (10,) * 5 = (10, 10, 10, 10, 10)
   - Without comma: (10) * 5 = 50 (arithmetic operation)

2. Memory Analysis
   - Tuples: Memory address changes after modification (new tuple created)
   - Lists: Memory address stays same (in-place modification)

3. Student Marks Analysis
   marks = (90, 82, 66, 76, 33)
   - Maximum: 90, Minimum: 33
   - Average: 69.4
   - Sorted: [33, 66, 76, 82, 90]

4. Tuple Unpacking
   result = ("Maths", 82, "A")
   - Subject: Maths, Marks: 82, Grade: A
   - Distinction: Yes (marks >= 75)

5. Attendance Tracking
   attendance = ("p", "a", "p", "p", "a", "p")
   - Present: 4 days, Absent: 2 days

--------------------------------------------------------------------------------
PRACTICAL APPLICATIONS:
--------------------------------------------------------------------------------

Use tuples for: database records, coordinates, function returns, dictionary keys, configuration data, RGB values, dates
Use lists for: dynamic data, frequent modifications, sorting in place

--------------------------------------------------------------------------------
CONCLUSION:
--------------------------------------------------------------------------------

Tuples provide efficient, safe storage for fixed collections in Python. Their immutability ensures data integrity while offering performance benefits over lists. This experiment successfully demonstrated tuple operations, memory behavior, and real-world applications.

--------------------------------------------------------------------------------
Date: February 3, 2026
Status: Successfully Completed
--------------------------------------------------------------------------------
