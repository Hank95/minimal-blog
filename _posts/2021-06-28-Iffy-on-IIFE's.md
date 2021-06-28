---
title: "Iffy on IIFE's"
categories:
  - JavaScript
tags:
  - JS
  - IIFE
  - Closures
---

An IIFE, Immediatly Invoked Function Expression, or “self-executing anonymous function” is exactly that, a function in Javascript that is invoked as soon as it it defined. Here is how and why ...

Lets make sure everyone is on the same page and start with some regular old function.

```javascript
function sayHello(name) {
  console.log(`Howdy ${name}`);
}
sayHello("Gerorge"); // Console logs "Howdy George"
```

This is a standard operation proceedure, this is a function decleration. We can declare a function then call it where we like in our code.
