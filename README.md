JavaScript Basics

Welcome to the JavaScript Basics repository! This repository serves as an introduction to JavaScript, a versatile and widely-used programming language primarily known for its role in web development.
Table of Contents

    Introduction
    Getting Started
    Variables and Data Types
    Operators
    Control Structures
    Functions
    Objects
    DOM Manipulation
    Events
    Conclusion
    Resources

Introduction

JavaScript allows developers to create interactive and dynamic web pages. This README provides an overview of JavaScript basics, serving as a starting point for beginners.
Getting Started
Setting Up

To start coding in JavaScript, you'll need a text editor and a web browser. Popular text editors include Visual Studio Code, Sublime Text, and Atom.
Basic Syntax

A basic JavaScript file can be included in an HTML document using the <script> tag:

html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>JavaScript Basics</title>
</head>
<body>
    <script src="script.js"></script>
</body>
</html>

Variables and Data Types
Variables

Variables store data values and can be declared using var, let, or const:

javascript

var name = "John";
let age = 25;
const isStudent = true;

Data Types

JavaScript supports various data types, including:

    String: "Hello, world!"
    Number: 42
    Boolean: true or false
    Null: null
    Undefined: undefined
    Object: { key: "value" }
    Array: [1, 2, 3]

Operators

Operators are used to perform operations on variables and values.
Arithmetic Operators

    Addition: +
    Subtraction: -
    Multiplication: *
    Division: /
    Modulus: %

Comparison Operators

    Equal to: ==
    Strict equal to: ===
    Not equal to: !=
    Greater than: >
    Less than: <

Logical Operators

    AND: &&
    OR: ||
    NOT: !

Control Structures
Conditional Statements

Conditional statements control the flow of the program based on conditions.

javascript

if (age > 18) {
    console.log("Adult");
} else {
    console.log("Not an adult");
}

Loops

Loops are used to execute a block of code repeatedly.

javascript

// For loop
for (let i = 0; i < 5; i++) {
    console.log(i);
}

// While loop
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}

Functions

Functions are reusable blocks of code that perform a specific task.

javascript

function greet(name) {
    return `Hello, ${name}!`;
}

console.log(greet("Alice"));

Objects

Objects are collections of key-value pairs.

javascript

const person = {
    name: "John",
    age: 30,
    greet: function() {
        console.log("Hello!");
    }
};

console.log(person.name);
person.greet();

DOM Manipulation

JavaScript can interact with the HTML and CSS of a web page through the Document Object Model (DOM).

javascript

const element = document.getElementById("myElement");
element.textContent = "Hello, World!";
element.style.color = "blue";

Events

JavaScript can respond to user interactions with events.

javascript

const button = document.getElementById("myButton");
button.addEventListener("click", function() {
    alert("Button clicked!");
});

Conclusion

This README has provided an overview of JavaScript basics, including variables, data types, operators, control structures, functions, objects, DOM manipulation, and events. These foundational concepts are essential for building dynamic and interactive web applications.
Resources

For further learning, consider exploring these resources:

    MDN Web Docs - JavaScript
    W3Schools - JavaScript Tutorial
    Eloquent JavaScript
    JavaScript.info

Happy coding!
