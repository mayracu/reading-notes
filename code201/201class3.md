# Class 3: HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML: Ordered and Unordered lists

* When should you use an unordered list in your HTML document?

An unordered list is used when the order of the elements of the list is not meaningful.

* How do you change the bullet style of unordered list items?

The bullet style is not defined in the HTML document, but in its associated CSS, using the list-style-type property.

* When should you use an ordered list vs an unorder list in your HTML document?

The `<ol>` element should be used when grouping a collection of items that have a numerical ordering. The `<ul>` element should be used when the order of the list items is meaningless.

* Describe two ways you can change the numbers on list items provided by an ordered list?

The numbers on list items can be changed to a different type, i.e. Roman Numeral type or using the start attribute.

## CSS: The Box Model

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Padding is a character which main role in this story is to create some distance among Content and Margin. Margin and Content want to be together, but Padding and Border are always in the way.

### List and describe the four parts of an HTML elements box as referred to by the box model.

* Margin: The invisible space around the box.
* Border: The line between the margin and the padding of a box.
* Padding: It sits between the border and the content area.
* Content box: The area where the content is displayed.

## JavaScript: Arrays. Operators and Expressions. Conditionals. Loops

### What data types can you store inside of an Array?

An array can store various data types: strings, numbers, objects, and even other arrays.

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

``
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
``
The people array a is a valid JavaScript array that stores three arrays. The items can be accessed using bracket notation and supplying the item's index.

### List five shorthand operators for assignment in javascript and describe what they do

``
    Addition assignment: x += f() --> x = x + f()Substraction assignment: x -= f() --> x = x - f()
    Multiplication assignment: x *= f() --> x = x * f()
    Division assignment: x /= f() --> x = x / f()
    Remainder assignment: x %= f() --> x = x % f()
    Exponentiation assignment: x **= f() --> x = x ** f()
``

### Read the code below and evaluate the last expression and explain what the result would be and why

``
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;
``
The result is 10dog. The values in between the parenthesis are summed up first and the value of the variable b is added last. Since c is false, this means its value is 0.

### Describe a real world example of when a conditional statement should be used in a JavaScript program

When there is a speed limit set for a street, if a vehicles goes up the speed limit it receives a speeding ticket.

### Give an example of when a loop is useful in JavaScript

It can be useful to use a loop in JavaScript when we want to provide a welcoming message to everyone in a chat session.

## Things I want to know more about

Creating functions with JavaScript using loops and conditionals.

*References:*

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

[https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
