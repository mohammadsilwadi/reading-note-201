# **Lists**
There are lots of occasions when we
need to use lists. HTML provides us with
three different types:
* Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
- Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).
* Definition lists are made up of a set of terms along with the
definitions for each of those terms.

The ordered list is created with
the <"ol"> element.
+ Each item in the list is placed
between an opening <'li'> tag
and a closing </'li'> tag. (The li
stands for list item.)

The unordered list is created
with the <'ul'> element.
+ Each item in the list is placed
between an opening <'li'> tag
and a closing </'li'> tag. (The li
stands for list item.)

<'dl'>
The definition list is created with
the <'dl'> element and usually
consists of a series of terms and
their definitions.
Inside the <'dl'> element you will
usually see pairs of <'dt'> and
<'dd'> elements.
+ <'dt'>
This is used to contain the term
being defined (the definition
term).
+ <'dd'>
This is used to contain the
definition.

# Boxes
![Box-Model](https://miro.medium.com/max/700/0*5qeKw4RhW1BxgEMx.png).
+ Border>
Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge of one box
from another.

* Margin>
Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two
adjacent boxes.

- Padding>
Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.

# Decisions and Loops
A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value.

![SWITCH STATEMENT](https://cdn.educba.com/academy/wp-content/uploads/2019/10/php-Switch-Statement.png.webp).
### TRUTHY & FALSY VALUES
In JavaScript, a truthy value is a value that is considered true when encountered in a Boolean context. All values are truthy unless they are defined as falsy (i.e., except for false , 0 , -0 , 0n , "" , null , undefined , and NaN ). JavaScript uses type coercion in Boolean contexts.
![Truthy Falsy edge cases](https://miro.medium.com/max/700/1*s-FasudN5aSYnX2rDz75AA.jpeg).

# LOOPS 


**Loops and iteration**

**for statement**>*A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.*
A for statement looks as follows:

**for** *([initialExpression]; [conditionExpression]; [incrementExpression])*

*statement*

*The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. *

**while statement**
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

**while** *(condition)*
 
 *statement*

*The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.*
