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

### List Comprehensions
-----------------------

List comprehension is a unique capability in Python distinguishing it from other programming languages. Despite its name, "comprehension" doesn't pertain to understanding, but rather to the comprehensive generation of lists. To illustrate, consider a list of numbers such as one, two, three, four, and five.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/45e43f3e-8b5e-40b1-bd36-2b73d27328ba)
- List Comprehension

With list comprehension, we can easily double each item in a list, as shown by the expression "two times item for item in my list." Enclosed in square brackets, this technique mirrors the syntax of a for loop. You have the flexibility to choose any variable name to represent list items, provided it remains consistent throughout.

List comprehension condenses a for loop into a single line while simultaneously generating a copy of the iterated list. Moreover, it facilitates filtering or applying functions to every list item.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/513b1ed6-e5aa-46c2-b3eb-1c5e058e172f)
- List comprehension with filters

Let's play around with list comprehension! As we discussed earlier, list comprehension can serve as a filter. For instance, consider a list named "my list," containing numbers ranging from 0 to 99 generated using the "range" function. We can create a filtered list by extracting only the numbers divisible by 10. This involves using the "modulus" operator to identify numbers in "my list" where the remainder after division by 10 equals 0. The result is a list comprising only the multiples of 10.

Now, let's modify the code slightly. Instead of selecting numbers divisible by 10, we'll pick those with a remainder less than 3 after division by 10. This modification yields a list containing numbers ending in 0, 1, or 2.

To enhance readability, we'll convert the filtered list into a print statement. This example demonstrates that list comprehensions are versatile tools, useful not only for numerical data but also for strings.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/83a2249e-0f4a-4de4-9065-a847992c3d35)
- List comprehensions with functions

Let me introduce you to a handy string function called "split." This function allows you to divide a string based on a specified character or string. For instance, consider the string "myString," which reads "my name is Ryan Mitchell, I live in Boston." Applying the "split" function to it using the period as the delimiter would split the string into two sentences. If no delimiter is provided, the "split" function defaults to using spaces, effectively dividing the string into individual words.

To further refine our text, we might want to eliminate periods and convert all words to lowercase. We can achieve this by crafting a new function called "cleanWord," leveraging the "replace" and "lower" functions to handle these tasks. It's worth noting that chaining functions in this manner can streamline your code, but it's essential to strike a balance to prevent excessively long and hard-to-read lines.

Now, let's implement the "cleanWord" function on our string using a list comprehension. This will yield a tidy list containing all the words in the text. If we wish to filter this list to only include short words, such as those comprising one or two letters, we could incorporate a condition using the "len" function.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/439d29c7-8e5f-4a46-978a-40a379b5d39c)
- Nested list comprehensions

List comprehensions are incredibly useful and frequently employed for tasks like text cleaning and managing large datasets. Let me illustrate a final example: nested list comprehension. With just one line of code, we can clean up words in a sentence and organize them by the sentence they belong to. Here's how it looks:

```python
cleanWord = [word for sentence in myString.split('.') for word in sentence.split()]
```

While it might seem complex initially, what's happening is that we're breaking the original text into sentences and then applying a nested list comprehension to each sentence. This produces a list of lists, forming a two-dimensional structure that groups clean words by the sentence they originated from.

In essence, list comprehensions are a fantastic addition to your Python toolkit, enhancing code readability and adhering to Pythonic principles. So, have fun experimenting with them! Congratulations, you're now officially a list comprehension expert.

### Dictionaries and Comprehensions
-----------------------------------

In Python, dictionary comprehensions offer a way to generate a new dictionary from an iterable structure, akin to list comprehensions for creating lists. For instance, suppose we begin with a list of tuples containing key-value pairs. Employing the syntax "animals = {item[0]: item[1] for item in animalList}" enables us to form a dictionary from this list. It's important to observe the use of a colon to separate the key and value, with the entire comprehension enclosed within curly braces.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/d2fb6550-ec1a-4d2c-ab0c-598877876ae4)
- Dictionaries and comprehensions

There's a more streamlined approach to crafting dictionary comprehensions using tuple unpacking. Instead of employing "item[0]: item[1]", we can simply use "key: value" and replace "item" with "(key, value)". This eliminates the need to individually index each element of the tuple. However, it's crucial to recognize that we can only unpack as many variables as there are elements in each tuple. Attempting to unpack more than two variables will result in a "not enough values to unpack" error.

Should we desire to revert our dictionary back into a list, we can utilize the "items" method, which yields a "dict_items" object containing a list of key-value pairs. This object can then be converted into a list using the "list" function. But what if we seek to alter the structure of our list?

By employing a list comprehension with the syntax "name_value = [{'name': key, 'value': value} for key, value in animals.items()]", we can generate a list of dictionary objects wherein the original keys and values are positioned under the "name" and "value" fields. This underscores the adaptability of both dictionary and list comprehensions for manipulating and formatting data in Python.

### If and Else
---------------

If you've worked with other programming languages, you might be familiar with the switch statement, which assesses a sequence of values and executes the code corresponding to the first true value encountered. But don't fret if you're unfamiliar; Python outshines other languages anyway.

Let's tackle a classic programming challenge: cycling through numbers one to 100 and printing "Fizz" for multiples of three, "Buzz" for multiples of five, "FizzBuzz" for multiples of 15, and the number itself if none of these conditions are met. We can achieve this in Python using if and else statements.

However, the code can become a tad convoluted with all the indentation. So, let's revamp it using the elif statement, short for "else if." The approach is to start with a single if statement, followed by as many elif statements as needed, with the option of concluding with a single else statement at the end to handle any unmatched scenarios.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/ae11ecc8-c4c4-4171-8eed-ecbba6e03174)
- If statements with “FizzBuzz”

If-else statements can sometimes sprawl across multiple lines, which can make the code less concise. For situations where you need to evaluate a condition in a single line, you can turn to the ternary operator. It swiftly assesses a Boolean condition, returning one value if true and another if false.

As Python enthusiasts, our aim is to craft code that's clear and easy to read. While ternary operators can help achieve this, they should be used judiciously to prevent code from becoming overly intricate.

### While
---------

When working with while loops, caution is necessary as they have the potential to run indefinitely. To exit a loop prematurely, the break statement proves useful, immediately halting the loop and proceeding to the subsequent line of code outside the loop. Conversely, if there are specific lines within a loop that you wish to bypass, the continue statement becomes handy, allowing the skipping of subsequent lines and reinitiating the loop for the next iteration from the top.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/6e952fd0-efa8-49e1-819f-e6cf3ea01824)
- While

Occasionally, you may employ a continue statement within an if statement to avoid executing certain code within a loop based on specific conditions. An alternative approach involves utilizing continue and break to enhance code readability for fellow programmers by restructuring it. While these statements may not always be imperative, discerning their appropriate usage and being prepared to employ them when necessary is crucial.

### For
-------

You will enjoy using the for loop syntax in Python. It's super intuitive, and it reads like plain English.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/075e0f07-8e2b-471b-b22d-4cc46587e284)
- For

The for loop is a fundamental construct in Python, allowing you to iterate over a list and assign each element to a variable like "item" as you move through it. It's concise and widely used in Python coding. Similar to while loops, you can employ statements like pass, continue, and break within for loops. Pass is handy for creating placeholders, continue skips the remainder of an iteration, and break halts the loop prematurely. An interesting feature we haven't explored yet is the break else statement, useful for identifying prime numbers efficiently. This pattern can also be applied to while loops. Mastering these loop constructs is key to maintaining clean and Pythonic code.

## Python 102: Python Fundamentals

### Anatomy of a Function
-------------------------

Many beginner programming courses draw parallels between programming and baking a cake, suggesting that following step-by-step instructions yields the desired outcome. While this analogy holds some truth at a surface level, programming is far more intricate. It involves intricate systems, tasks, objects, and interactions among components. Thus, programmers must adopt a mindset centered on designing programs rather than merely executing linear instructions.

In programming, functions serve as the fundamental building blocks, rather than individual lines of code. Functions imbue a program with functionality, making them indispensable. Let's explore functions further by dissecting some code to understand their mechanics in depth.

<i>Functions</i>

Functions consist of a name and parameters, which are specified using the "def" statement. Let's illustrate by creating a function called "performOperation," with "num1," "num2," and "operation" as parameters. The objective is to design a straightforward function that accepts two numbers and an operation (either "sum" or "multiply") as inputs and produces a result. If the operation is "sum," the function will output the sum of "num1" and "num2," while if it's "multiply," it will return the product of the two numbers.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/982932cc-95bc-4a43-81b5-57114c63642e)
- Functions

To demonstrate, we could invoke the function performOperation with two arguments, 2 and 3, and the operation "sum." This should yield an expected result of 5.

Yet, continuously specifying the operation parameter as "sum" might become cumbersome over time. To mitigate this, we can establish a default value for the operation parameter by utilizing named parameters or keyword arguments. Let's relocate the code and assign the default value of the operation to "sum."

<i>Named Parameters</i>

Without this part, the outcome will be five. Nevertheless, we can alternatively specify our preferred value. By assigning "operation equals multiply," we can override it. In invoking this function, explicitly stating "operation equals multiply" is unnecessary. Instead, simply provide "multiply" as the third parameter.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/ce464046-213e-44b5-8ec4-6dd26652573a)
- Named parameters

Consider adding another keyword argument, "message", to our function. Set a default message to be printed when the function is invoked. During the function call, position the message either before or after the operation. Ensure clarity by separating the arguments with commas to specify their respective positions.

<i>*args</i>

In Python, there's a rule governing the use of keyword arguments: they must follow positional arguments. The sequence of the initial two arguments is fixed and cannot be altered. However, subsequent to these compulsory arguments, keyword arguments can be arranged in any order.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/2f3dec68-f4b7-48fa-a22b-d3dfba40410a)
- *args

While optional arguments offer flexibility, they have a limitation regarding the number of variables they can handle. To enable users to input any number of variables, prepend the argument name with an asterisk symbol, creating a pointer to the supplied variables.

In the given example, the function "performOperation" is invoked with three arguments although it anticipates only one. By prefixing "args" with an asterisk, Python interprets the variable name as a reference to the passed-in arguments. However, this technique solely applies to positional arguments, not keyword arguments. Passing in a keyword argument will result in an "unexpected keyword argument" error.

<i>**kwargs</i>

To manage keyword arguments, a method named "kwargs," an abbreviation for keyword arguments, can be employed. When "kwargs" is printed, it reveals that keyword arguments are now stored as a dictionary rather than a tuple. This choice is logical because keyword arguments consist of keys and values and can be provided in any sequence, making a dictionary a suitable data structure for accessing them.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/b9d84418-082a-450f-883a-52bd180da1a6)
- **kwargs

Let's enhance the flexibility of the performOperation function further. First, import the math library using "import math". Then, redefine the performOperation function to utilize "args" as the default argument, with the operation set to "sum" by default. If the operation is "sum", it will return the sum of the args using math.sum. Alternatively, if the operation is "multiply", it will return the product of the args using math.prod.

With the function in place, we can execute the desired operation by providing the appropriate arguments. For instance, if we supply the numbers 1, 2, and 3, the result will be 6. Similarly, if we extend this to include the numbers 6, 7, and 8, the result will be 336.

### Variables and Scope
-----------------------

<i>Function Scope</i>

In a previous section, *args and **kwargs were employed to display the arguments passed into a function, providing us with a tuple and a dictionary of the passed arguments, respectively. However, there's an alternative approach that enables access to all variables within a Python function without the use of asterisks. This approach is known as the "locals" function.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/fd859a6e-e52c-4d1b-893f-b6c74a4963af)
- Function scope

<i>locals()</i>

Let's update the original function definition to execute the operation on num1 and num2, with the operation defaulting to addition. Then, we'll utilize the locals function in Python to print the output.

For example, if we call performOperation with the arguments one and two, specifying multiplication as the operation, we'll receive a dictionary containing all the variables passed in, whether provided as positional or keyword arguments.

Why the name "locals"? These are the variable names accessible only within the function. Remember, variables can be named anything within the function definition and remain available anywhere within that function. However, attempting to reference a variable outside its scope will result in an error.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/352b47c3-fd5d-4ee9-9db0-a00ba0d076f5)
- locals()

In Python, variables fall into two categories: local variables, defined within a function, and global variables, defined outside the function in the main code block. Fortunately, Python provides a convenient built-in function called globals, which allows us to access all these variables.

<i>globals()</i>

Executing the code will display numerous items, including Python's pre-built variables that prove useful when dealing with classes and packages. Additionally, Jupyter Notebooks utilize various variables to handle their data, encompassing all content within notebook cells as part of this data. Python operates various background processes, and the scope of variables accessible in a given line of code determines which variables can be utilized. This scope classification entails global variable scope and local variable scope, which we'll investigate further through experimentation with several functions.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/f674bf97-3703-4c48-a6a9-89a911bd4e5a)
- globals()

<i>Global and Local Scope</i>

We aim to develop two functions: the first one with variables A and B, and the second one with variables C and B. Each function will output its local variables. Function one will be invoked with arguments 1 and 2, while function two will be called with arguments 3 and 4. Both functions possess their distinct local variable scopes and can access any variables in the global scope. However, they lack the capability to access each other's data.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/738b42a9-4469-420d-a379-8dd667114915)
- Global and local scope

If we set a variable, "message," in the global scope and print it within both functions, we can observe that both functions can access it. However, if an attempt is made to print "varA" within function two, an error will arise since "varA" is confined to the local scope of function one, not function two.

In contrast, if "varA" is defined in the global scope, it can be printed within both functions. Python examines the local scope first when searching for a variable's data, then the global scope. We can redefine "message" within function one's local scope and print both the local and global values of "message."

We can define a function within another function, as demonstrated by the inner function within function one. This inner function is solely accessible within function one. An attempt to invoke it outside of function one will result in a syntax error. When the local variables in function one are printed, the inner function is designated as a variable. This prompts us to question whether functions can be treated as variables.

### Functions As Variables
--------------------------

<i>Variables as Functions</i>

Variables and functions both have names and data associated with them. However, for functions, this data includes information about required parameters and the lines of instruction to be executed. In Python, a function is represented as an object.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/9db0c9fe-e8ab-4ad1-9f32-90ea66f7493e)
- Variables as functions

<i>Viewing Function Data With  __code__</i>

By accessing the "code" attribute of Python function objects, one can verify that functions are essentially variables in Python. Utilizing this attribute, you can print the names of variables and byte objects for all lines of instruction within a function. However, this is not a commonly employed technique in typical programming scenarios.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/10615dbf-1be1-4227-a71b-1dedf97c8f5d)
- Viewing function data with  __code__

<i>Text Processing in Python</i>

Consider a scenario with familiar text and function names to illustrate a concept. Two text processing operations and a function capable of converting text to lowercase, removing punctuation, new lines, words of three characters or fewer, and long words. By listing these functions, one can change their order or decide which ones to apply.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/56f88484-1d29-4bc9-b16d-7aa75071e4d9)
- Text processing in Python

We'll assemble a list named "processing functions" containing operations like "lowercase," "remove punctuation," and "remove new lines." Then, through a for loop, we'll execute these functions on a text variable and display the modified text. If we include "remove long words" in the list, it will also eliminate short words. This method is highly adaptable for business processes with dynamic needs, offering flexibility in choosing and arranging text processing operations.

<i>Lambda Functions</i>

Lambda functions provide a means to define a function without explicitly assigning it a variable name. Similar to how simple expressions like 5 or 2 + 3 can stand alone without being stored in a variable, lambda functions can be created using the lambda keyword. For instance, lambda x: x + 3 is a lambda function that takes a parameter x and returns the result of adding three to it. Lambda functions don't require the return keyword since it's implied.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/ddacb33e-8c97-49c8-8061-0d8c6565593b)
- Lambda Functions

Lambda functions are useful when you want to pass a function as an argument to another Python function, like the sorted function, which sorts a list of values. For example, if you have a list of dictionaries and want to sort them based on a specific key, you can use the key parameter of the sorted function and pass in a lambda function. This lambda function takes an item in the list and returns the value to be used for sorting.

Lambda functions offer conciseness and convenience for creating small functions needed during code writing. That's it! You now have a foundational understanding of Python functions!

### Anatomy of a Class
----------------------

<i>Instance Attributes</i>

Understanding classes can be daunting, especially when it comes to identifying their purpose and how to assign members to them. Despite this complexity, consider a previously defined class, the dog class, as an example. It comprises two instance attributes, name and legs, both inherent to every instance of the dog class. For instance, when creating a new instance like "Rover," accessing its name and legs is as simple as using "my_dog.name" and "my_dog.legs," respectively.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/123b777b-ee57-4784-bb28-782494645e28)
- Instance attributes

So, we may ask ourselves, is having four legs an inherent property of being a dog? Even though three-legged dogs are adorable, we can create a class for them as well.

<i>Static Attributes</i>

Let's alter how the legs attribute is managed in the class for now. Rather than defining it within the constructor, let's set it as a static variable outside of the constructor. Consequently, every instance of the class will share the same value for legs. Accessing the legs attribute directly on the class itself can be done by calling `dog.legs`. These variables are termed "static" because they remain constant across instances and are typically employed to store constants or essential business logic.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/38d13be3-f07c-431a-b74e-98acb8ece49f)
- Static Attributes

A getter method retrieves the value of a variable, denoted as `get_legs` in this scenario. Interestingly, it doesn't require the `self` attribute to be passed because `legs` is a static variable within the class. While it's customary to call the method without passing in `self`, it's also permissible to include it.

Remember to be careful when creating a class and think about how it will be used and what's most convenient for the user.

### Instance and Static Methods
-------------------------------

String parsing is often a fascinating task in Python. To exemplify this, let's create a class named WordSet, designed to manage a set of words:

1. Begin with an empty set and populate it by feeding in large text blocks, inclusive of punctuation.
2. Utilize the method `add_text` for incorporating text. Initially, invoke the `clean_text` method to eliminate punctuation and convert all characters to lowercase.
3. Proceed by using the `split` function to transform the sentence into a list of words, subsequently adding them to the set.
4. Conclude by printing the set of words.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/4b3d3864-e34c-47e8-8c9f-ed5c5cb4277f)
- Static instances and methods

The method `clean_text` is designated as static since it's not tied to any specific instance of the class. On the contrary, `add_text` is an instance method, specific to a particular instance. Static variables like `replace_puncs` can be introduced to regulate which punctuations are replaced. These static variables can be referenced either through the class name or a class instance, unlike instance methods, which can't be accessed via the class name.

We can solve this issue in Python by using a decorator, which is a special annotation or description for a function definition. 

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/e5b2e887-50b5-45f5-b2a5-1e0dbced79fd)
- Decorators

By adding the @staticmethod decorator to the function definition, it explicitly states in Python that the function is a static method and should not have "self" passed in as an argument. This allows us to use the function without creating an instance of the class. 

### Inheritance
---------------

<i>Class Inheritance</i>

In computer science and Python programming, one class can inherit all the methods and attributes of another class. The original class is called the parent class, and the new class that extends it is termed the child class. This inheritance occurs automatically when the child class is created.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/543678ae-0e44-4c48-90f1-0488897f00f1)
- Class Inheritance

Consider the example where a Chihuahua class needs to be created, inheriting from the Dog class. To achieve this, simply write "class Chihuahua(Dog):" and include "pass" for now, which defines the new class. An instance of a Chihuahua can then be created, inheriting all the methods and attributes of the parent Dog class.

In this example, overwrite the dog class's "speak" method with a more appropriate "yap, yap, yap" method for chihuahuas. You can also add new methods to the child class, like a "wag tail" method, which the chihuahua can use. This is useful when an existing class is used but needs a few changes or additions to it.

<i>Extending Built-in Classes</i>

In Python, extending built-in classes like lists is possible. For instance, creating a new list is achieved by instantiating it as "list". Despite its appearance as a function, "list" is, in fact, a class.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/f678c73a-f487-482e-bcb4-4cc12f82b5bf)
- Extending built-in classes

Let's say you need a list that only accepts unique items, akin to a set. You can achieve this by creating a custom class called "UniqueList" that extends the functionality of the built-in list class. To start, you'll override the append method to ensure uniqueness.

In this custom append method, you'll first check if the item being appended is already in the list. If it is, the method simply returns without adding it again. However, you need to be careful not to call the append method from within the class itself using "self.append," as it could cause infinite recursion. Instead, you'll utilize the "super" function to access the append method of the parent list class.

To test this new class, create an instance of "UniqueList" and append some items to it. Upon printing the list, you'll notice that it only retains unique elements.

Another scenario where "super" comes in handy is in the constructor. If you want to add new attributes to your child class instance without overriding the parent class's constructor entirely, you can do so by calling "super" to invoke the parent constructor first before adding your new attributes.

Although class inheritance might seem complex initially, it's a sophisticated tool for addressing challenging programming tasks. And the best part? Understanding inheritance doesn't require a law degree!

### Handling Errors and Exceptions
----------------------------------

In our Python journey, we've faced various challenges. One familiar hiccup is the zero division error, triggered when attempting to divide by zero.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/8a676b1a-d0ee-48c5-8e81-f9a21211bc95)
- Errors and exceptions

When dealing with issues in Python, they're sometimes labeled as errors or exceptions interchangeably. Although the official Python documentation distinguishes them based on their runtime determination and retriability, there are many exceptions to this rule. In essence, errors and exceptions function similarly. They all stem from the base exception class in Python.

For example, the division by zero error is categorized as an arithmetic error, which is a type of exception that extends the base exception class. This class offers valuable properties for handling exceptions, such as halting code execution and providing insights into why and how the execution stopped.

Consider the zero division error. It reveals the file and specific line where the error occurred. When encapsulated within a function like "causeError" and called, the stack trace becomes more detailed, showing both the original function call location and the point within that function where the error occurred.

This comprehensive trace of function calls is known as a stack trace, which aids in debugging by offering a trail through nested operations. By creating functions like "callCauseError" that return and invoke "causeError," we can extend the stack trace even further. In complex programs spread across multiple files, these stack traces can become extensive, underscoring the importance of interpreting them effectively.

Exceptions can initially appear intimidating, as a minor error within numerous lines of code could lead to a program crash. However, they're merely classes. While this topic will be explored in more depth later, it's important to understand that we can handle exceptions using a try/except statement. This allows us to catch exceptions and access the instance of the raised exception, providing a way to manage errors within our code.

<i>Try/Except</i>

Let's put 1/0 within a try block and add an except block to catch any exception that occurs. We'll use the syntax "except Exception as e" to capture the instance of the exception that was raised, with "e" as our variable representing that instance. Then, we'll print the type of "e" to see the type of exception that occurred.

![image](https://github.com/MihlaliKota/Intro-To-Python/assets/133135575/5cf842f2-63c3-4855-97cf-9a433ccb6062)
- Try/Except 

We've successfully caught a ZeroDivisionError. Once caught, the exception won't interrupt the program's flow. Remember, exceptions are just classes with attributes, and you can create and manipulate them like any other class. While exceptions may seem daunting, handling them properly adds another layer of robustness to your code. Stick with this course to learn how to write code that, if not entirely free of errors, at least manages them gracefully.
