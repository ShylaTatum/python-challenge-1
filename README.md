# Menu

## Summary

Menu is creating an ordering system for a food truck. It allows the user to select from mulitpule menus. It keeps track of 
their order and prints an itemized receipt after the user is done ordering.

### _Question 1_
This creates an empty list that will be populated later in the program. 
 
### _Question 2_
This creates a question for the user to answer and stores the information provided for later use. An example of this 
can be found in in week 2 class 3 the first activity where a user provides a move for a game of Tic Tac Toe. 

### _Question 3_
This section is making sure that the user input can be used and understood by the code. A similar verification happens 
in week 2 class 3, in the game of tic tac toe in activity 1.

### _Question 4_
This section gathers the quantity and ensures it holds usable values. It also tells the user if there is an incorrect 
value. This is similar to an exercise on week 2 day 3 exercise 2.

### _Question 5_
This section allows the program to know when an order is complete or if it should continue to prompt the user. The use 
case of this matched the pie ordering in week 2 class 3.

### _Question 6_
The section is creating the loop that will allow for the creation of the receipt and the data it will contain. This was 
demonstrated by the 8th activity in week 2 day 3. 

### _Question 7_
This is to create the values that will appear on the receipt. We are creating a variable which will make for a simple 
way to call the information that is in the dictionary. This allows the later actions in this loop to cleanly use the data. 
This was demonstrated in week 2, day 3 activity 8. 

### _Question 8_
This creates a value that can be used later to have the correct number of spaces to align with the receipt. This value will 
look at the length needed and the length of the data. Since we won't know the length until the user provides input, the 
formula will ensure the correct length as the data changes order to order. This was found demonstrated in week 2 class 3 
activity 8.

### _Question 9_
This section is using the previous calculations and creating that number of spaces to be inserted later into the receipt. 
This is where is goes from a count to that number of spaces. This can be seen in week 2 day 3 activity 8. 


### _Question 10_
This allows the program to make a statement that uses data stored in variables so that the statement can change according
to the users inputs. There are examples throughout week 2 day 3, activity 1 uses it to tell teh user what the computer choose.  

### _Question 11_
This section is creating the total by creating a list comprehension that takes the amounts and multiples the correct quantities 
and makes a total. This was demonstrated in week 2 class 3 on the final exercise.

## General Verification

Helpful summation of Python brackets* :
>Generally, parentheses () are used for grouping expressions, defining functions or passing arguments, and defining tuples. 
>Square brackets [] are used for creating lists, indexing elements and slicing snippets. Curly braces {} serve two main 
>purposes: defining sets (unordered collections of unique elements) and dictionaries (key-value pairs).

Checking for Y or N** :

This resource was helpful in creating a solution for verifying if the user had answered Y or N; ultimatly a different solution 
was used. However the logic from this article was helpful in research and logic.  


## Citations

-[Syntax for decimal formating in question 11](https://tutorial.eyehunts.com/python/python-print-format-float-example-code/)

-[Clarification on paranthsis use*](https://discovery.cs.illinois.edu/guides/Python-Fundamentals/brackets/#:~:text=Generally%2C%20parentheses%20%28%29%20are%20used%20for%20grouping%20expressions%2C,collections%20of%20unique%20elements%29%20and%20dictionaries%20%28key-value%20pairs%29.)

-[Checking for Y or N**](https://stackoverflow.com/questions/38277231/python-input-from-user-is-not-recognized-as-y-or-n)
