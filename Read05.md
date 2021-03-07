# Operators and Loops

*The code can take more than one path in flowchart script* as it behaves differently depending upon how the 
user interacts with the web page and/or the browser window itself from here comes the need to handle these 
paths programmers often rely upon the following three concepts:
 
1. EVALUATIONS You can analyze values in your scripts to determine whether or not they match expected results. 
2. DECISIONS Using the results of evaluations, you can decide which path your script should go down. The 
flowchart can help at making paths.
For decision there are two components :
a) An expression is evaluated, which returns a value
b) A conditional statement says what to do in a given situation
3. LOOPS can execute a block of code several times...
 Different Kinds of Loops:
 A) for - loops through a block of code several times
 B) while - loops through a block of code while a specified condition is true

**The syntax of a for loop**

for ( init; condition; increment )
 {
   statement(s);
}

**The syntax of the while loop**

init.
while (Condition) 
{
    statements ;
     update;
}


## USING IF ... ELSE STATEMENTS:-
An if ... else statement allows you to provide two sets of code:
1. one set if the condition evaluates to true
2. another set if the condition is false
the statements inside if a statement should be followed by a semicolon, but there is no need to place one after the closing curly brace of the code blocks

## A switch statement:-
*A switch statement* starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

## IF ...ELSE & SWITCH:-

**IF ... ELSE**
• There is no need to provide an else option. (You can just use an if statement.)
• With a series of if statements, they are if all checked even a match has been found (so it performs more slowly than switch).

**SWITCH**
• You have a default option that is run if none of the cases match.
• If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple if statements).
