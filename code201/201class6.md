# Class 6: Problem Domain, Objects, and the DOM

## JavaScript Object Basics

### How would you describe an object to a non-technical friend you grew up with?

An object stores key-value pairs in an organized way. These key-values are organized like a collection of objects or records.

### What are some advantages to creating object literals?

It saves us time to create object literals when we want to create structured data.

### How do objects differ from arrays?

An object stores key-values whereas an array stores individual items.

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

We would need to use bracket notation when we want to link a property's name to a variable value.

### Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

```
const dog = {
  name: 'Spot',
  age: 2,
  olor: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

The term this refers to the values of the properties called name and age. The this keyword enables us to use the same method definition for every object we create.

## Introduction To The DOM

### What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents.

### Briefly describe the relationship between the DOM and JavaScript

JavaScript uses the DOM to access the document and its elements.

*References*

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

[https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

[https://simpleprogrammer.com/solving-problems-breaking-it-down/](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

[https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b?gi=0f951d0297cd](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b?gi=0f951d0297cd)
