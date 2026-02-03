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
   
   - Indexing and slicing
     
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

ALGORITHM:

1. Display Student Marks Statistics
   
- Start – Begin the process of analyzing student marks.

- Input marks tuple – Provide a tuple containing student marks.

- Find maximum – Use max() to get the highest mark.

- Find minimum – Use min() to get the lowest mark.

- Count elements – Use len() to determine how many marks are present.

- Calculate sum – Use sum() to add all marks together.

- Compute average – Divide total marks by count to get the average.

- Sort marks – Use sorted() to arrange marks in ascending order.

- Display results – Show maximum, minimum, average, and sorted list.

- Stop – End the algorithm.
  
2. Unpack Tuple Data
   
- Start – Begin the process of unpacking tuple data.

- Input result tuple – Provide a tuple containing subject, marks, and grade.

- Unpack tuple – Assign each element to separate variables.

- Check condition – If marks ≥ 75, set distinction status to "Yes", else "No".

- Display results – Show subject, marks, grade, and distinction status.

- Stop – End the algorithm.

3. Employee Attendance Analysis
   
- Start – Begin the process of analyzing attendance.

- Input attendance tuple – Provide a tuple with 'p' for present and 'a' for absent.

- Count present – Use count("p") to find total present days.

- Count absent – Use count("a") to find total absent days.

- Check condition – If absent days > 0, status = "Absent at least once".

- Else condition – If no absences, status = "Always Present".

- Display results – Show present days, absent days, and status.

- Stop – End the algorithm.
  
PRACTICAL APPLICATIONS:

Use tuples for: database records, coordinates, function returns, dictionary keys, configuration data, RGB values, dates

Use lists for: dynamic data, frequent modifications, sorting in place

CONCLUSION:

Tuples provide efficient, safe storage for fixed collections in Python. Their immutability ensures data integrity while offering performance benefits over lists. This experiment successfully demonstrated tuple operations, memory behavior, and real-world applications.
