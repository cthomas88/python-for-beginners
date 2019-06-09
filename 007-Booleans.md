# Booleans

## What is a Boolean?

A boolean is a computing variable that equates to either true or false ONLY and can have no other result. True or false can also be represented in numeric terms:

1 = True
0 = False

Boolean's use comparison operators and are useful in comparing two different values or variables to decide whether to carry out an operation or not. 

## How to define a Boolean

Generally booleans are not defined in a variable like most other input types, as the code itself will work out whether something is true or not. 

## What are booleans best used for

'While' and for 'loops' and 'if' statements use booleans in order to decide whether an operation should or should not be carried out.

## Here's an example

Here we have a variable to which we have asigned a number of your choice. The following code prints out a statement if the statement is true and if the statement if false. Look through the process slowly to fully understand what is happening here, and reacreate your own version in your text editor. 

<pre><code>num1 = 35

if num1 > 50:
    print ("This number is bigger than 50")
else:
    print ("This number is smaller than 50")

>>> "This number is smaller than 50"</code></pre>

This if statement prints out one of two statements depending on what the number assigned to the vairable num1 is. In this particular example the program compares the num1 number (in this case 35) to 50. First it checks if the number is greater than 50. The result is False and so the program moves onto the next line. This time it works out if num1 is smaller than 50. This results as True, and so it moves onto the associated print statement. 

If you have yet to visit control flow in Python and 'if' statements and this doesn't make a lot of sense, just understand the basic concept, that if statements allow you to carry out an action IF something is true or false. 

## Comparison operators
