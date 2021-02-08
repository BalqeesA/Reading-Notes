
## Lists
There are lots of occasions when we need to use lists. HTML provides us with three different types:
●● Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.
●● Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).
●● Definition lists are made up of a set of terms along with the definitions for each of those terms.

## Boxes
At the beginning of this section on CSS, you saw how CSS treats each HTML element as if it lives in its own box. You can set several properties that affect the appearance of these boxes.

### box dimenisions 
width, height
By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties.

### Border, Margin & Padding
Every box has three available properties that
can be adjusted to control its appearance:

Border
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

Margin
Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

Padding
Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

## ARRAYS
An array is a special type of variable. It doesn't just store one value; it stores a list of values

## CREATING AN ARRAY
You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array).

## USING IF ... ELSE STATEMENTS
Here you can see that an if ... e 1 se statement al lows you to provide two sets of code:
1. one set if the condition evaluates to true
2. another set if the condition is false

## SWITCH STATEMENTS
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

## TYPE COERCION & WEAK TYPING
If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error

JavaScript can convert data types behind the scenes to complete an operation. This is known as type coercion. For example, a string 'l ' could be converted to a number 1 in the following expression:(' 1' > 0). As a result, the above expression would evaluate to true.

## TRUTHY & FALSY VALUES
Due to type coercion, every value in JavaScript can be treated as if it were true or false; and this has some interesting side effects.

Falsy values are treated as if they are fa 1 se. The table to the left shows a hi ghScore variable with a series of va lues, all of which are falsy.

Truthy values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true.

## CHECKING EQUALITY & EXISTENCE
Because the presence of an object or array can be considered truthy, it is often used to check for the existence of an element within a page.

A unary operator returns a result with just one operand. Here you can see an if statement checking for the presence of an element. If the element is found, the result is truthy, so the first set of code is run. If it is not found, the second set is run instead

## SHORT CIRCUIT VALUES
Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or fa 1 se).

Logical operators will not always return true or false, because:
• They return the value that stopped processing.
• That va lue might have been treated as truthy or fa lsy

although it was not a Boolean. Programmers use this creatively (for example, to set values for variables or even create objects).


## KEY LOOP CONCEPTS
Here are three points to consider when you are working with loops. Each is illustrated in examples on the following three pages

KEYWORDS
You will commonly see these two keywords used with loops

break
This keyword causes the termination of the loop and tells the interpreter to go onto the next statement of code outside of the loop. (You may also see it used in functions.)

continue
This keyword te lls the interpreter to continue with the current iteration, and then check the condition again. (If it is true, the code runs again.)

LOOPS & ARRAYS
Loops are very helpful when dealing with arrays if you want to run the same code for each item in the array.

PERFORMANCE ISSUES
It is important to remember that when a browser comes across JavaScript, it will stop doing anything else until it has processed that script

### USING FOR LOOPS
A for loop is often used to loop through the items in an array.

### USING WHILE LOOPS
loop will continue to run for as long as the condition in the parentheses is true. That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block should run.

### USING DO WHILE LOOPS
The key difference between a whi 1 e loop and a do whi 1 e loop is that the statements in the code block come before the condition. This means that those
statements are run once whether or not the condition is met.




























