# Expressions and operators
# Loops and iteration

![operators](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS76aVIo4u18ZBAVWU79QkDQ6uvKUjF4leJ7g&usqp=CAU)

## operators

***JavaScript has the many types of operators, and here we are going to talk about few of them.***

### Assignment operators

***An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.***

### Comparison operators

***A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the `===` and `!==` operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.***

### Arithmetic operators

***An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).***

**For example:**

`1 / 2; // 0.5`

`1 / 2 == 1.0 / 2.0; // this is true`

### Bitwise operators

***A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.***

### Logical operators

***Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the `&&` and `||` operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table.***

### String operators
***In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.***

**For example**:

`console.log('my ' + 'string'); // console logs the string "my string".`

# Loops and iteration
***Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.***

## for statement

***A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.***

**A for statement looks as follows:**

`for ([initialExpression]; [conditionExpression]; [incrementExpression])`

`statement`

**When a for loop executes, the following occurs:**

* The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
* The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
* The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
* if present, the update expression incrementExpression is executed.
* Control returns to Step 2.

## while statement
***A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:***

>`while (condition)`

>`statement`

***f the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.***

***The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.***

***To execute multiple statements, use a block statement `({ ... }) `to group those statements.***

**example:**

`let n = 0;`

`let x = 0;`

`while (n < 3) {`

`n++;`
  
`x += n;`

`}`

***With each iteration, the loop increments n and adds that value to x. Therefore, x and n take on the following values:***

* After the first pass: n = 1 and x = 1
* After the second pass: n = 2 and x = 3
* After the third pass: n = 3 and x = 6

***After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.***

## break statement

Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.

* When you use break without a label, it terminates the innermost enclosing `while`, `do-while`, `for`, or `switch` immediately and transfers control to the following statement.
* When you use `break` with a label, it terminates the specified labeled statement.

**The syntax of the break statement looks like this:**

>`break;`

>`break [label];`



1. The first form of the syntax terminates the innermost enclosing loop or `switch`.
2. The second form of the syntax terminates the specified enclosing labeled statement.