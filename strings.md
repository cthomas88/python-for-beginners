# Strings

## What is a string?

A string is a collection of characters, which can include letters, numbers and even punctuation. 

## How are strings defined and displayed in Python?

A string can be a data type and can be assigned to a variable name. Whenever we give a variable name string data, we put place the string inside quotations marks. Take a look at this example:

<pre><code>string_variable = "I am a string!"</code></pre>

You can also use single quotations to define a string, it doesn't matter:

<pre><code>another_string = 'I am also a valid string!'</code></pre>

## What if I need to include an apostrophe or quotation marks within my string?

Sometimes your string may need to include an apostrophe or quotation marks, and so you need to tell Python when to ignore such punctuation. The following code will produce an error, because Python will attempt to end the string prematurely:

<pre><code>a_string = "Mark is a boy and he says "hi!", Mark also has a cat."</code></pre>

The string in this code will end at the first quotation mark within the string, just before hi!. This is because Python detects that this is a string, thanks to the very first quotation mark, and it looks for the end of the string in the form of another quotation mark. From hi!" ... to the very end of the string is not understood by Python and so an error will occur. 

It is perfectly OK to use a single apostrophe within a string that has been outlines with double quotation marks, as in this example:

<pre><code>a_string = "Mark is a boy and he says 'hi!', Mark also has a cat."</code></pre>

And you can also swap these around just like this:

<pre><code>a_string = 'Mark is a boy and he says "hi!", Mark also has a cat.'</code></pre>

## What if I need to include several various punctuation marks within my string?

I want to write a string that looks like this:

<pre><code>string = '"I am writing a Python string", Said Harry's mum. 'Nice!' Thought Harry.'</code></pre>

Running this code will output the following in Python 3:

<pre><code>SyntaxError: invalid syntax</code></pre>

And the string will attempt to end at the end of the first instance of the word Harry, where an apostrophe appears as it refers to Harry's mother. 

Therefore the string looks like this:

<pre><code>string = '"I am writing a Python string", Said Harry'</code></pre>

And the rest of the text from s.. on wards, will cause Python to run an error because it doesn't know what the rest of the text is meant to be!

There is a way to make Python ignore a piece of punctuation's original meaning and to include it in the string it is written within, and that invovles using the '\' mark, or the backslash, directly before the punctutation mark you want python to ignore. 

So, our string will eventually look like this:

<pre><code>string = '"I am writing a Python string", Said Harry\'s mum. \'Nice!\' Thought Harry.'
print (string)

>>> "I am writing a Python string", Said Harry's mum. 'Nice!' Thought Harry.</code></pre>

Ensure you place your backslash directly in front of the punctuation mark you want Python to ignore, with no spaces between them. As you type strings like this into your text editor, placing a \ will probably cause the text editor to highlight the backslash and proceeding punctuation mark in a different color. 
