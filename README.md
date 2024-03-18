# INTRO-TO-JAVASCRIPT
What is javaScript?
JavaScript is the Programming Language for the Web. JavaScript can update and change both HTML and CSS. JavaScript can calculate, manipulate and validate data.
WEEK 1
DAY 1
Variables,Operators and Asasignment
Variables
Variables can be thought of as named containers. You can place data into these containers and then refer to the data simply by naming the container.
JavaScript is an untyped language. This means that a JavaScript variable can hold a value of any data type.
OPERATORS
Javascript operators are used to perform different types of mathematical and logical computations.
Examples:
The Assignment Operator = assigns values
The Addition Operator + adds values
The Multiplication Operator * multiplies values
The Comparison Operator > compares values

Types of JavaScript Operators

There are different types of JavaScript operators:
-Arithmetic Operators
-Assignment Operators
-Comparison Operators
-String Operators
-Logical Operators
-Bitwise Operators
-Ternary Operators

Operator	Description
+         	Addition
-	          Subtraction
*	          Multiplication
**	        Exponentiation (ES2016)
/	          Division
%	          Modulus (Division Remainder)
++	        Increment
--	        Decrement

ASSIGNMENT
Assignment operators assign values to JavaScript variables.
Logical Assignment Operators
Operator	     Example                        	Same As
&&=	x       &&= y	x = x &&                      (x = y)
||=	x       ||= y	x = x ||                      (x = y)
??=	x      ??= y	x = x ??                      (x = y)

The = Operator
The Simple Assignment Operator assigns a value to a variable.

DAY 2
Strings and Arrays
Strings
A string is a sequence of one or more characters that may consist of letters, numbers, or symbols. Strings in JavaScript are primitive data types and immutable, which means they are unchanging.
Strings are for storing text. they are written with quotes it can be double quotes or single quotes.
Javascript strings are primitive and immutable: All string methods produces a new string without altering the original string.
String Length
To find the length of a string, use the built-in length property:
The length property returns the length of a string:
arrays
An array is a special variable, which can hold more than one value. It is a common practice to declare arrays with the const keyword.
Why Use Arrays?
If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:
let car1 = "Saab";
let car2 = "Volvo";
let car3 = "BMW";
However, what if you want to loop through the cars and find a specific one? And what if you had not 3 cars, but 300?
The solution is an array!
An array can hold many values under a single name, and you can access the values by referring to an index number.
JavaScript Array length
The length property returns the length (size) of an array.
Popping and Pushing
When you work with arrays, it is easy to remove elements and add new elements.
This is what popping and pushing is:
Popping items out of an array, or pushing items into an array.
JavaScript Array pop()
The pop() method removes the last element from an array
JavaScript Array push()
The push() method adds a new element to an array (at the end)
The push() method returns the new array length

DAY 3
FUNCTIONS
functions are a code designed to perfome a particular task. it is executed when "something" invokes (call) it.
FUNCTION INVOCATION
When an event occurs (when you click on something)
When code is called from a javaScript code
Automatically (self-invocation)
Functions have what we call local viriable, these variable athe one that are declared inside a function and can only be accessed within an function. they are created when a function starts and are also deleted when a function is completed.
functions can also be used as variables. you can use functions in all data types such as calculators,assignments and also operators.
functions contain letters,digits and dollar sign just like a variable.
functions use paranthesis () aS THEIR operator. accesing a function without an operator you will only get the function and not the results.

JavaScript Function Syntax

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)
The code to be executed, by the function, is placed inside curly brackets: {}
Function parameters are listed inside the parentheses () in the function definition.
Function arguments are the values received by the function when it is invoked.
Inside the function, the arguments (the parameters) behave as local variables.

Function Return

When JavaScript reaches a return statement, the function will stop executing.
If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
Functions often compute a return value. The return value is "returned" back to the "caller"

DAY 3
JavaScript Booleans

A JavaScript Boolean represents one of two values: true or false. Normally JavaScript booleans are primitive values 

Boolean Values

Very often, in programming, you will need a data type that can only have one of two values, like
YES / NO
ON / OFF
TRUE / FALSE
For this, JavaScript has a Boolean data type. It can only take the values true or false.
The Boolean() Function
You can use the Boolean() function to find out if an expression (or a variable) is true
The Boolean value of an expression is the basis for all JavaScript comparisons and conditions

Comparisons and Conditions

The chapter JS Comparisons gives a full overview of comparison operators.
The chapter JS If Else gives a full overview of conditional statements.
Here are some examples:
Operator	               Description	Example
==	                     equal to	if (day == "Monday")
>	                       greater than	if (salary > 9000)
<	                       less than	if (age < 18)

In booleans Everything With a "Value" is True and also Everything without a "Value" is False.

WEEK 2 WEB DESIGN
DAY 1
INTODUCTION TO HTML,CSS AND JAVASCRIPT
Type Conversions

JavaScript Type Conversion

-Converting Strings to Numbers
-Converting Numbers to Strings
-Converting Dates to Numbers
-Converting Numbers to Dates
-Converting Booleans to Numbers
-Converting Numbers to Booleans

THIS HOW WE CONVERT THE ABOVE TYPES

1.String Conversion
String conversion happens when we need the string form of a value.  
For example, alert(value) does it to show the value.  
We can also call the String(value) function to convert a value to a string

2.Numeric Conversion  
Numeric conversion happens in mathematical functions and expressions automatically.  
For example, when division / is applied to non-numbers.

3.Boolean Conversion  
Boolean conversion is the simplest one.  
It happens in logical operations (later we’ll meet condition tests and other similar things) but can also be performed explicitly with a call to Boolean(value).  

4.Converting Variables to Numbers  
If you find yourself in need to turn a variable into a number, these are the three methods you can use: 
Number() 
Number() method is widely used to convert JavaScript variables into numbers. Although, if a number cannot be returned, the program will return NaN (Not a Number).
parseInt()
If you want to create a JavaScript integer, you should use parseInt(). It works by parsing a string and then returning the number. Spaces may be present in the string, but only the first number will be returned.  
parseFloat()
parseFloat() method works by parsing a string and then returning a floating point number. Spaces may be present in the string, but only the first number will be returned.

The Document Object Model and JavaScript Syntax

The Document Object Model is an Application Programming Interface (API) for HTML and XML documents. It does two things for web developers: 
Provides a structural representation of the document
Defines the way that that structure is to be accessed from script
This allows you to get at the web page as a structured group of nodes. Essentially, it connects web pages to scripts or programming languages.
The JavaScript syntax has to do with objects. To access an object, property, or method, its reference must include every object that contains it, separated by a dot. This is called the "dot syntax".

1.Object- a JavaScript object is any scriptable HTML element, that is, any HTML element within a document that may be accessed through the JavaScript language. Although the browser window is not an HTML element, it too is a scriptable object.

2.Property
Objects have properties, which you can think of as characteristics of an object. A JavaScript property has a similar relationship to the object it belongs to that an HTML tag attribute has to the tag that contains it. For example, the JavaScript "value" property is to a text field object as the HTML "width" attribute is to a table tag.

3.Method
Methods are actions that can be applied directly to objects. Within a web page, methods cause a boring old HTML document to react to the end user. This results in a meaningful experience for the end user which would otherwise be completely one-sided. A parameter is simply information needed by a method in order to accomplish its task.

Here are a Few JavaScript Methods:

-alert() causes an alert dialog box to appear over the page that launched it
-write() writes content to a page
-focus() causes the mouse cursor to be inserted into a form element

Core APIs in the DOM
document and window objects are the objects whose interfaces you generally use most often in DOM programming. In simple terms, the window object represents something like the browser, and the document object is the root of the document itself. Element inherits from the generic Node interface, and together these two interfaces provide many of the methods and properties you use on individual elements. 

The following is a brief list of common APIs in web and XML page scripting using the DOM.

-document.getElementById(id)
-document.getElementsByTagName(name)
-document.createElement(name)
-parentNode.appendChild(node)
-element.innerHTML
-element.style.left
-element.setAttribute
-element.getAttribute
-element.addEventListener
-window._content
-window.onload
-window.dump()
-window.scrollTo()

DAY 2

JAVASCRIPT APIS

API stands for Application Programming Interface.
A Web API is an application programming interface for the Web.
A Browser API can extend the functionality of a web browser.
A Server API can extend the functionality of a web server.

What Is a Regular Expression? 

A regular expression is a sequence of characters that forms a search pattern. 
A regular expression can be a single character, or a more complicated pattern. 
Regular expressions can be used to perform all types of text search and text replace operations. 

DAY 3
JAVASCRIPT FORMS

Constraint Validation DOM Methods

Property                  	Description
checkValidity()	            Returns true if an input element contains valid data.
setCustomValidity()	        Sets the validationMessage property of an input element.
If an input field contains invalid data, display a message

Constraint Validation DOM Properties

Property	                Description
validity	                Contains boolean properties related to the validity of an input element.
validationMessage	        Contains the message a browser will display when the validity is false.
Validity Properties
The validity property of an input element contains a number of properties related to the validity of data:

Property                              	Description
customError                           	Set to true, if a custom validity message is set.
patternMismatch	                        Set to true, if an element's value does not match its pattern attribute.
rangeOverflow	                          Set to true, if an element's value is greater than its max attribute.
rangeUnderflow	                        Set to true, if an element's value is less than its min attribute.
stepMismatch	                          Set to true, if an element's value is invalid per its step attribute.
tooLong	                                Set to true, if an element's value exceeds its maxLength attribute.
typeMismatch	                          Set to true, if an element's value is invalid per its type attribute.
valueMissing	                          Set to true, if an element (with a required attribute) has no value.
valid                                 	Set to true, if an element's value is valid.
willValidate	                          Indicates if an input element will be validated.

JAVASCRIPT SWITCH STATEMENT

The switch statement is used to perform different actions based on different conditions

This is how it works: 

The switch expression is evaluated once. 
The value of the expression is compared with the values of each case. 
If there is a match, the associated block of code is executed. 
If there is no match, the default code block is executed. 

Example: 

The getDay() method returns the weekday as a number between 0 and 6. 
(Sunday=0, Monday=1, Tuesday=2 ..)

Strict Comparison: 

Switch cases use strict comparison (===). 
The values must be of the same type to match. 
A strict comparison can only be true if the operands are of the same type. 

DAY 4

JAVASCRIPT EVE

