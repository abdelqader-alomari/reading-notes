### Read: 05 - Operators and Loops:

## Operators:
JavaScript has different kinds of operators:

![Operators](https://www.miltonmarketing.com/wp-content/uploads/2018/04/mmjavascriptoperators4533535Javascript3-min.png)
### Logical Operators:
Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value.
![True table] (https://documents.sessions.edu/eforms/courseware/coursedocuments/javascript_for_designers/javascriptfordesigners_images/img_2x_truth-tables.png)

### Arithmetic Operators:

* The assignment operator (=) assigns a value to a variable.
* The addition operator (+) adds numbers
* The multiplication operator (*) multiplies numbers.
* The divistion operator (/) divides numbers.

### Assignment Operators:

Assign values to JavaScript variables.

such as: The addition assignment operator (+=) adds a value to a variable.

### String Operators:

The + operator can also be used to add (concatenate) strings.

Example:

var txt1 = "What a very ";

txt1 += "nice day";

The result of txt1 will be:

What a very nice day
-----

*Adding Strings and Numbers:*

Adding two numbers, will return the sum, but adding a number and a string will return a string:

### Comparison Operator:

| Operator | Discription |
| -------- | ----------- |
| == |	equal to |
| === |	equal value and equal type |
| != |	not equal |
| !== | not equal value or not equal type
| > |	greater than |
< |	less than |
>= |	greater than or equal to |
<= |	less than or equal to |
?	| ternary operator |

---------------------------

## Loops:

![Loops](https://www.toolsqa.com/wp-content/uploads/2020/02/JAVASCRIPT-LOOPS.jpeg)

Loops offer a quick and easy way to do something repeatedly.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

## for statement:

![For Loop](https://cdn.programiz.com/sites/tutorial2program/files/javascript-for-loop.png)

A for loop repeats until a specified condition evaluates to false.

A for statement looks as follows:

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
When a for loop executes, the following occurs:

The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
If present, the update expression incrementExpression is executed.
Control returns to Step 2.

### while statement:

![While loop](https://kindsonthegenius.com/javascript/wp-content/uploads/2020/01/While-loop.jpg)

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.
