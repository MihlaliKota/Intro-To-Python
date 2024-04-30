 # Intro-To-Python

## Python 101: Introduction to Python

### How Computers Work
----------------------

Computers process information in a complex manner that involves storing files and data in memory. The memory acts as a grid where files are stored, each with a file name and associated information like size. Accessing file contents involves the computer following pointers, which are addresses indicating where the file contents are located in memory.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/417a302d-9934-4c92-b1c3-9fffbd5a133f)
- How Computers Think

Interacting with a computer program means engaging with its memory. Programs create variables, akin to mini files, with names and addresses pointing to specific memory locations. For instance, in a program like A = 2, B = 3, C = A + B, the computer generates variables A and B, pointing to values 2 and 3 in memory. It then calculates A plus B, storing the result in variable C.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/c1affb48-3cde-4692-8430-57182822588e)
- Simple Program

Consider the following scenario: A represents a list of numbers in Python, [1, 2, 3, 4, 5]. When we assign B to A, B essentially refers to the same memory location as A.

This linkage means that any alterations made to A will also impact B. For example, if we change the value of 1 in A to 6, B will reflect the same modification. Understanding this concept of memory assignment is vital in programming, as it involves direct manipulation of the computer's memory for inputting, retrieving, and altering data. Hence, comprehending the underlying processes is crucial.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/70091c7e-24fc-4013-bfe6-ffe44f723230)
- List Program

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/8730487a-b710-45b2-9fc9-fbefcea7c7e9)
- Altered List Program

Understanding the inner workings of computers when executing programs is crucial, particularly in handling complex programs. When assigning one variable to another, rather than creating a copy, both variables point to the same memory location. Therefore, modifications to one variable will impact the other. This understanding is fundamental when programming and manipulating data in computer memory.

### Zen of Python
-----------------

Python has gained popularity over its three-decade existence, contrasting with the perceived clumsiness of JavaScript. Python is celebrated for its elegance, offering a modern language experience. Its syntax promotes consistency, ensuring similarity in calling functions. Developers deliberately maintained Python's simplicity and coherence, catering not only to beginners but also to complex system development. Python excels in managing intricate scenarios, aligning with its ethos encapsulated in the "import this" mission statement.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/4e0096a0-4ff8-48c3-8e4e-6bd8aea5e9f9)
- Starting up Python in a terminal

To enter the Python command prompt, launch a terminal and input "Python." Upon opening, you'll notice three greater-than symbols, signaling that the prompt awaits Python code input.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/c629cee4-a03e-4fdc-b1ab-43beccd71198)
- Running the “import this” statement

To continue, enter "import this" command. Here, "import" retrieves a module for use, and "this" denotes the module we're fetching. We'll delve deeper into import statements later, but for now, input "import this" at the command prompt to print the document.

### Variables and Types
-----------------------

The fundamental element of a program is termed a variable, which receives a value using the equal sign as an assignment operator. In Jupyter Notebooks, cells are executed with Shift + Enter, and a new cell can be added by clicking outside the margin and typing 'a'. Variables cannot begin with numbers, but they can contain uppercase and lowercase letters along with underscores. Conventionally, variable names in Python start with lowercase letters.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/72761aaf-a31e-4748-a102-3dc780c05c66)
- Introduction to Variables

Python encompasses various variable types: integers for whole numbers, floats for decimals, complex numbers for intricate math, strings for character collections, and Booleans for true/false values. Concatenating strings employs the plus sign, though it's not viable for mixing strings and numbers. Error messages furnish valuable insights during Python operations.

### Data Structures
-------------------

Python's data structures enable bundling multiple values within one variable. The initial structure explored is a list, capable of holding various data types, even lists within lists. List length is assessable via the length function. Sets, resembling lists but comprising only distinct elements, are initiated with curly braces.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/b07e5037-6db1-4736-a444-2e0e2a9aaee2)
- Introduction to Data Structures

Sets don't retain element order, unlike lists. Tuples resemble lists but are immutable once defined. They're beneficial for storing data efficiently, like coordinate pairs. Dictionaries consist of key-value pairs akin to a word-definition pair. Declared with curly braces, dictionaries are accessed via keys.

### Operators
-------------

Operators in Python are commands that execute actions on variables and values, facilitating data manipulation. Among them, arithmetic operators are prominent, performing mathematical computations. Addition is a typical arithmetic operator, yielding the sum of two values. Python offers various other arithmetic operators, like the multiplication operator, denoted by '*', which multiplies numbers. Additionally, the exponent operator raises a number to a designated power.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/ef71bdb2-aa18-4966-9bb9-d34a88e6acbd)
- Introduction to Operators

Operators in Python facilitate various operations on variables and values. Arithmetic operators, like division (/) and modulus (%), handle mathematical calculations. Division returns a floating-point value, while modulus provides the remainder after division, valuable for programming tasks.

String manipulation also employs operators. The addition operator concatenates strings, while multiplication repeats a string. It's noteworthy that addition is limited to string concatenation, whereas multiplication works with strings or numbers.

Another group of operators includes comparison, logical, identity, and membership operators. Comparison operators assess variables, yielding true or false results. Logical operators ('and', 'or', 'not') operate on Boolean values, determining their truth values. Membership operators ('in' and 'not in') ascertain presence in a sequence.

These operators serve diverse purposes in Python, enabling operations and comparisons. Although initially daunting, familiarity and practice with these concepts will develop through the course.

### Control Flow
----------------

The if statement is a fundamental aspect of programming's control flow, permitting the execution of code blocks based on specified conditions. In Python, it's utilized as follows: "a = True, if a: print('It is true')." If the condition holds true, the indented code beneath the if statement executes. Additional code can be incorporated under the if statement by further indentation. Integration of an else statement facilitates execution of its code block if the condition evaluates to false.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/05ef281e-22a0-49ce-8ec9-20839d49b693)
- Introduction to Control Flow

Indentation is crucial in Python as it delineates program structure. Iteration over lists or other iterable objects is achieved through for loops. The syntax is: "for item in my_list: print(item)." Here, "item" is a variable representing each list element, with a customizable name. While loops, akin to for loops, persist until a condition is false. A while loop in Python appears as: "a = 0, while a < 5: print(a), a = a + 1." Ensuring the eventual falsity of the while loop's condition prevents indefinite looping.

### Functions
-------------

A function acts akin to a machine, transforming inputs into outputs, analogous to a toaster converting bread into toast. Despite variations in input, the toaster operates according to its toasting function.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/3f0173dd-4389-47c3-8fa4-9ede65fd3fca)
- Introduction to Functions

In Python, functions are defined using the "def" keyword followed by the function name and arguments in parentheses. The function body, indented below, contains the code executing the desired operation on the inputs, with the "return" keyword specifying the output. Functions can have one or more arguments and may or may not return a value.

For instance, a function could alter a variable without returning anything. The print function exemplifies a function not returning anything but displaying output in the console. The special Python term "None" signifies the absence of a value, serving as the default return value for functions that don't explicitly return anything.

### Classes and Objects
-----------------------

In previous sections, we delved into the singular function of a toaster. However, for a comprehensive kitchen setup, diverse capabilities are essential: toasting, baking, microwaving, dishwashing, and coffee making, each with unique settings.

For example, a toaster might feature a knob, while a microwave operates with power settings. Similarly, a dishwasher boasts various modes and functions. Scaling up to multiple kitchens or entire houses, each with distinct rooms and functionalities, can result in sprawling, unwieldy code rife with numerous functions and variables.

To navigate these complexities, programmers devised a tool in Python known as a class. Classes assist in categorizing and organizing related sets of functions and attributes, streamlining code management in complex scenarios.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/81eb8299-662c-4858-9b41-313d096241e7)
- Introduction to Classes and Objects

As an illustrative example of classes in programming, let's consider the creation of a class named Dog, which encompasses multiple functions and attributes such as legs, a name, and bark. When defining a class, we capitalize the class name and specify its functions and attributes within the class definition.

Typically, we initiate with a special function known as the initialization function, or "init" function, which executes whenever an instance of the class is generated. This init function accepts a variable named "self," referencing the specific instance of the Dog class.

Subsequently, we define the attributes and functions of the Dog class. For instance, we can instantiate a Dog with four legs and the name "Rover," along with a function named "speak" that outputs "bark." Accessing any attributes or functions within the class is facilitated by the "self" variable.

To employ this class, we create a new instance by invoking "dog" and providing any required variables such as the dog's name. Multiple dogs with distinct names can be instantiated, each having access to all functions and attributes of the Dog class.

The speak function takes "self" as its initial variable, denoting the instance of the class upon which the function is invoked. These instances are referred to as objects, with their internal variables termed attributes and their functions labeled methods.

This serves as a concise introduction to object-oriented programming concepts and terminology, which wield considerable power and utility.

### Ints and Floats
-------------------

Let's return to integers (ints) and floating-point numbers (floats), essential numeric types in Python, to examine their interaction, conversion methods, and potential pitfalls.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/d74f8019-a673-4ea9-8155-01ade9c8eaef)
- Ints and floats revisited

In our earlier example, we observed that division involving integers yields a float result, like 20 divided by 4 giving us 5.0. Python automatically adjusts to floats to accommodate non-whole numbers. Operations like addition, multiplication, and exponentiation involving a mix of floats and integers also produce float results.

To convert a float, such as 256.0, back to an integer, we utilize the int class, not a function. Despite its appearance, int is a built-in class in Python, similar to other types like strings, floats, and lists. When transforming from one type to another, such as float to int, it's termed casting. While casting is straightforward, it can pose challenges when dealing with values like 8.9, which casts to 8, not 9. Python doesn't round when casting floats to ints; it simply discards the decimal part. For rounding a float to the nearest integer, the round function is employed. Additionally, the round function allows specifying the desired number of decimal places to round to, such as rounding 4.67 to 5.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/35b9178f-cba9-476e-bf29-bffde3303a46)
- Ints and floats revisited continued

A potential challenge with floats lies in their approximation nature, often resulting in rounding discrepancies. For instance, subtracting 1.0 from 1.2 yields 0.19999999999999996 instead of the expected 0.2. Floats are stored in memory as binary representations of ones and zeros, constrained by finite memory, prompting Python to make approximations, thereby introducing rounding errors. Nevertheless, employing the round function can alleviate this issue.

Caution is warranted when using floats, especially in scenarios such as financial transactions where precise decimal values are crucial. In the subsequent section, we'll explore strategies for managing decimals, particularly in financial contexts.

