---
layout: essay
type: essay
title: "Professionals Have (Coding) Standards"
# All dates must be YYYY-MM-DD format!
date: 2026-09-27
published: false
labels:
  - ESLint
---

## Coding Standards: How Important Are They?

Coding standards are rules/guidelines on how code is written and structed. The purpose of coding standards is that it helps with consistensity, maintainability, and readability, making it easier for others to understand the code you write. It also helps detect errors. These factors will help with efficient software development. 

An example of a common coding practice is naming variables and functions clearly.

Here's an example of a function with an unclear name:
function foo(a) {
    return a + 2;
}

Even if the name is unclear, it's easy to see what the function does. However, if the function was more complex, it'll be a bit harder to see what it does. 

Here's the same function with a more specific name:
function addTwo(value) {
    return value + 2;
}

The name of the function helps explain what it does. Properly naming variables can also help keep track on what it is. 


## My Experience with ESLint

The only rule I understood was proper indentation, where it makes code more neat and readable. ESLint also informs you on whether a variable or function is used or not. I didn’t understand the purpose of the new line at the end of the file and using single quotes. 

ESLint feels similar to the Checkstype Plugin in Eclipse IDE. I remember that the rule I had to fix the most was indentation. 

I did some research on why the rules I was confused about exist. I read on the official website that it’s useful for string style consistency and the rule can be disabled. The rule can also be changed to use double and backtick quotes instead. 


