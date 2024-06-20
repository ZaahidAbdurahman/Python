# Python

# 1. Python 101 Introduction to Python

  # How Computers Work

  -  Well, your computer's memory is essentially a grid where it stores files and data.
  
  -  Each file has a file name that is represented in the computer's file directory, like a file icon that you click on.

  - Let's consider this scenario: A is a list of numbers, specifically 1, 2, 3, 4, and 5 in Python notation, denoted by square brackets.
  
  - When we assign B to A, B points to the same memory location as A.

  - Knowing what's happening behind the scenes when computers execute a program is essential, especially when working with more complex programs.

  # Zen of Python

  - Python has been in existence for three decades, and its popularity has been continuously increasing over time.

  -  Python is an elegant language that fits into the modern era.
  
  -  For instance, the syntax used to call one function is likely to be similar to that used to call a similar function.

  -  Python's true potential is recognized in situations with many complexities, where the last thing you want is to add more complexities.
  
  -  Python's hidden mission statement called "import this," drives this point home.

     ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/7817bce7-4d57-428c-8d7e-e4498e6e5e2b)

     Figure 11: Starting up Python in a terminal

     To access the Python command prompt, open a terminal and type "Python". Once opened, there are three greater-than symbols indicating that the prompt is ready to accept a line of Python code.

      ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/f02d7542-f41f-4857-8aa0-6e36067c51d9)

      Figure 12: Running the “import this” statement

  # Writing Python Programs

  - We will now write our first Python program, which can be done using any text editor. 
  
  - Visual Studio Code, Sublime, PyCharm, and Notepad++ (for Windows users) are some recommended options.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/9f32c98d-4ab5-4a38-9c40-408b5a159a01)

  Figure 13: Creating and running a simple Python statement, “Hello world!”

  # Jupyter Notebooks

  - In this course, we'll be utilizing Jupyter Notebooks for the majority of our programming work.
  
  - You may be wondering why we're using it and what the benefits are, especially after the installation process.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/8d6b4d0d-3e87-42d6-b031-83586ced648e)
  Figure 16: Jupyter.org site

2.  Getting Started with Python

#  Variables and Types

  - The basic unit of a program is called a variable, which is assigned a value.
  
  - An equal sign is used as an assignment operator.

  - If a variable name begins with a number, it cannot be used, but a variable name can include upper and lower case letters, as well as underscores.
  
  - Variable names traditionally begin with lowercase letters in Python.

  - There are several types of variables in Python, including integers, which are whole numbers; floats, which are decimal numbers; complex numbers, which are used for complex mathematical calculations; and strings, which     are collections of characters.
  
  - Booleans, which are true or false values, are another type of variable in Python.

 #  Data Structures

 - In Python, data structures allow for the storage of a list of values in a single variable.
 
 - The first data structure we learn about is a list, which can contain any data type, including a list within a list.

#  Operators

- Operators are instructions that perform operations on variables and values in Python.

- They are used to manipulate and perform actions on data.

- The most familiar type of operator is the arithmetic operator, which is used for mathematical calculations.

- Addition is one example of an arithmetic operator, where adding one and one gives you the result of two.

- Python provides several other arithmetic operators, such as the multiplication operator represented by an asterisk, which multiplies numbers together.

- Division can be performed using the forward slash operator, and it returns a floating-point value, even if the result is a whole number.

- Strings can also be manipulated using operators.

- The addition operator can concatenate or combine two strings together, while the multiplication operator can repeat a string a certain number of times.

- Logical operators, such as "and," "or," and "not," operate on Boolean values.

- The "and" operator returns true only if both operands are true, while the "or" operator returns true if at least one operand is true.

- The "not" operator negates the Boolean value it operates on.

# Control Flow

- The if statement is one of the three main types of control flow in programming, and it allows you to execute a block of code only if a certain condition is met.

- In Python, you use the if statement like this: "a = True, if a: print It is true." If the condition is true, the indented code under the if statement will be executed.

# Functions

- A function is like a machine that takes inputs and produces outputs, just like a toaster that takes in bread and produces toast.

- Even if the input is not bread, the toaster can still apply its toasting function.

- In Python, functions can be defined using the "def" keyword followed by the function name and arguments in parentheses.

# Classes and Objects

-  As a classic example to demonstrate classes in programming, we can create a class called Dog, as it has multiple functions and attributes, such as legs, a name, and bark.

-  When we define a class, we use an uppercase letter for the class name, and we start defining all the functions and attributes inside the class definition.

# 3. Basic Data Types

-  Let's revisit ints and floats, which are two fundamental number types in Python, and take a closer look at how they interact, how to convert between them, and some common pitfalls to be aware of. 

-  In our previous example, we saw how division with ints returns a float, such as 20 divided by 4 giving us 5.0.

-  Python automatically returns a float to accommodate non-whole numbers.

-  Adding a float to an int or multiplying or using exponents with both also returns a float.

#  Alternative Number Types

-  To start, I want to show you some cool things you can do with the int class in Python.

- If you pass a number as a string, the int class will convert it to an integer.

- For example, "100" becomes the integer 100. But what's really neat is that if you pass a second argument as a number, it will convert the first argument from that base to base 10.

- For instance, "100" in base 2 is equal to 4 in base 10.

- Moving on, Python has another number class called decimal that addresses some of the issues we saw with floats in the previous video.

- Floats are great, but they have floating point errors that can be problematic in certain situations, such as when dealing with money.

- With the decimal class, you can instantiate a decimal object with a number value.

- For instance, decimal 1 divided by decimal 3 returns 0.3333 with four decimal places.

# Booleans

-  Booleans and it may have seemed like there wasn't much to cover.

-  True and false, right? But there are actually some tricky aspects we need to go over, especially since we use them a lot as programmers.

-  First, let's talk about casting. Python easily casts integers to booleans - 1 is true and 0 is false. In fact, anything except 0 is true. So even -1 and imaginary 1 are true, but float 0 and imaginary 0 are false.

- What about strings? Boolean true is true, of course, and anything other than an empty string is also true.

- So even the string "false" is true.

- The only false string is an empty one, but be careful not to accidentally have a space in there.

- We can also cast data structures to booleans.

- An empty list or dictionary is false, but anything inside is true.

- When Python returns a non-value from a function, it is cast to false.

# Strings

-  Python involves a lot of work with strings, whether you're parsing them to extract data or constructing them to present information to the user.

-  Luckily, Python has numerous tools to analyze and construct strings, and one of the most useful is slicing.

-  Slicing refers to taking a portion of a string and returning it.

-  Python has a few ways to create strings, including string concatenation and f-strings.

-  F-strings allow us to insert variables or expressions inside curly braces in a string.

-  We can also do rounding and number formatting with f-strings.

-  Lastly, Python has a handy feature for creating multi-line strings by using triple quotes.

-  If we need to include literal triple quotes in the string, we can escape them with a backslash.

# Bytes

- Python byte object. It's not something you'll work with every day, but it's used behind the scenes in programs.

- It's data that's passed around but rarely modified directly.

- When computers store information, it's done as ones and zeros. 

- When Python loads that data, it knows what type it is - string, int, class, etc. 

- But sometimes all you want is raw data, like a random sequence of ones and zeros. That's where the bytes object comes in.

- To create a bytes object with actual data in it, like an emoji, you need to tell Python the type, like utf-8.

- Once it knows the format, it can represent the data correctly.

- You can also use the decode function to turn a bytes object back into a string.

# 4. Basic Data Structure 

# Lists

- We have covered strings in Python, which are similar to lists and use the same slicing syntax.

- Slicing can be used to extract a range of values from a list or string, and you can also add a third value to control the step size.

- Range function can be used to generate longer lists, which can also be sliced.

- Negative values can be used to step backward through the list.

- To add an item to the end of a list, we can use the append() method.

- For example, if we have a list myList with the values 1, 2, 3, 4, we can append the value 5 to it by typing myList.append(5) and then printing myList.

- There are two ways to remove items from a list.

- The first method is called remove(), which removes an item based on its value, not its index.

- For instance, if we want to remove the value 5 from myList, we can type myList.remove(5) and then print myList.

- However, if we try to remove a value that isn't in the list, we will get an error.

# Tuples and Sets

- Let's take a closer look at two data structures that we briefly covered before tuples and sets.

- First, let's talk about sets.

- A set is defined using curly brackets, like this: {'a', 'b', 'c'}, mySet.

- You can also define a set by passing any iterable object in the constructor of the set class, like this: mySet = set(('a', 'b', 'c')).

- One common use of sets in programming is to remove duplicates from a list, since sets only contain unique values.

- To demonstrate, let's create a list with some duplicate values and de-duplicate it by converting it to a set and back again: myList = ['b', 'c', 'c'] mySet = list(set(myList)).

- Sets are not ordered lists but rather collections of elements, so their order is randomized.

- You can't access elements in a set using an index or slicing syntax.

- However, you can add elements to a set using the add() function and remove elements using the discard() function.

- One common use case for tuples is when you want to return multiple values from a function.

# Dictionaries

- In Python, you will commonly work with two main data structures: lists and dictionaries.

- Combining lists and dictionaries can solve nearly 95% of your data structure needs.

- Let's take a look at some examples using a dictionary of animals. 

- You may notice a comma at the end of the last key-value pair, which is called a trailing comma.

- While it's not technically necessary, it's good practice and convention to include it. 

- To access a specific key-value pair in the dictionary, you can simply type the name of the dictionary followed by the key in square brackets.

- The resulting object for .keys() is a dict_keys object, which is immutable.

- To change this object, you need to convert it to a list first.

- If you try to access a key that doesn't exist, you'll get an error.

- To handle this, you can use the handy get() function, which takes a key as its first argument and an optional default value as its second argument.

# List Comprehensions

- List comprehension is a special feature in Python that sets it apart from other programming languages.

- The term "comprehension" here has nothing to do with understanding, but rather with the comprehensive listing of things.

- To demonstrate this, let's take a list of numbers like one, two, three, four, and five.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/1546d085-280b-4887-b83a-daf83d8acda2)

   Figure 53: List comprehensions

- Using a list comprehension, we can multiply each item in the list by two, like this: two times item for item in my list.

- A list comprehension allows you to create a for loop in one line while also returning a copy of the list you're iterating over.

- It also enables you to filter or apply functions to every item in a list.

- By using the "split" function and creating our own "cleanWord" function, we can manipulate strings to fit our needs and create more useful data structures.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/5e263b1f-5b89-4cb8-9135-70da9a7b60e6)

  Figure 56: Nested list comprehensions

# Dictionaries and Comprehensions

- In Python, you can use dictionary comprehensions to create a new dictionary from an iterable structure, much like how list comprehensions create a new list.

- To demonstrate, let's start with a list of tuples as our key-value pairs.

- We can use the syntax "animals = {item[0]: item[1] for item in animalList}" to create a dictionary from this list.

- Notice that we use a colon to separate the key and value, and surround the comprehension with curly braces.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/f0282902-05fb-4295-bc16-d038ee33390a)

   Figure 54: Dictionaries and comprehensions

- There is actually a more concise way to write this dictionary comprehension using tuple unpacking.

- Instead of using "item[0]: item[1]", we can use "key: value" and replace "item" with "(key, value)".

# 5. Basic Control Flow

# If and Else

-  This statement evaluates a series of values and runs the code instructions that correspond to the first true value found.

-  If you are unfamiliar with the switch statement, don't worry because Python is superior to other programming languages anyway.

- One issue with if else statements is that they can often drag on for too many lines.

- Sometimes, you want to evaluate something in a one-liner. This is where the ternary operator comes in.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/02241e71-452a-4ea5-9122-b45ed3c51c82)

  Figure 62: If statements with “FizzBuzz”

  # While

- It's important to be careful when running code that has a while loop, because it can run forever.

- If you want to exit a loop early, you can use the break statement, which will exit the loop and move on to the next line of code outside of the loop.

- On the other hand, if you want to skip over certain lines within a loop, you can use the continue statement, which will skip over any lines that come after it and jump back to the top of the loop to start the next 
  iteration.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/74c4b307-5a0a-4604-9a35-174585c8dd02)

   Figure 63: While

  # For
-  You will enjoy using the for loop syntax in Python. It's super intuitive, and it reads like plain English.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/23c44f24-b0d9-4506-90b3-6dedcc7ca674)
 
  Figure 64: For

- With the for loop, you can declare a new variable, like "item," to hold the value of each element in your list as you iterate through it.

- It's short and sweet, and it's actually the most common loop you'll use when coding in Python.

# Python 102: Python Fundamentals 1. Basic Functions

# Anatomy of a Function

# Functions

- Functions are composed of a name and parameters, which are denoted by the def statement. So, to create a function, let's call it performOperation and include num1, num2, and operation as parameters. 

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/78b6d7ee-c5ed-465c-bcc2-7820a14174c3)

  Figure 1: Functions

# Named Parameters

- If we remove this part, we'll end up with a total of five. However, we can also assign our own value.

- If our function has a lot of these optional keyword parameters, it can become confusing to determine their order.

- Therefore, it may be more clear and easier to read to explicitly state "operation equals multiply".

# *args

- There is a rule when using keyword arguments in Python i.e. they must come after the positional arguments.

- The order of the first two arguments is important and cannot be changed.

- However, after these mandatory arguments, the keyword arguments can be in any order.

# Variables and Scope

# Function Scope

- In our earlier section, *args and **kwargs were used to print out the arguments passed into a function.

- This allowed us to see a tuple and dictionary of the passed arguments.

- However, there's another method that allows us to access all the variables within a Python function without any asterisks.

# locals()

- Let's modify the original function definition to execute operation num1, num2, and operation, which defaults to addition.

- Afterwards, use the locals function in Python to print the output.

![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/7c3e8dce-6171-44db-b82f-f32c8d0bf6a2)

Figure 6: locals()

# globals()

- Running the code would result in so many items, some of which are Python's pre-built variables that will come in handy when working with classes and packages.

- However, Jupyter Notebooks also employ various variables to manage its data.

# Global and Local Scope

- The plan is to create two functions: function one with variables A and B, and function two with variables C and B.

- Both functions will print out their local variables.

- We will call function one with arguments 1 and 2, and function two with arguments 3 and 4.

# Functions As Variables

# Variables as Functions

- Variables and functions both have names and data associated with them.

- However, for functions, this data includes information about required parameters and the lines of instruction to be executed.

-   In Python, a function is represented as an object.

# Viewing Function Data With  __code__

- The "code" attribute of Python function objects can be used to confirm that functions are just variables in Python.

# Text Processing in Python

- Here are familiar text and function names to illustrate a point.

- There are two text processing operations, and a function that can make the text lowercase, remove punctuation, new lines, and words that are three characters or less.

# Lambda Functions

- These are a way to represent a function without giving it a variable name.

- Just like how an expression like 5 or 2 + 3 can be written without assigning it to a variable, a small function can be defined using the lambda keyword.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/6044fd33-ed12-4937-bb3c-fec97c0adbb0)

  Figure 12: Lambda functions

# 2. Classes and Objects Fundamentals

# Instance Attributes

- The topic of classes can be overwhelming and hard to understand.

- We may not be sure what they are or how to determine which class a member belongs to.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/503bfbe8-e99f-431d-8c80-1ed6a894c7c7)

  Figure 15: Instance attributes

# Static Attributes

- For now, change the way legs attribute are handled in the class.

- Instead of keeping it in the constructor, define it as a static variable outside of the constructor. 

- It is important to note that static variables can still be changed, so to prevent this, programmers conventionally add an underscore before the variable name.

# Instance and Static Methods

One of your favorite things to do in Python may be string parsing. To demonstrate, create a class called Word Set that contains a set of words. 

- Start with an empty set and add to it by passing in big blocks of text, punctuation and all. 

- Add text using the method add text, which first calls the method clean text to remove the punctuation and make everything lowercase. 

- Then use the split function to turn the sentence into a list of words, which can be added to the set. 

- Finally, print the set of words. 

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/8a9abc10-b8e2-4d72-903a-5c72c780d67e)

  Figure 17: Static instances and methods

- The clean text method is a static method because it does not belong to any particular class instance, whereas add text is an instance method that belongs to a particular instance of the class.

# Inheritance

# Class Inheritance

- In the world of computer science and Python programming, it is possible for one class to inherit all the methods and attributes of another class.

- The original class is referred to as the parent class, while the new class that extends it is known as the child class.

# Extending Built-in Classes

- We can also apply class extensions in Python's built-in classes.

- In Python, creating a new list can be done by instantiating it as "list". Although it appears as a function, "list" is actually a class.
  
 ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/d63a5c1a-4244-4ece-9db8-7a6cf3d29715)

  Figure 20: Extending built-in classes

- Suppose you want a list that ensures all appended items are unique, like a set.

- Create your own unique list class by extending the list class.

- The unique list class inherits from the list class and we will override the append function.

# 3. Error Handling Fundamentals

![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/0081e220-9fb9-4a08-a6e6-4ec793956d6a)

Figure 23: Errors and exceptions

- When working with Python, notice that sometimes these problems are referred to as errors, while other times are called exceptions.

- If official Python documentation is consulted, you will find that exceptions are determined during runtime and can be retried, whereas errors cannot be retried.

# Try/Except 

- Let's give it a try. Add 1/0 in here and then except. Going to except exception as e, so e is going to be our variable.

- Actually, that instance of the exception that was raised, print type e, and there you go.

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/cc996beb-45d3-467d-b420-9bd912812e91)

  Figure 24: Try/Except 

# Managing and Handling Exceptions

- Exceptions are not to be feared but they do need to be reigned in. We saw a little bit about how to do this previously with the Try / Except statement.

- Here we are catching this exception and then just returning it. 

  ![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/20c2e63c-fd0f-4fa6-88c3-d38b3667ca7c)

  Figure 25: Try/Except

  - We do not get a stack trace or anything, but do see that this zero division error instance is returned.
 
  # Finally

- Another useful tool is the finally statement. If you take the Try / Except block and add a finally to it, this will always execute and gets printed out.

- Finally statements can be useful because they will always execute no matter what happens inside this try block.

- You do not even need any except statements! This error is thrown, but still printed out.

# Catching Exceptions by Type

- Notice that you are always catching this exception class.

- You could add another except statement above this and chain these together just fine. 

- We are going to catch the zero division specifically.

- There was a zero division error, and now that prints out.

![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/d01299ee-b00c-4a80-936d-531ff75a6524)

Figure 27: Catching exceptions by type

# Custom Decorators

- Custom decorators can also be used to do this.

- We saw decorators previously with the static method decorator but now we are going to write our own.

- Grab all these exception handlings that were done and make a new function called handleException.

- We are going to pass as an argument, a function, and then define an inner function called wrapper.

# Raising Exceptions

- Let's talk about raising exceptions. Use the handle exception decorator. Make a  function called raiseError raise Exception.

- This raise statement raises or throws this new exception that was created when it is reached.

# Working With Custom Exceptions

- Custom exceptions is an easy one. In fact, you already know how to do this, class CustomException extends Exception:pass. Now you have written a custom exception.

- There are, however, a few more things to cover.

- The pass statement is used because we literally do not need to define anything for our new CustomException class.

- It inherits the constructor of the Exception class that it is extending. 

# Adding Attributes

- Let's write an HTTP exception with a static status code and a message attribute, and then some information about how to format the string that it passes to the parent exception.

- Here is the HttpException. It is going to extend the Exception and we are going to give it a status code.

- Make that None for now — a special None value, and a message that is also None. 















