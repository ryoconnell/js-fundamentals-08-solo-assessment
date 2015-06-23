![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Assessment for JavaScript Fundamentals

You have 20 minutes

## Instructions

Fork, clone, and npm install.

Follow the prompts below and complete each question.  You may use any resource, other than someone else in the classroom, to help you complete this assessment.

You should save your answers in this README.md file.

# Question 1

```js
var a = 2;
var b = 3;
a = b;
```


After this code executes, what are the values of a and b? Please explain your answer.

a and b are 3.  the variable on the right evaluates to the variable on the left.  if b = 2 and a = 3, then both would be 2.

## Question 2

```js
var c = 5;
var d = 2;
c = c + d;
```

After this code executes, what is the value of c?  Please explain what the last line of this program `c = c + d;` means.

c = 7.  the variable c can change.  it has a new value after adding 5 and 2...it isn't constant.

## Question 3

```js
var x = 4;
var y = 3;
x = y;
y = 10;
```

After this code executes, what are the values of x and y?  Please explain your answer.

<!-- Replace this comment with your answer -->
x = 3, y = 10.  x changes to y's value of 3.  y then changes to the new value of 10.
## Question 4

```js
var weather;
weather = "sunny";
weather === "sunny";
```

What are the values of these expressions?  Explain your answers.

<!-- Replace this comment with your answer -->
weather = true.  the === asks if weather is the same as the variable.  both are true.
## Question 5

```js
var howMuchILikeSushi = 2;

if (howMuchILikeSushi >= 3) {
  console.log("sushi is delicious");
}

if (x > 0) {
  console.log("sushi is tasty");
}
```

Imagine that you take the code from this question, save it to a file called `food.js`, and run `node food.js` in your Terminal.

What would be the output? Explain your answer.
neither statement would show.  2 isn't greater than 3, so the delicious wouldn't appear.  x isn't defined, so that statement would appear.  It would be a default.
<!-- Replace this comment with your answer -->

## Question 6

```js
var howMuchILikeSushi = 2;

if (howMuchILikeSushi > 0) {
  console.log("sushi is tasty");
} else if (x >= 3) {
  console.log("sushi is delicious");
} else {
  console.log("I don't like sushi");
}
```

Imagine that you take the code from this question, save it to a file called `sushi.js`, and run `node sushi.js` in your Terminal.

What would be the output? Explain your answer.

"sushi is tasty" the var is higher than 0, so it would be complete and wouldn't continue to the else if, and the I don't like sushi would appear if the var is assigned something that isn't >0 or >= 3.<!-- Replace this comment with your answer -->

## Question 7

```js
//We'll learn about require later in the course
var ask = require('./ask.js');

var answer = 'not empty';

while (answer !== '' && answer !== 'SeCrEt') {
  answer = ask("Guess my secret? ");
}
```

Imagine that you take the code from this question, save it to a file called `name.js`, and run `node name.js` in your Terminal.

What would you have to type to exit the while loop?  Explain your answer.


<!-- Replace this comment with your answer -->


---

Commit and push your changes.

Submit a pull request.
