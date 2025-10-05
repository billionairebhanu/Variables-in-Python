# Variables-in-Python
Know about Variables in Python

VARIABLES
Variables are names or labels that reference value stored in a memory. it allow you to hold data and manipulate it within a program.
        
        x =  10
        name = "Leo" 
naMe , Name , name are different variables, so -- Python is Case-sensitive. 
python automatically save it as string, because we use double / single - quotation
here variable is X and name. 
Must start with a letter or an underscore (_)
    
      print(type(x))
      print(type(name))


Data Types:
1. Integers
A whole number, positive or negative, without a decimal point.
Example: 10, -5, 0, 99999

2. String
A sequence of characters (letters, numbers, symbols, spaces) enclosed in single quotes ('...'), double quotes ("..."), or triple quotes ("""...""").
Example: "Hello World", 'Python', "123 Main St"

3. Float
A number, positive or negative, that contains one or more decimal points. These are also known as "floating-point numbers."
Use: Calculations involving division, percentages, temperatures, or currency.
Example: 3.14, -0.01, 2.0 (Note: 2.0 is a float, while 2 is an integer).


5. Boolean
A data type that can only have one of two values: True or False. (Note the capital 'T' and 'F').
Use: Representing truth values, controlling program flow (e.g., in if/else statements), and evaluating conditions.
Example: True, False

6. None
A special constant that represents the absence of a value or a null value. It is its own unique data type (NoneType).
Use: Used to indicate that a variable has not been assigned a specific value yet, or as a default return value for functions that don't explicitly return anything.




       num = 10
       num=num+10
       print(num)
it can also be written as
 
       num = 10
       num+=10
       print(num)


       a=10
       a*=5
       print(a)

Logical Operators

       print(not True) #not will convert true into false and false into true
       print(not False)

Create variables for your name, age, and favorite color. Print them using f-string formatting.

       name = 'Bhanu'
       Age = '32'
       Favourite_colour = "Green"
       message = f"My name is {name.title()}, my age is {Age}, and My favourite_colour is {Favourite_colour.title()}."
       print(message)


Assign values to two variables and swap their values without using a third variable.

     First_Name = "Bhanu"
     last_Name = "Partap"
     First_Name , last_Name = last_Name , First_Name
     message = f"First_Name = {First_Name} , last_Name = {last_Name}"
     print(message)
     
Assign values to three variables in a single line, then modify two of the variables and print all three.

    a,b,c = 4,5,6
    a+=2
    b+=1
    print(a,b,c)
  
