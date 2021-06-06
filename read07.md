# Control flow
![controlflow](https://miro.medium.com/max/1820/1*Z1saasjHQBVQWNHKdnh6fw.png)

***The control flow is the order in which the computer executes statements in a script.***

***Code is run in order from the first line in the file to the last line, unless the computer runs across the structures that change the control flow, such as `conditionals` and `loops`.***

***For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:***

`if (field==empty) {`

`promptUser();`

`} else {`

`submitForm();`

`}`

**A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.**

## more about control flow

***In computer science, control flow (or flow of control) is the order in which individual statements, instructions or function calls of an imperative program are executed or evaluated. The emphasis on explicit control flow distinguishes an imperative programming language from a declarative programming language.***

***Within an imperative programming language, a control flow statement is a statement that results in a choice being made as to which of two or more paths to follow. For non-strict functional languages, functions and language constructs exist to achieve the same result, but they are usually not termed control flow statements.***

**for more information click on the following [link](https://en.wikipedia.org/wiki/Control_flow)


## Functions

***Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.***

### Defining functions

***A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:***

* The name of the function.

* A list of parameters to the function, enclosed in parentheses and separated by commas.

* The JavaScript statements that define the function, enclosed in curly brackets, `{...}`.

**For example, the following code defines a simple function named square:**

`function square(number) {`

`return number * number;`

`}`

## JavaScript Functions

***JavaScript function is a block of code designed to perform a particular task.***

***A JavaScript function is executed when "something" invokes it (calls it).***

## JavaScript Function Syntax

***A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().***

***Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).***

***The parentheses may include parameter names separated by commas:***
***(parameter1, parameter2, ...)***

***The code to be executed, by the function, is placed inside curly brackets: {}***

`function name(parameter1, parameter2, parameter3) {`

`// code to be executed`

`}`

### Why Functions?

* ***You can reuse code: Define the code once, and use it many times.***

* ***organize the code better.***

## JavaScript Operators

***javascript have many operators and we are going to talk about few of them.***

### operator types

* The assignment operator (=) assigns a value to a variable.
`var x = 10;`
* The addition operator (+) adds numbers: 
`var z = x + y;`
* The multiplication operator (*) multiplies numbers.

`var z = x * y;`

### Adding Strings and Numbers
 Adding two numbers, will return the sum, but adding a number and a string will return a string:

`var x = 5 + 5;`

`var y = "5" + 5;`

`var z = "Hello" + 5;`

The result of x, y, and z will be:

`10`

`55`

`Hello5`




