![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/9f7578ff-12a3-4b49-bfca-28c9e668438f)![image](https://github.com/ZaahidAbdurahman/Python/assets/169241347/0c0456b9-5d5c-40ba-b11d-2be0e28cd3c6)# Python

# 1. Introduction to Python

  # How Computers Work

  -  Well, your computer's memory is essentially a grid where it stores files and data.
  
  -  Each file has a file name that is represented in the computer's file directory, like a file icon that you click on.

     [Uploading image.png…]()
     Figure 2: Simple program

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

