# Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

There are also compound assignment operators that are shorthand for the operations listed in the following table:
Name	                                Shorthand operator	            Meaning
Assignment	                            x = f()	                        x = f()
Addition assignment	                    x += f()	                    x = x + f()
Subtraction assignment	                x -= f()	                    x = x - f()
Multiplication assignment	            x *= f()	                    x = x * f()
Division assignment	                    x /= f()	                    x = x / f()
Remainder assignment	                x %= f()	                    x = x % f()
Exponentiation assignment	            x **= f()	                    x = x ** f()
Left shift assignment	                x <<= f()	                    x = x << f()
Right shift assignment	                x >>= f()	                    x = x >> f()
Unsigned right shift assignment	        x >>>= f()	                    x = x >>> f()
Bitwise AND assignment	                x &= f()	                    x = x & f()
Bitwise XOR assignment	                x ^= f()	                    x = x ^ f()
Bitwise OR assignment	                x |= f()	                    x = x | f()
Logical AND assignment	                x &&= f()	                    x && (x = f())
Logical OR assignment	                x ||= f()	                    x || (x = f())
Logical nullish assignment	            x ??= f()	                    x ?? (x = f())


# for Loop
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
Copy to Clipboard
When a for loop executes, the following occurs:

The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
If present, the update expression incrementExpression is executed.
Control returns to Step 2.


# Structure of a while loop
