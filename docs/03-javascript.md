#programming #teaching

# Javascript (JS)

#### Content
JavaScript is a very powerful **client-side scripting language***. JavaScript is used mainly for enhancing the interaction of a user with the webpage. In other words, you can make your webpage more lively and interactive, with the help of JavaScript. JavaScript is also being used widely in game development and [Mobile](https://www.guru99.com/mobile-testing.html) 
application development.

- Javascript runs on the browser, it cannot be run on its own (V8). Modern JS can also be run on a ser.
- ***** Before was called scripting language, but now it can stand as a full programming language.
- Every browser comes with JS installed.
- JavaScript is case sensitive.

---

#### Variables
Variables are used to **store values** (name = "Euge") **or expressions** (sum = x + y). Naming variables with descriptive and meaningful names, it is a good programming practice.
- how to declare a variable?
- how to assign a value to a variable?
- how to use a variable?

[String](https://developer.mozilla.org/en-US/docs/Glossary/String)

This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks.

`let myVariable = 'Bob';`

[Number](https://developer.mozilla.org/en-US/docs/Glossary/Number)

This is a number. Numbers don't have quotes around them.

`let myVariable = 10;`

[Boolean](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

This is a True/False value. The words `true` and `false` are special keywords that don't need quote marks.

`let myVariable = true;`

[Array](https://developer.mozilla.org/en-US/docs/Glossary/array)

This is a structure that allows you to store multiple values in a single reference.

`let myVariable = [1,'Bob','Steve',10];`  
Refer to each member of the array like this:  
`myVariable[0]`, `myVariable[1]`, etc.

[Object](https://developer.mozilla.org/en-US/docs/Glossary/Object)

This can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn.

`let myVariable = document.querySelector('h1');`  

All of the above examples too.

---
#### Operators
An `[operator](https://developer.mozilla.org/en-US/docs/Glossary/Operator)` is a mathematical symbol that produces a result based on two values (or variables).

Addition

Add two numbers together or combine two strings.

`+`

`6 + 9;  
'Hello ' + 'world!';`

Subtraction, Multiplication, Division

These do what you'd expect them to do in basic math.

`-`, `*`, `/`

`9 - 3;  
8 * 2; // multiply in JS is an asterisk  
9 / 3;`

Assignment

As you've seen already: this assigns a value to a variable.

`=`

`let myVariable = 'Bob';`

Equality

This performs a test to see if two values are equal. It returns a `true`/`false` (Boolean) result.

`===`

`let myVariable = 3;  
myVariable === 4;`

Not, Does-not-equal

This returns the logically opposite value of what it precedes. It turns a `true` into a `false`, etc.. When it is used alongside the Equality operator, the negation operator tests whether two values are _not_ equal.

`!`, `!==`

For "Not", the basic expression is `true`, but the comparison returns `false` because we negate it:

`let myVariable = 3;  
!(myVariable === 3);`

---
#### Objects
[Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object) refers to a data structure containing data and instructions for working with the data. Objects sometimes refer to real-world things, for example a `car` or `map` object in a racing game.


#### How to show a message in the browser?
Using `alert()`

#### How to show a message in the browser console?
Using `console.log()` will display a message in the console log of the browser.
- what is the browser console?
- how to access the browser console?

#### Where does the code need to go?
Using `<script type="text/javascript">
</script>` tags inside the HTML file, as internal scripting or using its own file `script.js` as external scripting.


#### Resources
- [Javascript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Hello World](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)

#### Common parts of JS
- DOM
- Functions
	- Parameters and Arguments
- Data types
	- Array
	- Objects
	- String
	- Integer
	- null and undefined
	- Booleans
- Conditional Statements
- Loops Statements
