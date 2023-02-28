# Python-Tutorial-for-Beginners---Learn-Python-in-5-Hours


https://www.youtube.com/watch?v=t8pPdKYpowI

https://gitlab.com/RodrigoMvs1231/cicd/-/tree/main 

Web Development 
Data Science 
Machine Learning 
Automation 

Course Overview
Intro to Python and Local Setup

Basic Building Blocks of Programming
work with strings, numbers, booleans 
work with lists, sets, dictionaries 
variables and functions 
accepting user input 
input validation with conditionals (if / else) 
error handling with try / except 
looping: for loop, while loop

Modules
write own modules 
use build-in python modules
work with datetime module

Project: Countdown App
enter your goal with a deadline separated by colon…
Dear user ! Time remaining for your goal: Learn python is 132 days …

Package , PYPI and pip

Project: Automation with Python

OOP - Classes and Objects 

Project: API Request to GitLab


Introduction to Python
Python is a programming language 
As Java, JavaScript 

Easy to learn / simple syntax / ease to set up
Large ecosystem / many libraries / large community

Flexible / you are not limited to language specifics  

What is Python used for ? 
Web Development ( www ) 
   Data Science 
   Machine Learning 
   Artificial Intelligence 
                                   Pandas / Numpy / PyTorch / TensorFlow / Keras / Python 
Web Scraping   

Automation 
Automate DevOps tasks 
CI/CD pipeline 
AWS
Google Cloud 

automated general tasks ( Working with Excel Sheets )

Development 
Mobile 
Game 
Desktop 

Installation and Local Setup 
Welcome to Python.org
Terminal MacOS
[/W] $ python3 - - version 
Python 3.9.1
[/w]  $ python - - version 
Python 2.7.10
[/w]  $ 

Setup PYCharm IDE 
https://www.jetbrains.com/pycharm/
Download Pycharm 



New Project 
Location: … / my-python-project

Our Source Code 
Python Interpreter 
Knows how to execute Python code 
Translate our program into machine readable binary code 
 Create 
Our First Program

Python IDE vs simple file editor 

main.py 



print (“100 is a great number”) => string

[/W] $ touch test.py
[/W] $ vim test.py 
[/W] $ python3 test.py
100 is a great number
[/W] $ 

String and Numbers 
print (3.5) => float 
print ( 3 ) => Integer 

Working with numbers  
Arithmetic Operators 

print(20 * 24 * 60) // 28800
to be a programmer, you do not need to be a math genius for 
Web Development 
Automation 

String Concatenation 
print( “20 days are ” +str(50) + “ minutes ”)
print( f”20 days are {50} minutes”) 

print( f”20 days are {50} minutes”) 
[/W] $ touch test.py
[/W] $ vim test.py 
[/W] $ python3 test.py
100 is a great number
[/W] $ vim test.py 
print(“100 is a great number”) // delete 
print( f”20 days are {50} minutes”) 

[/W] $ touch test.py
[/W] $ vim test.py 
[/W] $ python3 test.py
100 is a great number
[/W] $ vim test.py 
[/W] $ python 3 test.py
print( f”20 days are {50} minutes”) 



[/W] $ touch test.py
[/W] $ vim test.py 
[/W] $ python3 test.py
100 is a great number
[/W] $ vim test.py 
[/W] $ python 3 test.py
print( f”20 days are {50} minutes”) 
[/W] $ python test.py
   File “test.py”, line 1 
      print ( f “20 days are {50} minutes” )
SyntaxError: invalid syntax 
[/W] $ python - - version
Python 2.7.10.
[/W] $  

print( f”20 days are {20 * 24 * 60 } minutes”) // 20 days are 28800 minutes

Variables 

  // print( f”20 days are {20 * 24 * 60 } minutes” 
print( f”35 days are {35 * 24 * 60 } minutes” // 35 days are 50400 minutes
print( f”50 days are {50 * 24 * 60 } minutes” // 50 days are 72000 minutes
print( f”20 days are {110 * 24 * 60 } minutes” // 110 days are 158400 minutes

Variables 
caculation_to_seconds = 24 * 60 * 60 

print( f”35 days are {35 * 24 * 60 * 60 } seconds” // 35 days are 50400 minutes
print( f”50 days are {50 * 24 * 60 * 60 } seconds” // 50 days are 72000 minutes
print( f”20 days are {110 * 24 * 60 * 60 } seconds” // 110 days are 158400 minutes 

Python is dynamically typed vs Static Typing: 
Naming Convention 
  Naming convention is a convention (generally agreed scheme ) for naming things.

Reserved Keywords in Python

cauculation_to_units = 24 * 60 * 60
named_of_unit = “seconds”

print( f”20 days are {20 * cauculation_to_units } seconds” ) // 20 days are 1728000
print( f”35 days are {35 * cauculation_to_units } seconds” ) // 35 days are 3024000
print( f”50 days are {50 * cauculation_to_units } seconds” ) // 50 days are 4320000
print( f”110 days are {110 * cauculation_to_units } seconds” )  // 110 days are 9504000




cauculation_to_units = 24 * 60 * 60
named_of_unit = “seconds”

print( f”20 days are {20 * cauculation_to_units } {name_of_unit}” )  // 20 days are 1728000
print( f”35 days are {35 * cauculation_to_units } {name_of_unit}” ) // 35 days are 3024000
print( f”50 days are {50 * cauculation_to_units } {name_of_unit}” ) // 50 days are 4320000
print( f”110 days are {110 * cauculation_to_units } {name_of_unit}” // 110 days are 9504000

cauculation_to_units = 24 
named_of_unit = “hours”

print( f”20 days are {20 * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours
print( f”35 days are {35 * cauculation_to_units } {name_of_unit}” ) // 35 days are 840 hours
print( f”50 days are {50 * cauculation_to_units } {name_of_unit}” ) // 50 days are 1200 hours
print( f”110 days are {110 * cauculation_to_units } {name_of_unit}” // 110 days are 2640 hours

Use descriptive variable names!

Functions 

To avoid repeating the same logic 
A function is defined using the def keyword 
Block of code white only runs when it is called

cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (): 

print( f”20 days are {20 * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours
print( f”35 days are {35 * cauculation_to_units } {name_of_unit}” ) // 35 days are 840 hours
print( f”50 days are {50 * cauculation_to_units } {name_of_unit}” ) // 50 days are 1200 hours
print( f”110 days are {110 * cauculation_to_units } {name_of_unit}” // 110 days are 2640 hours


cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (): 

print( f”20 days are {20 * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours
print (“All good!”)

days_to_units () 

All good!
Function Parameters 
 


cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days): 

print( f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours
print (“All good!”)

days_to_units (35) 

All good!

35 days are 840 hours 
All good !

print( f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours

days_of_units (20)
days_to_units (35) 
days_to_units (50) 
days_to_units (110)

20 days are 480 hours
35 days are 840 hours 
50 days are 1200 hours 
110 days are 2640 hours 

less code
reduced code duplication 
more descriptive 


days_of_units (20)
days_to_units (35) 
days_to_units (50) 
days_to_units (110)


cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days, custom message): 

print( f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours
print ( custom message )

days_to_units ( 20, “Awesome!” )
days_to_units ( 35, “Looks good!” )

20 days are 480 hours
Awesome! 
35 days are 840 hours 
Looks good! 

Scope // A variable is only available from inside the region it is created 
-Global Scope = variables available from within any scope  


cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days, custom message): 

print( f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}” )  // 20 days are 480 hours
Print ( custom message )

def scope_check (num_of_days): 
my_var = “variable inside function”
print (name_of_unit)
print (num_of_days) 
print (my_var) 

scope_check (20)

// 20 
// variable inside function

User Input 
-To ask the user for an input 
-Python stops executing when it comes to the input () 

Built-In Function
Are provided by python language itself 

cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days): 
      print( f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}” ) 

user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
print (user_input) 
Waiting for user input …

//  Expression 
an instruction that combine values and operators and always evaluates down to a single value

Hey user, enter a number of days and I will convert it to hours ! 
30 
20


Function with Return Values

1 - Function executed 
cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days): 
      return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}” 
2 - Return value is assigned to variable 
my_var = days to units (20) // Return Values - A function can return data as a result
print ( my_var ) 3 - Variable value is print to standard output  

20 days are 840 hours 


Back to our User Input Example 

cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days): 
      return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”


user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
// input () always returns a string
user_input_number = int(user_input)
// Casting - +str(50)+ 
// int() - build-in Python function 
// converts the specified value into an integer number   

calculated value = days_to_units (user_input)
print ( calculated_value )  
10 days are 240 hours 


[/W] $ touch test.py
[/W] $ vim test.py 
[/W] $ python3 test.py
100 is a great number
[/W] $ vim test.py 
[/W] $ python 3 test.py
print( f”20 days are {50} minutes”) 
[/W] $ python test.py
   File “test.py”, line 1 
      print ( f “20 days are {50} minutes” )
SyntaxError: invalid syntax 
[/W] $ python - - version
Python 2.7.10.
[/W] $  clear 

[/W] $  vim test.py

INSERT
wq 
test.py 16L … 
[/W] $ python3 test.py

cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days): 
      return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”


user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
// input () always returns a string
user_input_number = int(user_input)
// Casting - +str(50)+ 
// int() - build-in Python function 
// converts the specified value into an integer number   

calculated value = days_to_units (user_input)
print ( calculated_value )  

[/W] $  vim test.py

INSERT
wq 
test.py 16L … 
[/W] $ python3 test.py
Hey user, enter a number of days and I will convert it to hours !
25
25 days are 600 hours 
[/W] $ 

Conditionals (if/else) and Boolean Data Type

Validate user input 
We want to avoid or handle values: 
witch do not make sense
that could crash our program
could even be a security risk 


cauculation_to_units = 24 
named_of_unit = “hours”

def days_to_units (num_of_days): // if / else statement 
       condition_check  =  num_of_days > 0 
    print ( type (condition_check))
       if num_of_days  > 0:  
// Condition - If condition is correct: then do this otherwise do this 
// Condition - Can be TRUE or FALSE 
// Boolean Data Type - Can only have 2 values: TRUE or FALSE 
                 return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”

elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
// Program Flow / Value Positive / 1. Is the number higher than 0 ? Yes. 
// Program Flow / Value Negative / 1. Is the number higher than 0 ? No.
// Numbers equal 0 ? No.
// = assigning a value to a variable 
// = = check for equality  
        else: 
       return “you entered a negative number, so no conversion for you!”

// print (type(“this should be a string type”) )


user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
user_input_number = int(user_input)

calculated value = days_to_units (user_input_number)
print ( calculated_value )  
// Return value of inner function is the input value for the outer function 

Hey ! user, enter a numbers of days and I will convert it to hours
10
10 days are 240 hours 

Hey ! user, enter a numbers of days and I will convert it to hours
-10 
None
 
-10 
you entered a negative number, so no conversion for you!

// -10(string data type) 
// -10 (integer data type)
// passes value into function 
// evaluates conditions in if …
// if positive, return calculate string
// if negative, return other string

Hey ! user, enter a numbers of days and I will convert it to hours

10 
True

Hey user, enter a number of days and I will convert it to hours !
-10 
False

23
<class’bool’>
23 days are 552 hours  

<class str>

Hey user, enter a number of days and I will convert it to hours !
10
10 days are 240 hours 

Hey user, enter a number of days and I will convert it to hours !
0
you entered a 0, please enter a valid positive number 

Hey user, enter a number of days and I will convert it to hours !
-10 
you entered a negative value, so no conversion for you !





More User Input Validation 


cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days):
    if num_of_days  > 0: 
       return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”
    elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 

def validate_and_execute
  if user_input.isdigit():
          user_input_number = int (user_input)
          calculated value = days_to_units (user_input_number)
          print ( calculated_value )  
       else:
           print(“your input is not a number. Do not ruin my program”)

user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
validate_and_execute()

Hey user, enter a number of days and I will convert it to hours !
sometext 
ValueError: invalid literal for int() with base 10: ‘sometext’

Hey user, enter a number of days and I will convert it to hours !
user_input_number = int(user_input)
19.99
ValueError: invalid literal for int() with base 10: ‘19.99’ 


Hey user, enter a number of days and I will convert it to hours !
sometext 
your input is not a valid number. Do not ruin my program

20 
20 days are 240 hours 

0 
you entered a 0, please enter a valid positive number 

19.99
your input is not a valid number. Do not ruin my program


Hey user, enter a number of days and I will convert it to hours !
-5 
your input is not a valid number. Do not ruin my program
Hey user, enter a number of days and I will convert it to hours !
10 
10 days are 240 hours

Hey user, enter a number of days and I will convert it to hours !
19.999
your input is not a valid number. Do not ruin my program


Clean Up Our Code

cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days):
     return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”
    elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 

def validate_and_execute
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (user_input)
           if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number)
                print ( calculated_value )  
           elif user_input_number = = 0: 
                 print (“you entered a 0, please enter a valid positive number”) 
 except: ValueError: 
           print(“your input is not a number. Do not ruin my program”)

user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
validate_and_execute()

Nested 
If … Else




Error Handling with try / except 

 cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days):
     return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”
    elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 

def validate_and_execute
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (user_input)
           if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number)
                print ( calculated_value )  
           elif user_input_number = = 0: 
                 print (“you entered a negative number no conversion for you !”) 
 except: ValueError: // “Also called try/catch in other programming language”
           print(“your input is not a valid number. Do not ruin my program”)

user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
validate_and_execute()

Nested 
If … Else

Hey user, enter a number of days and I will convert it to hours !
sometext 
your input is not a number. Do not ruin my program !

Hey user, enter a number of days and I will convert it to hours !
19.99
your input is not a valid number. Do not ruin my program

Hey user, enter a number of days and I will convert it to hours !
20
20 days are 480 hours 

Hey user, enter a number of days and I will convert it to hours !
-10
you entered a negative number no conversion for you !


While Loops 

Looping 
To execute logic multiple times 
Python has 2 loop commands 
Conditions 
Evaluate to true or false
Are use most commonly in “if statement” and “loops”
While Loop
execute a sets of statements as long as a condition is true  

 cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days):
     return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”
    elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 

def validate_and_execute
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (user_input)
           if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number)
                print ( calculated_value )  
           elif user_input_number = = 0: 
                 print (“you entered a negative number no conversion for you !”) 
 except: ValueError: // “Also called try/catch in other programming language”
           print(“your input is not a valid number. Do not ruin my program”)

while True: 
user_input = input ( “Hey ! user, enter a numbers of days and I will convert it to hours/n” ) 
validate_and_execute()

10 
10 days are 240 hours 
Hey user, enter a numbers of days and I will convert it to hours !

-10 
you entered a negative number no conversion for you
Hey ! user, enter a numbers of days and I will convert it to hours

sometext 
your input is not a valid number. Do not ruin my program !
Hey ! user, enter a numbers of days and I will convert it to hours


 cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days):
     return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”
    elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 

def validate_and_execute
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (user_input)
           if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number)
                print ( calculated_value )  
           elif user_input_number = = 0: 
                 print (“you entered a negative number no conversion for you !”) 
 except: ValueError: // “Also called try/catch in other programming language”
           print(“your input is not a valid number. Do not ruin my program”)

user_input = 
while user_input != “exit”: // IDE warnings - help you to avoid mistakes   
user_input = input ( “Hey user, enter a numbers of days and I will convert it to hours !/n” ) 
validate_and_execute()

5. Second Loop: check if “exit” was typed in
6. User is prompted for its input
7. Function is called and input is validated and executed 
8. Loop continues … 

Let user exit the program 

exit
your input is not a valid number. Do not ruin my program !

Hey user, enter a number of days and I will convert it to hours ! 
10 
10 days are 240 hours 

Hey user, enter a number of days and I will convert it to hours ! 
-19 
you entered a negative number no conversion for you !
Hey user, enter a number of days and I will convert it to hours ! 
20
20 days are 480 hours 

Hey user, enter a number of days and I will convert it to hours ! 
40 
40 days are 960 hours 

Hey user, enter a number of days and I will convert it to hours ! 
exit 
your input is not a valid number. Do not ruin my program !


Lists and For Loop 

Hey user, enter a number of days and I will convert it to hours ! 
20
20 days are 480 hours 

Hey user, enter a number of days and I will convert it to hours ! 
40 
40 days are 960 hours

 cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days):
# 
     return f”{num_of_days} days are {num_of_days * cauculation_to_units } {name_of_unit}”
    elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 

def validate_and_execute
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (num_of_days_element)

       # we want to do a conversion only for positive integers 
         # Comments 
#Can be used to explain code 
#  Can be used to prevent execution when testing code ( Python interpreter ignores it )
  if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number)
                print ( calculated_value )  
           elif user_input_number = = 0: 
                print (“you entered a negative number no conversion for you !”) 
 except: ValueError: // “Also called try/catch in other programming language”
           print(“your input is not a valid number. Do not ruin my program !”)



“string exemple”
10        String
19.99   Float 
True     Boolean
False    Boolean 
[10,15,40,100] Integer 

Lists 
To store multiple items in a single variable 



user_input = “”
while user_input != “exit”: // IDE warnings - help you to avoid mistakes   
   user_input = input ( “Hey user, enter a number of days as a comma list and I will convert it to hours !/n” )
list_of_days = user_input.split(“, ”)
print (list_of_days) 
print (set (list_of_days)) 

print (type( list_of_days))
print (type (set(list_of_days))) # Nested Function Execution 

#1. set( list_of_days)
# => Input: the user input array 
# => Output: Returns the converted Set

#2. type ( return_value_of_previous_func) 
# => Input: the converted Set
# => Returns the data type of the Set

#3. print (return_value_of_previous_func) 
# => Input: the data type 
# => Output:Prints the value to console 

  for num_of_days_element in set (user_input.split(“, ”)):  // String “10, 22, 50, 100” - list[10,22,50,100] 
print(type (user_input.split(“, ”))) 
print (user.input.split (“,”))
        validate_and_execute() 
String - split() “10 22 50 100” => [10,22,50,100]


Hey user, enter a number of days and I will convert it to hours ! 
[10.15,40,100]
your input is not a valid number. Do not ruin my program !
Hey user, enter a number of days and I will convert it to hours ! 

[10.15,40,100]
validate_and_execute ( ) 

For loop 
-Is used for iterating over a sequence (like a list)
-So we can execute smth for each item in a list

Hey user, enter a number of days and I will convert it to hours ! 
10,30,20

Hey user, enter a number of days and I will convert it to hours ! 
10,20,40,55
10 days are 240 hours 
20 days are 480 hours 
40 days are 960 hours 
55 days are 1320 hours 
Hey user, enter a number of days and I will convert it to hours ! 
10,20,”text” , 19.99
10 days are 240
20 days are 480 hours 
your input is not a valid number. Do not ruin my program !
your input is not a valid number. Do not ruin my program ! 
Hey user, enter a number of days and I will convert it to hours ! 
20, true, -100
20 days are 480 hours 
your input is not a valid number. Do not ruin my program !
you entered a negative number, no conversion for you !
Hey user, enter a number of days and I will convert it to hours ! 
23, 40, 50 
23 days are 552 hours 
40 days are 960 hours 
50 days are 1200 hours 
Hey user, enter a number of days and I will convert it to hours ! 
exit 
your input is not a valid number. Do not ruin my program !
Hey user, enter a number of days and I will convert it to hours ! 

20, test, 56
<class’list’>
[‘20’, ‘text’, ‘56’]
20 days are 480 hours 
your input is not a valid number. Do not ruin my program !
56 days are 1344 hours 
Hey user, enter a number of days as a comma list and I will convert it to hours !

3, 6, test
<class ‘list’>
[‘3’, ‘6’, ‘test’]
3 days are 72 hours 
6 days are 144 hours 
your input is not a valid number. Do not ruin my program !
Hey user, enter a number of days as a comma list and I will convert it to hours !

Basic List Operations 
Create a list 
Add an item to the list 
Remove an item from the list 
Change items in the list
Access items of the list 





lists.py 


my_list = [“January”, “February”, “March”]  
my_list [] // List Items are indexed - First items has index 0 
print (my_list [2]) 
my_list.append (“April”) 
print ( my_list [3])  
// print ( my_list [4]) Error   
March 
[‘January’, 'February', ‘March’, ‘April’]

March
April  

March 

https://www.jetbrains.com/ 
https://www.jetbrains.com/pycharm/?_gl=1*1a8w09t*_up*MQ..&gclid=CjwKCAiA0JKfBhBIEiwAPhZXD_YPITw6IQ_9pT7Jmw4FMu7eANM4izv4z_hfa2wT1ioF6FdpjvXa2BoC2zMQAvD_BwE
https://www.jetbrains.com/idea/ 

Sets 

Hey user, enter a number of days as a comma list and I will convert it to hours !
20, 50, 20
20 days are 480 hours 
50 days are 1200 hours 
20 days are 480 hours 
Hey user, enter a number of days as a comma list and I will convert it to hours !

-another build-in data type of python 
-as with Lists, used to store multiple items of data
-does NOT allow duplicate value 

 Hey user, enter a number of days as a comma separated  list and I will convert it to hours !
10, 45, 30, 10
[‘10’,’45’,’30’,’10’]
{‘45’, ‘30’, ‘10’}
<class ‘list’>
<class ‘set’>
45 days are 1080 hours 
30 days are 720 hours 
10 days are 240 hours 
 Hey user, enter a number of days as a comma separated  list and I will convert it to hours !


Basic Set Operations and Syntax 


sets.py 



my_set = {“January”, “February”, “March”}

# Basic set operations 
Create a set
Access items only via loop !
Add an item to the set 
Remove an item from the set

# Unordered and unchangeable 
Items is a set that does not have a defined order !

my_set = {“January”, “February”, “March”}
for element in my_set:
             print (element)
March
February 
January 

my_set.add(”April”)
             print(my_set)
January
March 
February 
{‘January’, ‘April’, ‘March’, ‘February’}


my_set = {“January”, “February”, “March”}
for element in my_set:
             print (element)

my_set.add(”April”)
             print(my_set)
my_set.remove(“January”)
             print(my_set)



January
March 
February 
{‘January’, ‘April’, ‘March’, ‘February’}
{‘April’, ‘March’, ‘February’}



my_set = {“January”, “February”, “March”}
for element in my_set:
             print (element)

my_set.add(”April”)
             print(my_set)
my_set.remove(“January”)
             print(my_set)

my_list = [“January”, “February”, “March”]
my_list.remove (“January”)
             print(my_list) 

{‘January’, ‘April’, ‘March’, ‘February’}
{‘April’, ‘March’, ‘February’}
['February', ‘March’]


Build-In Functions 

cauculation_to_units = 24 
named_of_unit = “hours”


def days_to_units (num_of_days, conversion_unit):
     if conversion_unit == “hours”: 
     return f”{num_of_days} days are {num_of_days * 24 } hours”
elif conversion_unit == “minutes”: 
     return f”{num_of_days} days are {num_of_days * 24 * 60 } hours”
else 
     return “unsupported unit”
     elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 


def validate_and_execute
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (days_and_unit_dictionary [“days”])

# Accessing Items in a Dictionary
# Items can be accessed by its key name 
# You can use square brackets or () get method 
# Your_dict [“days”] or your_dict.get (“days”)

           if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number, days_end_unit_dictionary [“unit”] )
                print ( calculated_value )  
           elif user_input_number = = 0: 
                 print (“you entered a negative number no conversion for you !”) 
 except: ValueError: // “Also called try/catch in other programming language”
           print(“your input is not a valid number. Do not ruin my program”)

user_input = “”
while user_input != “exit”: // IDE warnings - help you to avoid mistakes   
   user_input = input ( “Hey user, enter a number of days as a comma list and I will convert it to hours !/n” )
list_of_days = user_input.split(“, ”)
for num_of_days_element in set(list_of_days): 
        validate_and_execute()

print (list_of_days) 
print (set (list_of_days)) 
print (type( list_of_days))
print (type (set(list_of_days))) # Nested Function Execution 

#Standalone Built-In Functions 
# print () => Print to the standard output device 
# input() => aks user for input 
# set () => Return a new set
# int () => Converts value into an integer number 

print (“some text”) 
input (“enter value”)
set ([1,3,4])
int (‘20“)

“2, 3”.split ()
[1, 3, 4 ].county () 

# Build-In Functions on Data Type 
# each data type has it own build - in - functions 
# which are useful/ makes sense only for this specific data type 


Dictionary Data Type 

my_dictionary = {
       “days”: 20,
       “unit”: “hours”, 
} 


Allow user to input: 
number of days, e.g.50
unit to convert to, e.g.hours 

user_input = “”
while user_input != “exit”: // IDE warnings - help you to avoid mistakes   
   user_input = input ( “Hey user, enter a number of days and conversion unit! /n” )
   days_and_unit = user_input.split(“:”)
   print (days_and_unit) 
   days_and_unit_dictionary = {“days”: days_and_unit [0], “unit”: days_and_unit[1] }
   print ( days_and_unit_dictionary )  
   print (type(days_and_unit_dictionary)) 
   validate_and_execute

message = “enter some value” 
days = 20
price = 9.99 
valid_number = True 
exit_input = False 
list_of_days = [20, 40, 20, 100]
list_of_months = [“January”, “February”, “June”]
set_of_days = {20, 45, 100}
days_and_unit = {“days”: 10, “unit”: “hours”}  



my_list = [“20”, “30”, “100”]
print ( my_list [2] )

my_dictionary = {“days”: 20, “unit”: “hours”, “message”: “all good” }
print (my_dictionary [“message”])


# Accessing Items in a List
# Items can be accessed by index 
#  The first item has index 0 

   
#Dictionary 
#Are used to store values in key:value pairs 

Hey user, enter a number of days and a conversion unit!
45:hours 

Hey user, enter a number of days and a conversion unit!
20:hours 
[‘20’, ‘hours’] 

Hey user, enter a number of days and a conversion unit!
20:hours
[‘20’, ‘hours’]
{‘days’: ‘20’, ‘unit:’ ‘hours’}
Hey user, enter a number of days and a conversion unit!
40 minutes 
[‘40’, ‘minutes’]
{‘days’: ‘40’, ‘unit’: ‘minutes’ }
Hey user, enter a number of days and a conversion unit

100 
all good

Hey user, enter a number of days and a conversion unit
20:minutes 
[‘20’: ‘minutes’]
{‘days’: ‘20’, ‘unit’: ‘minutes’}
20 days are 28800 minutes

Hey user, enter a number of days and a conversion unit
90:hours
{‘days’: ‘90’, ‘unit’: ‘hours’}
90 days are 2160 hours 

Hey user, enter a number of days and a conversion unit
20:minutes
[‘20’, ‘minutes’]
{‘days’: ‘20’, ‘unit: ‘minutes’}
<class ’dict’>
20 days are 28800 minutes 

Hey user, enter a number of days and a conversion unit


Modules 

#Modules
# logically organize your Python code 
# Modules should contain related code 
# is just a .py file 

main.py // _inite_.py

from helper import validate_and_execute, user_input_message
import logging 

logger = logging.getLogger (“MAIN”)
logger.error (“Error happened in the app”) 
“”” Error happened in the app””” 

“””user_input = “”
while user_input != “exit”: // IDE warnings - help you to avoid mistakes   
   user_input = input (user_input_message )
   days_and_unit = user_input.split(“:”)
   print (days_and_unit) 
   days_and_unit_dictionary = {“days”: days_and_unit [0], “unit”: days_and_unit[1] }
   print ( days_and_unit_dictionary )  
   print (type(days_and_unit_dictionary)) 
 validate_and_execute ( days_and_unit_dictionary )”””

helper.py 


# Create a Module and import statement 


def days_to_units (num_of_days, conversion_unit):
     if conversion_unit == “hours”: 
     return f”{num_of_days} days are {num_of_days * 24 } hours”
elif conversion_unit == “minutes”: 
     return f”{num_of_days} days are {num_of_days * 24 * 60 } hours”
else 
     return “unsupported unit”
     elif num_of_days = = 0: 
         return “you entered a 0, please enter a valid positive number”
     else: 
         return “you entered a negative number, so no conversion for you!” 


def validate_and_execute ( days_and_unit_dictionary ) 
      try:  // Program Flow - 1. Is user input a digit? No.
try / except The try block : lets you “test” a block of code for errors
          user_input_number = int (days_and_unit_dictionary [“days”])

# Accessing Items in a Dictionary
# Items can be accessed by its key name 
# You can use square brackets or () get method 
# Your_dict [“days”] or your_dict.get (“days”)

           if user_input_number > 0: // It is a positive number ? Yes. 
               calculated value = days_to_units (user_input_number, days_end_unit_dictionary [“unit”] )
                print ( calculated_value )  
           elif user_input_number = = 0: 
                 print (“you entered a negative number no conversion for you !”) 
 except: ValueError: // “Also called try/catch in other programming language”
           print(“your input is not a valid number. Do not ruin my program”) 

user_input_message = “Hey user, enter a number of days and a conversion unit! /n”


Build_In Python Module

You can use many exiting Python Modules 
Datetime module provides you with many different functions that make it easier for you to work with dates and times !
from datetime import datetime, timezone
now = datetime.now () 
datetime.datetime ( 2018, 10, 7, 12, 27, 25, 527961 ) 
obj.astimezone ( timezone.utc ) 


Build_In Python Module Example

Project: Countdown App 


Project Exercise 
time-till-deadline.py

Exercise 

Accept user input of goal end a deadline
Print back:
                How much time remains until the deadline ? 
      
We make use of datetime module for the time calculation 

Solution Implementation 

from datetime import datetime 


user_input = input (“ enter your goal with a deadline separated by colon\n ”)
input__list = user_input.split (“ : ”)

goal = input_list [0]
deadline = input_list [1] 

deadLine_date = datetime.datetime.strptime (deadline, “%d.%m.%Y”)
today_date = datetime.today() 
time_till = deadLine_date - today_date

hours_till = int(time_till.total_seconds() / 60 / 60 )
print (f“Dear user! Time remaining for your goal: {goal} is {hours till} hours” )


enter your goal with a deadLine separated by colon

2021-02-07 13:51:20 .845322
learn python: 12.8.2021
185 days, 10:07:01.878109

learn python: 20.06.2021 
Dear user! Time remaining for your goal: learn python is 132 days, 10:03:06.754276

learn python: 20.06.2021 
Dear user! Time remaining for your goal: learn python is 132 

learn python: 20.06.2021 
Dear user! Time remaining for your goal: learn python is 132 days 

learn python: 20.06.2021 
Dear user! Time remaining for your goal: Learn python is 4450.0000416111 hours 

learn python: 10.02.2021
Dear user! Time remaining for your goal: Learn python is 57 hours


print (input_list) 

Hey user, enter number of days and conversion unit ! 
learn python: 10.02.2021 

enter your goal with a deadline separated by colon
learn python: 12.07.2021 
[‘learn python’, ‘12.07.2021’]


#How would you know how to use a module ? 
google, see some examples, etc.

https://www.w3schools.com/python/python_datetime.asp

module documentation 


Third-Party Packages 

Build-In versus Third-Party 

Python comes with only a set of build-in modules 
Many more modules out there, witch are NOT party of the python installation
You need to install this third-party packages 
Build-In Modules and Packages are most common ones
Depending on what application you write, add specific ones

Web machine 
Django ( Where do I find these packages ?)
                        ( How do I install them ? )
https://pypi.org/ 

Machine learning App 

Module versus Package 
Module 
Any python file is a module 
            Package 
Package is a collection of Python modules 
Package must include an_init_.py file 
This _init_ file distinguishes a package from a directory 



https://pypi.org/ 
The Python Package Index (PyPI)
PypI is a repository ( storage ) for third-party Python package 
People can publish their packages to this repository 
So it became available for everyone to use
A large community means, many people are creating useful modules and make them available for others 


pip  pip is a package manager for python 
https://pypi.org/project/Django/

pip is a package manager for python 
used to install packages from the Python Package Index, but also other indexs 
pip is included in the Python Installation 
import django 
pip uninstall django 
proceed (y/n)? y 
Successfully uninstalled Django-4.1.7


Python Packages Tool Window

Extension
https://docs.djangoproject.com/en/4.1/
https://djangopackages.org/

Project : Automation with Python 
Project Introduction 

Learn how to work with Spreadsheets
Read spreadsheet file and automate stuff 


main.py 
inventory.xlsx

Exercises 
Ex: List each company with respective product count 
# Exercise-Result: 
{‘AAA Company’: 43, ‘BBB Company’:17, ‘CCC Company’: 14 } 


Ex: List products with inventory less than 10 
# Exercise-Result:
{25:7, 30:06, 74:2}

Ex: List each company with respective total inventory value 
# Exercise-Result: {‘AAA Company’: 10969059.95, ‘BBB Company’: 2375499.47, ‘CCC Company’: 8114363.62}

Ex: Write to spreadsheet: Calculate and write inventory value for each product into spreadsheet 


Install Package 
   
main.py 
inventory.xlsx

Different ways to work with files
Python has several build-in functions for handling files in general
iomodule / create, read, write 

f = open (“demofile.txt”, “r”)

# Read
f.read ()

# Write 
f.write (“Now the file has more content !”)

#Close the file
f.close()

Python package to work with spreadsheets specifically 

more practical functions for spreadsheets specifically 
easier to use 

https://pypi.org/
https://pypi.org/search/?q=openpyxl

Terminal 
(venv) [/W] $ pip install openpyxl 
… successfully installed openpyxl-3.0.6






Module = .py file 
Package = collection of modules.
Library = collection of packages 
                   

Implementation

main.py 
import openpyxl 
inv_file = openpyxl.load_workbook (“Inventory.xlsx”) 
product_list = inv_file[“sheet1”]

for product_row in range (product.list.max_row) 
range () 
creates a sequence of numbers 
start from 0 by default: 
range 75 - [0,1,2,3,...74]
valid for loop 
we can iterate over and do something for each item in this list  [0,1,2,3,...74]

for product_row in range  (2 product.list.max_row + 1)
        supplier_name = product_list.cell (product_row, 4).value 
        inventory = product_list.cell (product_row, 2).value 
        price = product_list.cell (product_row, 3).value  
        product_num =  product_list.cell (product_row, 1).value
        inventory_price = product.cell(product_row, 5)

# calculation number of products per supplier 
    if supplier_name in products_per_supplier:
  current_num_products = products_per_supplier.get (supplier_name) 
   products_per_supplier [supplier_name]
= current _num_products + 1
     else: 
             products_per_supplier [supplier_name] = 1

# calculation total value of inventory per supplier 
    if supplier_name in total_value_per_supplier:  
     current_total_value =  total_value_per_supplier.get (supplier_name) 
   total_value_per_supplier [supplier_name]  =  current_total_value + inventory * price 
    else: 
            total_value_per_supplier [supplier_name] = inventory * price 

# logic products with inventory less than 10 
 if inventory < 10: 
   products_under_10_inv = [int(product_num)] =int( inventory)
   print ( products_under_10_inv )

# add value for total inventory price 
inventory_price.value = inventory * price 


print( products_per_supplier )
print ( total_value_per_supplier )
print ( products_under_10_inv ) 

inv_file.save(“inventory_with_total_value.xlsx”) 

{‘AAA Company’: 43, ‘BBB Company’:17, ‘CCC Company’: 14 } 
{‘AAA Company’: 10969059.95, ‘BBB Company’: 2375499.47, ‘CCC Company’: 8114363.62}
{25.0:7.0, 30.0:6.0, 74.0: 2.0}

adding a new supplier 
adding a new supplier
adding a new supplier

{“AAA Company”: 43, “BBB Company”:17, “CCC Company”:14}

{“AAA Company”: 10969059.95, “BBB Company”:2375499.47, “CCC Company”:8114363.62}


Exercises
Ex: List each company with respective product count
Ex: Total inventory value per supplier 
EX : List each company with respective total inventory value

{“AAA Company”: 1, “BBB Company”:1}

range (2, max_row) [2,3,4…]

Inventory Sheet 
Go through each and every row in the sheet ?
Execute the same logic on each item ? 

Looping ! 
How many times to execute ? 
As many times as the number of product


Exercise 1 

products_per_supplier = {“ “}

name of company
Key : value 
Product count 
# Exercise-Result: 
{‘AAA Company’: 43, ‘BBB Company’:17, ‘CCC Company’: 14 } 

Classes and Objects 

Object-oriented programming
Objects
Classes 
email = “nn@nn.com”
name =”Nana Janashia“
password = “pwd”
current_job_title = “DevOps engineer”

def change_password ():
        # do smth
def change_job_title ():
        # do smth
def add_new skill ():
        # do smth

User -  User Attributes
Email            email = “nn@nn.com”
Name            name =”Nana Janashia“
Password      password = “pwd”
Job Title        current_job_title = “DevOps engineer”           

           User Behavior 
change _pwd  change pwd
change_job     change job 

What information does a user have ?
What actions can a user perform ? 


Create a Class 

user.py ( Class ) 

class User: 
   def __init__ ( self, user_email, name, password, current_job_title ): 
             self.email = user_email
             self.name = name
             self.password = password
             self.current_job_title = current_job_title 



# 1 - Object will be created with initial values 
#  tom User ( “tt@tt.com,”, ”Tom”, “pwd”, “Developer” )
# Call function on that object to change its password
# tom.change_password(“betterpwd”)



   def change_password (self, new_password):
         self.password = new_password
             # do smth
   def change_job_title (self, new_job_title):
          self.current_job_title = new_job_tilte
   def get_user_info(self): 
   print(f”User{self.name}currently works as a {self.current_job_title}. You can contact them at {self.email}”)


   app_user_one = User(“nn@nn.com”, “Nana Janashia”, “pwd1”, “DevOps Engineer”)
app_user_one.get_user_info () 
app_user_one.change_job_title (“DevOps Trainer”)
app_user_one.get_user_info()

app_user_two = User (“aa@aa.com”, “James Bond”, “supersecret”, “Agent”)
app_user_two.get_user_info()


# Methods - Functions that belong to an object are called methods. 

             # do smth
# Classes
class is like an object constructor 
# “self” Parameter 
self is a reference to the current instance of the class


Create an Object

 User Nana Janashia currently work as a DevOps Engineer. You can contact them at nn@nn.com 
 User Nana Janashia currently work as a DevOps Trainer. You can contact them at nn@nn.com 
 User Nana Janashia currently work as a Agent. You can contact them at nn@nn.com 



main.py
from user import User 

from post import Post
app_user_one = User(“nn@nn.com”, “Nana Janashia”, “pwd1”, “DevOps Engineer”)
app_user_one.get_user_info () 
app_user_two = User (“aa@aa.com”, “James Bond”, “supersecret”, “Agent”)
app_user_two.get_user_info()

new_post = Post (“on a secret mission today”, app_user_two.name)
new_post.get_post_info()

User Nana Janashia currently work as a DevOps Engineer. You can contact them at nn@nn.com 
 User Nana Janashia currently work as a Agent. You can contact them at nn@nn.com 
Post: on a secret mission today written by James Bond

Create Another Class and Objects 

post.py
class Post:
        def __init__(self, message, author):
        self.message = message
        self.author = author
        
def get_post_info (self):
      print(f”Post: {self.message} written by {self.author}”)
 
main.py
from user import User 


Object Oriented Programming 


Project:

API Request to GitLab
      Python and GitLab
HTTP request
HTTP response 
API request

Implementation 
https://pypi.org/project/requests/
pip install requests
main.py
import requests

response = requests.get(“http://gitlab.com/api/v4/users/nanuchi/:user_id/projects”)
https://docs.gitlab.com/ee/api/rest/#valid-api-request 
https://docs.gitlab.com/ee/api/projects.html#list-user-projects 
my_projects = response.json()
for project in my_projects:
print(f”Project Name: {project[‘name’]}”) \nProject Url: {project[‘web_url’]}\n)

Project Name: python-programming Project Url: …
Project Name: Python Programming 
Project Url: https://gitlab.com…

print(response.json) # lightweight format for transporting data, often use to send data over the web

#Request in JSON
#Response in JSON
#json() - requests json() function converts the data from json into Python data type

<Response [200] >
[{ “id:24254492, …
print(type(response.json))
<class ‘str’>
[{ “id:24254492, …
<class ‘list’> 
print (response.json([0]))
[{ “id:24254492, …
<class ‘list’> 
{ “id:24254492, …


Wrap Up

