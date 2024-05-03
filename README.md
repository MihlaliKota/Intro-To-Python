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

### Alternative Number Types
----------------------------

Let's delve into some fascinating capabilities of the int class in Python. When a number is passed as a string, the int class swiftly converts it to an integer. For example, "100" becomes the integer 100. Even more intriguing is its ability to convert from different number bases to base 10 when provided with a second argument as the base. For instance, "100" in base 2 translates to 4 in base 10.

However, it's imperative that the first argument is always a string, even for conversions from different bases. This precaution is necessary as there may be non-numeric characters in the string, valid in certain bases like "1ab" in base 16. However, "1ab" is not a valid integer, highlighting the importance of the string format.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/de1c8cae-5298-4405-89a2-8011cfd5a6ec)
- Integers (int)

Continuing forward, Python offers an alternative number class known as "decimal," aimed at resolving the concerns associated with floats highlighted in the prior video. While floats are versatile, their floating-point inaccuracies can pose challenges, particularly in contexts like financial calculations. To utilize the decimal module, one must import both the decimal class and the getcontext function at the beginning of the code. The getcontext function retrieves a context object responsible for managing global settings pertinent to utilizing the decimal class. These settings, including precision, can be adjusted by altering the attributes of the context object.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/3e72f7d8-e6a1-4614-b0f0-c1c99a3bb33a)
- Decimals

Using the decimal class, you can create a decimal object with a numerical value. For instance, dividing decimal 1 by decimal 3 yields 0.3333 with four decimal places. While you can pass in a float, note that the decimal module strives to replicate the float precisely, potentially leading to floating-point inaccuracies. In such instances, it's advisable to provide the float as a string. The decimal class offers various representations for numbers, so consult the documentation for comprehensive details.

Is it necessary to always employ the decimal class instead of floats? Not necessarily. It's crucial to round appropriately before presenting values to users and exercise caution with extremely small or large numbers. For most scenarios, floats suffice. Thus, rather than returning a result like 1.2 minus 1.0, it's preferable to round it first and then display the rounded outcome to users.

### Booleans
------------

Previously, we touched on Booleans, seemingly straightforward with true and false values. However, there are nuances worth exploring, particularly given their frequent usage in programming. At times, I find myself verifying boolean logic in the Python terminal to ensure accuracy. So, let's delve deeper into this topic.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/f64893a6-3624-4ebd-84c1-2e6455dcdf33)
- Booleans

Let's begin by discussing casting. Python seamlessly converts integers to booleans—1 translates to true and 0 to false. Essentially, anything except 0 is true, encompassing even negative numbers like -1 and imaginary ones like 1. However, float 0 and imaginary 0 are false.

What about strings? Naturally, the string "true" is true, and any non-empty string is also true, including "false". The sole false string is an empty one, but beware of inadvertently adding a space.

Data structures can also be cast to booleans. An empty list or dictionary registers as false, whereas any content within renders it true. Python interprets a non-value return from a function as false.

Understanding boolean casting in Python holds significant importance as booleans primarily feature in if statements or loops, necessitating comprehension of their value evaluation. For instance, we can convert a list to boolean to ascertain if it contains any values.

Multiple approaches exist to assess a boolean, demanding careful consideration of logic. For instance, when deciding whether to go for a walk based on weather conditions and umbrella availability, the statement "if not have an umbrella or weather is nice, go for a walk; else, stay inside" may seem logical. However, Python evaluates booleans left to right, prompting the need for parentheses or an "and" statement to ensure correct logic.

### Strings
-----------

Python tasks frequently entail working with strings, whether parsing them for data extraction or constructing them to convey information to users. Fortunately, Python provides a plethora of tools for string analysis and construction, with slicing being particularly valuable. Slicing involves extracting a segment of a string and returning it.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/01860264-7dd9-4ba1-ab6c-1d4e5b38dd3f)
- Slicing

Consider the string "My name is Iron-Man." To retrieve the first character, we utilize name[0] since programmers commence counting from zero. Similarly, the second character is obtained using name[1]. Extracting the initial seven characters of the string involves the syntax name[0:7], capturing characters from index zero up to but excluding the space following "name." Alternatively, shorthand notation name[7] achieves the same outcome. To obtain all characters from index 11 to the end of the string, we employ the syntax name[11:], leaving the end unspecified.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/ccd4300a-5ab9-4b5c-bb25-bebf3dec6545)
- Formatting

Python offers various methods for string creation, such as string concatenation and f-strings. F-strings permit the insertion of variables or expressions within curly braces directly into a string. Additionally, f-strings facilitate rounding and number formatting. The format function, akin to f-strings, was prevalent in Python versions predating 3.6.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/e90f5e88-7990-4cff-8293-068a782bbe0f)
- Multi-line Strings

Lastly, Python provides a convenient method for generating multi-line strings through triple quotes. To incorporate literal triple quotes within the string, escaping them with a backslash is necessary. While Python boasts numerous string functions and methods, further exploration of these will be covered later. In the meantime, for comprehensive details, refer to the official documentation available on Python's website.

### Bytes
---------

Let's delve into the Python byte object. While it's not an everyday tool, it plays a vital role behind the scenes in programs. Typically, it's data that circulates but is seldom directly altered. Computers store information as binary digits—ones and zeros. When Python loads this data, it discerns its type—string, integer, class, etc. However, sometimes you merely require raw data, like a random sequence of binary digits. This is where the bytes object proves valuable. It serves as a straightforward sequence of data, devoid of additional context that Python typically associates with loaded data. The bytes object finds common usage in streaming files or transmitting text without encoding knowledge. Let's explore how to identify and leverage the bytes object.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/6d0f4d40-89e2-4064-826f-407e0265b098)
- Bytes

### Lists
---------

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/6c83eff9-381a-46b4-aad1-208274da92b9)
- List Slicing

In Python, strings, akin to lists, share the same slicing syntax. Slicing facilitates the extraction of a range of values from both lists and strings, with the option to include a third value to dictate the step size. Additionally, the range function aids in generating longer lists, which are also susceptible to slicing. Negative values enable backward traversal through the list. Collectively, these operations enable the extraction of data from lists or strings, one value at a time.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/42645aaf-0954-40d8-9c5b-09489198c7b1)
- Modifying lists

In this section, we'll explore how to modify lists in Python. To append an item to the end of a list, we can utilize the append() method. For example, if myList contains values 1, 2, 3, 4, appending 5 is achieved by typing myList.append(5) and then printing myList.

Inserting an item at a specific position in the list is accomplished using the insert() method. For instance, inserting the value 10 at position 3 in myList is executed with myList.insert(3, 10), followed by printing myList.

There are two primary methods for removing items from a list. The remove() method eliminates an item based on its value, while the pop() method removes and returns the item at the end of the list. For instance, typing myList.remove(5) removes the value 5 from myList, whereas myList.pop() removes the last item.

Using a loop with pop() allows for removing all items from the list. For example, employing a while loop with the condition while len(myList) > 0: and executing myList.pop() inside the loop results in an empty list post-iteration.

When assigning a list to a variable, the variable stores a reference to the list, not a copy. Consequently, modifications made through one variable are reflected in others referencing the same list. However, to create an independent copy of a list, preserving the original, the copy() method can be employed. For instance, to duplicate list a with values 1, 2, 3, 4, 5, one can type b = a.copy() and then print both a and b to observe the disparity.

Lists represent a fundamental and potent data structure in Python, necessitating a thorough understanding of their manipulation. Experimenting with various methods discussed here is advisable to become proficient with their functionality.

### Tuples and Sets
-------------------

Let's delve deeper into two data structures we previously introduced: tuples and sets. Beginning with sets, they are delineated using curly brackets, for instance: {'a', 'b', 'c'}. Alternatively, a set can be defined by passing any iterable object into the constructor of the set class, exemplified as: mySet = set(('a', 'b', 'c')).

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/709a8810-8a3d-4b18-b0a8-3f039f023c37)
- Sets

A prevalent application of sets in programming is eliminating duplicates from a list, as sets inherently store only unique values. To illustrate, consider a list with duplicates, and to remove them, convert it into a set and then back into a list: myList = ['b', 'c', 'c'] mySet = list(set(myList)).

Sets offer functionalities such as checking membership with the 'in' operator and determining the set's length using the len() function. Additionally, sets possess a pop() function, which removes and returns an arbitrary element from the set.

Turning to tuples, they resemble lists but are declared with parentheses rather than square brackets. For instance, a tuple named myTuple with elements 'a', 'b', and 'c' necessitates commas between them. Tuples maintain order and support indexing like lists; however, they are immutable, precluding modification. While elements can be retrieved from a tuple using indexing, any attempt to alter them results in an error. Despite their immutability, tuples are more memory-efficient than lists, making them preferable for storing large datasets.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/a6f96ef9-7b0b-472c-b66c-305aab915513)
- Tuples

Tuples find frequent application when needing to return multiple values from a function. A convenient approach is to separate these values with commas, prompting Python to generate a tuple automatically. Although parentheses are not strictly necessary, using them enhances readability. Furthermore, the values within a tuple can be unpacked into individual variables effortlessly using the syntax A, B, C = myTuple. While tuples may not match lists in flexibility, they provide convenience and elegance in specific scenarios.

### Dictionaries
----------------

In Python, you'll frequently utilize two primary data structures: lists and dictionaries. By combining these structures, you can address nearly 95% of your data structure requirements. To illustrate, let's explore some examples using a dictionary representing animals.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/c7a98591-8281-4102-8a84-b27abbe79570)
- Dictionaries

You might observe a comma after the last key-value pair in a dictionary, known as a trailing comma. While not strictly necessary, it's considered good practice and conforms to convention.

Accessing a specific key-value pair in a dictionary is straightforward; you simply type the dictionary name followed by the key in square brackets. Similarly, to add a new key-value pair, you employ a similar syntax with the assignment operator. For updating an existing key-value pair, you access it and reassign it a new value. The keys and values of a dictionary can be accessed using the .keys() and .values() methods, respectively.

A common pattern involves a dictionary with listed values. Adding to such a structure is easy if the key already exists. However, uncertainty about the key's existence warrants the use of an if-else statement to manage both cases. Lastly, the len() function serves to obtain the length of a dictionary, akin to its use with lists or strings.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/f2518887-951b-44ee-9a98-d9b20fa30959)
- Default dictionaries

Do you find the previous code too complex? Fortunately, there's a solution that can streamline it: the default dict, available for import from the collections package.

Creating a default dict involves specifying the default return type it should provide. However, it's essential not to mistakenly pass in an instance of the desired object; rather, you must provide a callable function responsible for creating the object. Once you have your default dict, you can add items to it just like you would with a regular dictionary.

What makes default dict particularly useful is its automatic creation of a new default value if a key doesn't yet exist, eliminating the need to handle errors as a regular dictionary would. This feature greatly simplifies your code. While combining lists and dictionaries is potent in Python, the capabilities of Python data structures extend far beyond that!
