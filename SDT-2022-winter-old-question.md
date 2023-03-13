Q1 

```
a)  Class Name nae Function name tu dr ko (Constructor Function)
The function Hotel has the same name as the class name, this is called constructor method.
  The purpose of a constructor is to create a new object and initializes object's attributes with staring values.

(b)The two functions with the same name but has different method signatures, called method overloading in object oriented languages.
The first function has three arguments and the second function doesn't have any parameter, this feature uniquely distinguishes them.


(c) 
Function GetRooms() returns whole number
End function

Function SetDistance (needs d as real number)
Distance=d
End function

(d) The functions GetRoom and SetDistance generally known as accessor funcitons in object-oriented languages.
The function GetRoom is used to get the value of object's attribute rooms. The setDistance function is used to change the distance vlaue of an object.
```


Q2
```
a)
FIFO data structure 1,-2,5,-10
(i) tail = -10
(ii)head = 1, 
(iii) 2 number taken = 1, -2
      multiplied = -2
      the result in queue = 5, -10, -2 
        1,-2,5,-10
        -2
        5,-10,-2
        
        
b)
Top Buttom Stack data structure  1,-2,5,-10
-10 (top)        
 5
-2
 1 (buttom)
(i) buttom = 1
(ii)  top =  -10, 
(iii) 2 number taken = -10, 5
      multiplied = -50
      the result in queue = -50, -2, 1
        1,-2,5,-10
        1, -2 , -50 
      -50, -2, 1

-50 (top)        
-2
 1
 
(c) Array and Linked List
```


Q3
```
Low Range value = -4,-3,-2,-1,0,1
High Range Value = 1,2,3,4
Extreme - kyaw twar tae values
a) 
Transition in values: -1, 0, 1
Extreme Values: 5,-5
Bad Values: -8, 8
Boundary Values: 4,-4


b) 
Regression Testing (code changes)
Integration Testing (Communication: between different modules, components, or systems within an application )
Unit Testing (an isolation, test individual functions or methods)
```


Q4
```
a) Requirement stage on SDLC
In this stage, the software requirements are gathered and analyzed to determine the scope of the project. The main objective of this stage is to define the functional and non-functional requirements of the software application. (Requirements gathering, Requirements analysis, Requirements validation, Requirements management)  
The stage that comes after the Requirement stage in the SDLC is:  the Design stage


b) 2 Software Development Models
- Waterfall  or May be Iterative / DevOps Model
- Agile

c) 5 Goals 
- Efficient Development Process
- High-Quality Software
- Timely Delivery
- Cost-Effective Development
- Customer Satisfaction
```

Q5
```
a) 
- The above program have repeat code for greater than 0 function. By using a loop, we can write the code once and have it execute multiple times, which can save a lot of time and effort compared to writing the same code multiple times.
A loop can be useful in many cases where we need to perform a similar operation multiple times, such as iterating over a list or array, processing data in batches, or waiting for user input. 
- An unbounded loop is a loop that does not have a predefined endpoint or exit condition. This means that the loop will continue to execute indefinitely until some external event causes it to stop, such as a user input or a system error. 
Unbounded loops are typically used in cases where you need to continuously monitor or process data, such as in server applications or real-time systems.

b) 
Data books as whole number
Data total as whole number
input books
loop while books is not equal to 0
 If books is greater than 0 then
 total=total+books
 End If
 input books
next loop
output total
c) 
- The main difference between a bounded and unbounded loop is that a bounded loop has a fixed number of iterations, while an unbounded loop can execute indefinitely. Bounded loops are often used in cases where you know the exact number of times you need to execute a block of code, while unbounded loops are used in cases where you need to continuously process data or wait for user input.
```

Q6
a)
```
Two Dimensional Arrays
data myGrip as array (row,column) of whole numbers
(i) - data myGrip as array (5,10) of whole numbers
(ii) myGrid[2][5]=-1
```

b) 
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

c) 
```
(i) When we pass an array to a function, we do not specify its size.
(ii) the logical operator "or" means either condition must be true to give a result of true.  

```


Q7
a)
```
(i)
- Searching refers to the process of finding a specific element within a collection of data. This is typically done by comparing the target value to each element in the collection until a match is found. There are many different search algorithms, each with its own advantages and disadvantages depending on the size and nature of the data being searched.
- Sorting refers to the process of rearranging a collection of data into a specific order. This is typically done by comparing pairs of elements in the collection and swapping them if they are out of order. There are many different sorting algorithms, each with its own strengths and weaknesses depending on the size and nature of the data being sorted.

(ii)
Best scaling - O(1)
Worst - O(n^2)

Explain 
O(1) is the best possible scaling complexity, meaning that the runtime of the algorithm does not depend on the size of the input data. This is ideal because it means the algorithm will perform equally well regardless of the size of the input. Examples of O(1) algorithms include accessing a specific element in an array or checking the size of a collection.
O(n^2) is a worst-case scenario scaling complexity, meaning that the runtime of the algorithm grows exponentially with the size of the input data. This is problematic because it means the algorithm can quickly become very slow and inefficient for larger inputs. Examples of O(n^2) algorithms include bubble sort and selection sort, which involve nested loops that compare and swap pairs of elements in an array.

```
b)
```
i) linear (simplest kind)
ii) binary  (ordered array)
iii) bubble sort (simplest form of )
iv) quick sort (splits an array into sub-arrays and sorts each individually.
```

Q8
a)
```
P AND Q
F
F
F
T

P OR Q
F
T
T
T

R
T
F
F
F
```
b)
```
C = NOT A AND B
D = NOT C

Not A     B    C      D
T         F    F      T
T         T    T      F  
F         F    F      T
F         T    F      T

```

c) 
```
If var2 is greater than 0 then
    var1 = 1
End if

If var2 is less than 0 then
    var1 = 0
End if
```


Q9
```
i) Efficient algorithms do what they need to do in the **minimum numbers** of lines of code.
ii) Loops within loops are called **nested loops**.
iii) Variables which are made up of other variables are composite variables.. **(Complex data types)**
iv) Iteration is another word for **repetition**.
v) Calling a function means executing the function.
vi) Objects are created using the "new" keyword.

parameter so yin needs par ya ml. 
Function myFunction(needs value as whole number)
	If value is less than 0 then
		output “Yes”
	Else if value is greater than 0 / otherwise
		output “No”
	End if
End function
```

Q10
```
Data a as string : "Hey"
Data b as whole number: 123
Data c as real number: 1.23
Data d as Boolean : True
Data e as character: 'M'
```
