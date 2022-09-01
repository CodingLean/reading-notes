## This section is dedicated to the JavaScript language itself, and not the parts that are specific to Web pages or other host environments. For information about APIs that are specific to Web pages, please see Web APIs and DOM.

# When to Use JavaScript const?
If you want a general rule: always declare variables with const.
If you think the value of the variable can change, use let.
CONST = a constant value that will never change


# JavaScript Identifiers
All JavaScript variables must be identified with unique names.
These unique names are called identifiers.
Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).
The general rules for constructing names for variables (unique identifiers) are:
Names can contain letters, digits, underscores, and dollar signs.
Names must begin with a letter
Names can also begin with $ and _ (but we will not use it in this tutorial)
Names are case sensitive (y and Y are different variables)
Reserved words (like JavaScript keywords) cannot be used as names.


# Value = undefined
In computer programs, variables are often declared without a value. The value can be something that has to be calculated, or something that will be provided later, like user input.
A variable declared without a value will have the value undefined.

# JavaScript Underscore (_)
Since JavaScript treats underscore as a letter, identifiers containing _ are valid variable names:
