# Uniwersity_OperatingSystems_Project1

Using the expr command, write a bash / zsh shell script that acts as a simple number calculator
integers with four basic actions (+ - * /) and
exponentiation (x ^ n, where: x - integer, n - natural number). Perform the exponentiation operation as a shell function. Belongs
include the precedence of operators (^, * /, + -).

Script invocation form:

calculator arg op arg op arg ...

The script should:

1) calculate and provide the final result,

2) signal syntax errors:

- invalid type of arguments (only integer arguments, also negative),

- invalid operator (valid operators: + - * / ^),

- incorrect number of arguments,

- division by 0,

- other,

3) provide the correct form of syntax in the case of invocation without arguments or detecting errors.