# Class 7: Object-Oriented Programming, HTML Tables

## Domain Modeling

### Why do we need domain modeling?

Domain modeling allows developers to tackle a problem in code that requires to describe various entities, attributes, and constraints; commonly using an object-oriented model.

## HTML Table Basics

### Why should tables not be used for page layouts?

- Layout tables reduce accessibility for visually impaired users when using screen readers.
- Tables produce tag soup (code get harder to read, write, maintain and debug).
- Tables are not automatically responsive (tables are sized according to their content by default).

### List and describe 3 different semantic HTML elements used in an HTML `<table>`

- `<td>` element: "td" stands for "table data"
- `<tr>` element: "tr" stands for "table row"
- `<th>` element: "th" stands for "table header"

## Introducing Constructors

### What is a constructor and what are some advantages to using it?

Constructors allow us to define the set of methods and the properties an object can have, and then create as many objects as we like. We just will need to update the values for the properties that are different. This is very useful when we need to create various objects.

### How does the term `this` differ when used in an object literal versus when used in a constructor?

When used in an object literal the term `this` refers to a property of the object referenced. On the other hand, when used in a constructor the term `this` binds to a property of each object contained inside the constructor.

## Object prototypes using a constructor

### Explain prototypes and inheritance via an analogy from your previous work experience

Prototypes allow developers to share methods across all instances of a function.

Analogy: At a university, there is a curriculum that defines the basic structure, properties and behaviors that all the graduates should have. This is similar to a JavaScript prototype.

There are various careers and diplomas offered by this university. Each of these diplomas inherit the basic curriculum from the generic prototype but also add their own specialized features and behaviors.

## Things I want to know more about

Constructors and classes.

*References*

[https://github.com/codefellows/domain_modeling#domain-modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

[https://ui.dev/beginners-guide-to-javascript-prototype](https://ui.dev/beginners-guide-to-javascript-prototype)

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)