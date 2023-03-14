# JavaScript

JavaScript

- Variables

Variables are containers for storing data (storing data values).

we can declare variable use let , var and for constant Value const.

The var keyword is used in all JavaScript code from 1995 to 2015.

The let and const keywords were added to JavaScript in 2015.

If you want your code to run in older browsers, you must use var.

Variables defined with let cannot be Redeclared.

Variables defined with let must be Declared before use.

Variable defined with Var can be Redeclared and we can declare after using it.

```jsx

jsx
let x=5;
var y=15;
const p=4;
```

JavaScript is a popular programming language used for both frontend and backend web development. It has various data types, including String, Number, Boolean, Undefined, Null, Symbol, Object, and Bigint. Variables are used to store data and can be declared using the keywords let, var, and const. The if-else statement and switch statement are used for conditional statements, and the for loop and do-while loop are used for looping. JavaScript functions are defined with the function keyword, and objects are defined using object literals. Finally, HTML events are actions performed by the browser or user, such as a page loading or a button click.

- Data Types

There are 8 datatypes in JavaScript

1.String

1. Number
2. Bigint
3. Boolean
4. Undefined
5. Null
6. Symbol
7. Object
- Control flow statement(if/Else)
1. If/else statement

The if else statement is a conditional statement and the block of code only execute if the if condition is true .

```jsx
jsx
if (hour < 18) {
greeting = "Good day";
} else {
greeting = "Good evening";
}
```

if  there is another alternative method is there we use if-else-if statment

jsx
if (time < 10) {
greeting = "Good morning";
} else if (time < 20) {
greeting = "Good day";
} else {
greeting = "Good evening";
}

Switch statement is another type of conditional statement use the variable as parameter and the options with their block of code using case keyword and break keywork to terminate the checking if the case condition is satisfied.

jsx
switch (new Date().getDay()) {

case 0:

day = "Sunday";

break;

case 1:

day = "Monday";

break;

case 2:

day = "Tuesday";

break;

case 3:

day = "Wednesday";

break;

case 4:

day = "Thursday";

break;

case 5:

day = "Friday";

break;

case 6:

day = "Saturday";

}

- Loop

For loop:

jsx
for (let i = 0; i < 5; i++) {
text += "The number is " + i + "<br>";
}

- Do while loop

jsx
do {
text += "The number is " + i;
i++;
}
while (i < 10);

- Functions

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

jsx
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
return a * b;             // Function returns the product of a and b
}

- Objects

You define (and create) a JavaScript object with an object literal:

- Events

```jsx
jsx
const person = {
firstName: "John",
lastName: "Doe",
age: 50,
eyeColor: "blue"
};
```

An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

- An HTML web page has finished loading
- An HTML input field was changed
- An HTML button was clicked