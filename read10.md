# Error Handling & Debugging

Each time a script enters a new execution context, there are two phases
of activity:

1-  PREPARE

+ The new scope is created

+ Variables, functions, and arguments are created

+ The value of the this keyword is determined

2-  EXECUTE

+ Now it can assign values to variables

+ Reference functions and run their code

+ Execute statements

## ERROR OBJECTS

Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

 ### some types of errors 

+ Syntax Error 
SYNTAX IS NOT CORRECT 
This is caused by incorrect use of the rules of the 
language. It is often the result of a simple typo. 

+ Ref erenceError 
VARIABLE DOES NOT EXIST 
This is caused by a variable that is not declared or is 
out of scope. 

+ Ev alError 
INCORRECT USE OF eval() FUNCTION 
The eva l () function evaluates text through the 
interpreter and runs it as code (it is not discussed 
in this book). It is rare that you would see this type 
of error, as browsers often throw other errors when 
they are supposed to throw an Eva 1 Error.

+ UR I Error 
INCORRECT USE OF URI FUNCTIONS 
If these characters are not escaped in URls, they will 
cause an error: / ? & I : ; 
CHARACTERS ARE NOT ESCAPED 
decodeURI('http: //bbc . com/ news . phplla=l'); 
URlError: URI error.

+ Type Error 
VALUE IS UNEXPECTED DATA TYPE 
This is often caused by trying to use an object or 
method that does not exist. 

+ RangeError 
NUMBER OUTSIDE OF RANGE 
If you call a function using numbers outside of its 
accepted range.
