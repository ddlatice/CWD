---
title: JS Variables + Scope. 🔍 
date: "2020-05-30T23:46:37.121Z"
description: "Thou Shalt Know the Fundamentals."
---

To begin programming in JS, one must know the fundamentals. This includes understanding the concepts of Variables and Scope. For awhile, when I first started reading about JavaScript I hadn't been familiar with the term "Scope" at all. Here I'm going to dive deeper in a laid back kinda way.

If you don't already know what a variable is, it is basically a container that holds a value. You declare a variable with a keyword and then you can put whatever value you want in it! As long as it's one of JavaScript's primitive or object data types.

Primitive types in JavaScript are:
* String
* Number
* Boolean
* Null
* Undefined
* Symbol

learn more about primitive types and objects [here:](https://javascript.info/types)
learn more about naming variables [here:](https://javascript.info/variables)

Much of understanding the relationship between variables and scope relies on the term 'Block', which is essentially a block of code 🥰

ex:
```
{
✨ block of code is between these cute curly braces✨
}
```

**Variable Scope** refers to the current accessibility of your declared variable. 

There are two kinds of Variable Scope:
* Global Variables: these are variables that you declare OUTSIDE a block of code.
* Local Variables: these are variables that you declare INSIDE a block of code.

...simple enough. let's continue.

In JS, you can declare variables using 3 top-dawg keywords : **var, let and const**. 
These keywords differ based on what scope they can be used in.
Keywords *let* and *const* can be used in Block Scope.
Keyword *var* can be used in Function Scope.

Here is the difference between the two types of Scope:

* Variables declared in function scope are defined inside a FUNCTION BLOCK.
a function block is a block of code within a function. These variables are NOT accessible outside of that function scope.

* Variables declared in block scope are defined inside of a block of code. these variables only exist within that block of code.

So bottom line is, bascially you can't just declare variables anywhere in your code using any old keyword and expect it to be accessible.

When writing code in JS, it is important to correctly use keywords and understand their scope, because this will allow you to manage the accessibilty of the variables you are using to make your program run!

Happy Learning Stuffs,
<br>
Dom.
