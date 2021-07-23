# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 
 
.map runs through each elements in the array and returns a new array as the result of calling a provided function on each element. it is used to manipulating and reshape data.
.filter loops through each item and return a new array of the elements that satisfied given condition(s). If the condition is not met, the current item will be skipped. it is used to filter out what are not needed based on conditions.
.reduce helps manipulate and reshape data into a single value. It takes a callback known as reduce function. the function takes a previous value and a next value (accumulator and current value) and accumulate the values through each looping, starting with a starting point (for example. 0).


2. Explain the difference between a callback and a higher order function.

A higher order function is a function that receives another function as its parameter and returns a function.
A callback is used as a parameter for another function called higher order function.


3. Explain what a closure is.

A closure is the combination of a function bundled together with references to the surrounding environment. A closure gives the ability for an inner function to access variables and parameters of the outter function's scope.


4. Describe the four principles of the 'this' keyword.

-First principles is global binding. When none of the other rules apply, THIS refers to the global object which is window or console in node, and it's undefined in strict mode.
-Second is implicit binding - When a function is invoked, THIS refers to the object on the left side of the preceeding dot.
-Third is new binding - Keyword NEW is used to construct a new object. When a function as a constructor function is invoked, THIS refers to the objects newly created.
-Fourth is explicit binding - Usually three cases occur: 
1. 'call'keyword is used: call invokes a function immidiately and specifies the context in which the function is invoked by passing in arguments one by one. THIS refers to that context.
2.  'bind'keyword is used: it is exactly like CALL but invokes the function later.
3. 'apply' keyword is used: its exactly like CALL but you can pass in a single array as the agrument.


5. Why do we need super() in an extended class?

- SUPER keyword refers the parent classs. It is used to call the constructor of the parent class in order to be able to access all the properties and methods that the parent class has.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

