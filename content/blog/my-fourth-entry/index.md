---
title: FUNctions in JS. ✨
date: "2020-06-30T23:46:37.121Z"
description: "Making Stuff Work."
---

Ok so JavaScript really puts the FUN in functions. Why? Because functions hold all of the magic. A function is a group of statements in your JS code that perform a specific task.They are bundled together, as to not be disturbed or altered by the main program. They’re cool because you can make them perform any task you like… also they’re reusable and easy to debug.

**How We Define Functions.**

Let’s say in your JS script you want to construct a customized greeting as an alert. It’s time to define a function.

Your **Function Declaration** has to begin with the <code>function</code> keyword, followed by the name of the function you’re creating. Then, you want to add your () and curly braces {}. Between these curly braces, you’re going to write your instructions.

```

function myGreeting() {
     alert("Hiya ");
}

```

To get your function to actually do something, you want to <i>call</i> the function, also called <i>invoking</i> the function. Think of calling a function similar to calling your friend to come pick you up. Your friend’s function is to pick you up… but they can’t pick you up if you don’t call them first!

Let’s say you want your greeting to include someone’s name. Maybe your own. This is where _parameters_ come in. Parameters are information that you provide your function. When you define a parameter, it needs to be “passed” as an argument when the function is called. Like this:

```

function myGreeting(name) {
     alert("Hiya " + name); // output will be: Hiya Dominique!
}

myGreeting('Dominique!'); //your function call with your name as an argument.

```

You can also return values from a function. This is called creating a return statement. This is placed on the last line of your function. Like this:

```

function myFunction(num1, num2) {
  return num1 * num2;   // returns the product of num 1 and 2.
}

alert(myFunction(3,4)); // alert will show result of 12.

```

The catch is, a function can only return one value. However, you could return an array.

**Function Declaration vs Function Expression.**

A Function Declaration uses the syntax of:

```
function declaration (num1, num2) {
  return num1 + num2;
}

```

A Function Expression uses the syntax of:

```
let myExpression = function() {
   console.log('expression');
};

```

The difference between function declarations and function expressions are that function declarations are HOISTED to the top of its enclosing scope or global scope. This means that they are parsed or interpreted before the program runs. Invoking a function declaration before it is defined will not throw an error. Function expressions are only evaluated when it is assigned to a variable (when the interpreter gets to that line in the code). You can only invoke a function expression after it has been defined.

In JavaScript ES6, function expressions are shorter and sweeter, because they can be written as arrow functions. Like this:

```
var sum = (num1, num2) => num1 + num2;
console.log(sum(100, 50)); // result is 150.

```

Functions are super essential building blocks. The more you write them, the more you love them. Thats just my opinion, though.

Happy Coding Functions and Stuff,
<br>
Dom
