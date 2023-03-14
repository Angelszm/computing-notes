

Slide 1 (Topic 1)
- Computer Program  (Machine Language) 
- Compliation, Execution, Data, ALgorithim, Input, Output
- SDLC (Planning, Requirement, Requirement Analysis, Defining Requirements, Design, Implemenation, Testing, Maintenenance)
- SDLC (why need ?)
```
The SDLC is necessary to ensure that software systems are developed and maintained in a structured and systematic manner, with consideration for user needs, quality, and efficiency.
-(to manage software complexity and to facilite production of detect free software)
```

Neeeds SDLC 
```
To manage software complexity and to facilitate production of defect free software that conforms to user requirements.
- Efficiency and productivity
- Customer satisfaction
- Risk management
```


SDLC Models
- Waterfall 
- Iterative waterfall
- Prototyping 
- Agile

Agile
- A flexible and iterative approach to software development that emphasizes collaboration, continuous improvement, and rapid delivery of working software.
```
- User Involvement
- Iterative, Incremental
- Flexibley, Prioritisation, Collaborative
```

- Constructor
```
- function is always called the same thing as the name of the class. ) 
```
- Accessor Function (getter and setter)
```
get function 
set function
```
- Method Overloading
```
methoad signatures two functions with the same name. have different signatures if they have different parameter list.  (Same name different parameter)
```
- Assembler
```
A program that translates assembly language code into machine language code that can be executed by a computer.
```
- Interpreter 
```
A program that translates high-level programming language code into machine language code on-the-fly, executing the program as it is being translated.
```
- Compiler
```
Compiler: A program that translates high-level programming language code into machine language code before the program is executed, generating an executable file that can be run independently.
```
- High Level Programming Languages
```
High-level programming languages are designed to be easy to read and write, with a focus on abstraction and productivity. (is written in the manner that human beings can understand. 
```

Regression Testing (code changes)
```
- Regression Testing is a type of testing that is done to verify that a code change in the software does not impact the existing functionality of the product. 
- A type of software testing that verifies that changes made to a software application do not adversely affect existing functionality. Regression testing involves re-executing test cases that have already been executed in previous cycles of testing, in order to ensure that previously working features still work as intended after changes have been made.
```

White-box Testing (the whole code, especially desk-checking, Testing the flow of execution through a unit using desk-check)
```
A type of software testing that examines the internal workings of an application or system, including its code, data structures, and algorithms. White-box testing is typically performed by developers or quality assurance engineers with access to the application's source code, and it can help to identify defects or issues that may not be visible through other types of testing.
- White box testing is a type of testing where the tester can see the code. The main purposes of this type of testing are to test the inner workings of the software, as well as strengthen its security, and improve its usability and design.
```

Black-box Testing (only result: input, output, Testing the results that come from a unit)
```
A type of software testing that focuses on the external behavior of an application or system, without knowledge of its internal workings. Black-box testing is typically performed by testers who do not have access to the application's source code, and it is designed to verify that the application or system meets its functional and non-functional requirements. Black-box testing can involve various techniques such as functional testing, usability testing, performance testing, and security testing.
```

Unit Testing (function test, Testing of a single function in isolation)
```
A type of software testing that focuses on verifying the smallest testable parts of an application, typically individual functions or methods. Unit testing is often performed by developers during the development process, and it is designed to ensure that each unit of code performs as intended and meets its specified requirements. Unit tests are usually automated, and they help to catch defects early in the development process, reducing the risk of introducing bugs or errors into the application.
```
Integration Testing (different features/different modules for each, different funtions to work together )
```
A type of software testing that focuses on testing the interactions and interfaces between different modules, components, or systems within an application. Integration testing is performed after unit testing, and it is designed to verify that the individual units of code work correctly when integrated together as a larger system. Integration testing can help to identify defects or issues that may arise due to dependencies or interactions between different parts of the application, and it can ensure that the application functions as intended as a whole. Integration testing can be performed at different levels, such as module level, subsystem level, or system level, depending on the complexity of the application.
```


Topic 2
- Good Algorithm
- good algorithm (robust:testing, complete, efficient, readable, maintainable, documented)
```
- Complete: Arrive at desired conclustion
- Robust: unlikely situations and incorrect data
- Efficient: minimun number of steps
- Readable: people can understand
- Maintainable: can change in future
- Documented: instructions
```

Pseudocode
```
- Logic 
- Not Real Programming Code 
- logic of an algorithm 
- can check the correctness on paper
````

Bubble Sort:  (Swap)
```
A simple sorting algorithm that repeatedly steps through a list of items, compares adjacent elements and swaps them if they are in the wrong order. The algorithm passes through the list until no more swaps are needed, indicating that the list is now sorted. Bubble sort is easy to understand and implement, but its performance is not efficient for large datasets.
```

Quick Sort: 
```
A fast, recursive, and efficient sorting algorithm that works by partitioning an array into two smaller sub-arrays around a pivot element. The algorithm selects an element in the array (the pivot), and then rearranges the other elements so that all elements less than the pivot are placed before it, and all elements greater than the pivot are placed after it. The algorithm then recursively sorts the sub-arrays on either side of the pivot. Quick Sort has an average case time complexity of O(n log n) and is often considered one of the most efficient sorting algorithms.
```

Pseudocode 
- whole number, real number, string 
- Desk Check 
```
 Desk-checking is a technique used in software development to manually review code to ensure that it is correct and meets the requirements of the program. 
 - the process of working through each line of code in an algorithm
```

Desk Checking Pseudocode (Table: Rows and Columns)
- Rows : for each code line and instructions
- Column: Code, Variables, Notes
```
- each code line
- Variable Names,
- Notes 
```
- Commenting (only 4)
```
- single line comment - //
- multi - /*   */
```

- Data <name> as <type> (Data myAge as whole number)
- Input into myAge
- Output myAge


Topic 3
Data Representation 
- Whole Number : integer
- Real Number: floats 
- Boolean 
- Single Character
```
Data a as string : "Hey"
Data b as whole number: 123
Data c as real number: 1.23
Data d as Boolean : True
Data e as character: 'M'
```

 - Primitive Data : value data rypes (whole/real numbers)
 - Complex : reference data types 

 

 
Iteration 
- Bounded iteration (They know how many times to repeat)
```
In bounded iteration, the number of times the loop will execute is known before the loop starts. A loop with a fixed number of iterations is an example of bounded iteration.
- A loop that will iterate a known number of times
```
- Unbounded iteration (They don't know how many times to repeat)
```
In unbounded iteration, the number of times the loop will execute is not known before the loop starts. A loop that continues until a certain condition is met is an example of unbounded iteration.
- A loop taht will iterate an unknown number of times
```

Why Iteration 
```
- There are several major problems with this. If you need to change the logic of one, you need to manually change the logic in all. 
```

Condensing Loops
```
- Calculate enough loops that you can be sure that the pattern is reliable. 
- It also means you can desk-check large loops without having to do it all manually. but it is still only an approximation. 
To condense loops, programmers may use features such as list comprehensions or generator expressions to express the loop in a more concise form.
- Removing the need to step through every line of code in a large loop by identifying the pattern that lets you approximate. 
```
 
Topic 8- Array 
sideof (Number of not known arrays : like user enter 10 and will loop with 10, if 15 and then 15 loop)

Two Dimensional Arrays
```
data myGrip as array (row,column) of whole numbers
- Creating
- data myGrip as array (10,10) of whole numbers
- Setting
    - myGrip [9,5] =100
- Getting
    - output myGrip[9,5]
```

 
Topic 9 : Searching and Sorting

Linear Search 
- best case is 1 check 
- worst case is N checks
- average case is N/2 checks
 
Search and sort notes
```
- linear (simplest kind)
- binary  (ordered array, ascending, descending)
- bubble sort (simplest form of sort )
- quick sort (splits an array into sub-arrays and sorts each individually, much better algorithm)
Quick Sort is more efficient than Bubble sort. 

Binary Search - need ordered array to function
Binary Search better than linear search 
```

Scaling 
 - Making an algorithm work for large amounts of data and operations. 
 

```
Big O Notation belongs to linear search. 
O(1) -constant scale (constant time complexity)
O(N) - Linear (directly propotion size)
O(N^2) - Bubble sort (Swap) = quadratic time complexity
O(nlogn) - Quick Sort
O(logn)  - logarithmic time

```
Scale : means the shape of curve showing the number of attempts based on the size of data being operated. 
 - the performance of the algorithm changes predictably as the size of the input data increases. 

Sorting Method 
- Bubble sort
- quick sort 
- Linear sort



Bubble Sort 
- Check adjacent pairs and then swap them require to step over the whole array several times. 
Swap 
```
loop while -- swap = true 
- the purpose of first loop - to check the entire array of elements is ordered using boolean variable swapped. 
```

Quick Sort 
```
use recursive 1
divide and conquer
by spilling an array into two selections
- sort each arry individually 
- recursive 
```

Topic 10: 
Objects and classes
Objects
```
- specific instantiation of class 
- class data type
- A varibale created from our data type 
```

Classes
```
- can have functions within them
- classes are more powerful than array 
 - A cusutom data type we create
```

 Instantiation
 - Creating an object from a class
 
 
 Topic 11: Data Structures
 
 
 
 ### PseudoCode Syntax 


- Data <name> as <type> (Data myAge as whole number)
- Input into myAge
- Output myAge

- whole number, real number (datama), string

### Example Programs


PseudoCode Example 
```
data myAge as whole number
data myNewAge as whole number
output "Please enter your age"
input myAge

myNewAge = myAge + 1
output "In a year you will be"
output myNewAge

```
PseudoCode Example1
```
data firstNumber as whole number
data secondNumber as whole number
data answer as whole number

output "Please enter a number"
input firstNumber
output "Please enter a second number"
input secondNumber

answer = firstNumebr * secondNumber
Output "The answer is "
output answer
```


Iteration - Bounded Loop -1
```
data counter as whole number
data sum as whole number
counter =1
loop until counter is equal to 10
    sum = sum  + counter
    counter = counter + 1
Next Loop  
```


Iteration - UnBounded Loop -1
```
data userInput as character
Loop until userInput is equal to Q
    output "Give me a letter!"
    input userInput
    next loop 
output "Oh, I really don't like that letter"
```


Example from Old Questions
```
 data counter as whole number
 loop while counter is less than sizeof(nums)
  output nums[counter]
  counter=counter+1
 next loop
End Function
```


```
loop while counter1 is less than sizeof(nums)
  loop while counter2 is less than sizeof(nums[counter1])
      nums[counter1][counter2]=0
    counter2 = counter2 + 1
  next loop
  counter1 = counter1 + 1
next loop
```


```
Function isPositive(needs p as whole number) returns Boolean
    Data result as Boolean
    result=false
    if p is greater than or equal to 0 then 
        result = true
    endif
    return result
End function 
```

create a new object named Mercedes of type Vehicle
```
Data Mercedes as Vehicle
Mercedes=new Vehicle ("A180", 2021, 4419, 47.9)
```
