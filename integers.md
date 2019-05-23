# Integers

## What is an integer?

An integer is a whole number, commonly used in most programming languages. Integers, (often referred to as an 'int') has no decimal point at the end of it, even if a zero follows the decimal point. 

## Integer examples

Here is a list of numbers. ALL of these are integers:

- 3
- 67
- 492
- 7969276459827034
- 100000
- 1

## What can I do with integers in Python?

Variables can be used to store integer values. If you need to know what a variable is take a look at the chapter entitles 'variables.md'.

Here is an example of a variable with a value that is an integer:

<pre><code>oranges = 6
apples = 9

basket = oranges + apples

print(basket)

Output: 15</code></pre>

When assigning an integer to a variable there is no need for quotation marks or any other defining decoration around the number. Place a number within quotation marks would make the number a 'string' and mathematical equations could not longer be used on the numbers. See the 'string' chapter to find out what a string in Python is. 

## What if I want a whole number as my mathematical answer?

Dividing two numbers that do not equally part in Python 3 will automatically result in the ouput being a *floating* number. There is a whole chapter on floating numbers if this concept is new to you. You can tell Python to output integers only by prefixing the argument with 'int'. Here's an example:
### For Python 3

<pre><code>print (10 / 3)
>>> 3.333333333</code></pre>

However, you may just want the number 3 on its own rather than this long output. To do this prefix your sum with int, like this:

<pre><code>print (int(10 / 3))
>>> 3</code></pre>

Remember, in Python 3 everything you want to print must be in parethesis, and so must the sum you want to convert to an integer.

### Basically, an integer is ANY whole number!
