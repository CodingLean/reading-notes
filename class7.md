# Control flow
- means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

Function parameters are listed inside the parentheses () in the function definition.
Function arguments are the values received by the function when it is invoked.
Inside the function, the arguments (the parameters) behave as local variables.

# Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

-When an event occurs (when a user clicks a button)
-When it is invoked (called) from JavaScript code
-Automatically (self invoked)
You will learn a lot more about function invocation later in this tutorial.

# JavaScript Arithmetic Operators
Arithmetic operators are used to perform arithmetic on numbers:

Operator	Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement

# JavaScript Assignment Operators
Assignment operators assign values to JavaScript variables.

Operator	Example	        Same As
=	        x = y	        x = y
+=      	x += y      	x = x + y
-=	        x -= y	        x = x - y
*=	        x *= y	        x = x * y
/=	        x /= y	        x = x / y
%=	        x %= y	        x = x % y
**=	        x **= y	        x = x ** y

# JavaScript String Operators
The + operator can also be used to add (concatenate) strings.

# JavaScript  Comparison Operators
Operator	Description
==      	equal to
===	e       qual value and equal type
!=	        not equal
!==	        not equal value or not equal type
>	        greater than
<	        less than
>=	        greater than or equal to
<=	        less than or equal to
?	        ternary operator

# JavaScript Logical Operators
Operator	Description
&&	        logical and
||	        logical or
!	        logical not

# JavaScript Bitwise Operators
Bit operators work on 32 bits numbers.

Any numeric operand in the operation is converted into a 32 bit number. The result is converted back to a JavaScript number.
Operator	Description             Example	    Same as	      Result	Decimal
&	        AND	                    5 & 1	    0101 & 0001	    0001	  1
|	        OR	                    5 | 1	    0101 | 0001	    0101	  5
~	        NOT	                    ~ 5	        ~0101	        1010	 10
^	        XOR	                    5 ^ 1	    0101 ^ 0001	    0100	  4
<<	        left shift	            5 << 1	    0101 << 1	    1010	 10
>>	        right shift	            5 >> 1	    0101 >> 1	    0010	  2
>>>	        unsigned right shift	5 >>> 1	    0101 >>> 1	    0010	  2


# Comparison operators
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

