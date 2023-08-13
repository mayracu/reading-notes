# Class 2: HTML, CSS and JavaScript

## Why is it important to use semantic elements in our HTML?

Semantic elements have semantic values and get extra benefits. Semantic elements are used as important keywords that can influence the pages's search rankings (SEO). Also, in terms of accessibility, semantic elements like headings are used by screen readers to allow their users to find the information they need on a website.

## How many levels of headings are there in HTML?

There are six levels of headings: h1, h2, h3, h4, h5, and h6.

## What are some uses for the `<sup>` and `<sub>` elements?

superscript and subscript elements are useful when marking up items like dates, chemical formulae, mathematical equations, etc. so they have the correct meaning.

``
  <p>
    Water's chemical formula is
    H<sub>2</sub>O
  </p>
``

## When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

A full expansion of the term can be provided using the title attribute.

## What are ways we can apply CSS to our HTML?

CSS can be applied to a document with an external stylesheet, with an internal stylesheet, and with inline styles.

## Why should we avoid using inline styles?

- Making styling changes can be tedious and time consuming within a single web page.
- Inline CSS mixes presentational code with HTML and content.

## Components of a CSS rule

``
     h2 {
     color: black;
     padding: 5px;
   }
``

- h2 is the selector
- `color: black;` is a CSS declaration
- `padding: 5px;` is a CSS declaration
- The content within {} is a CSS declaration block
- Properties identify the stylistic features to modify. Color and padding are the properties especified on this CSS rule.

## JavaScript

### What data type is a sequence of text enclosed in single quote marks?

Strings are enclosed in single or double quote marks.

### List 4 types of JavaScript operators

- Addition: `4+4`
- Substraction: `8-4`
- Division: `16/4`
- Multiplication: `8*8`

### Describe a real world problem you could solve with a function

To identify if a certain plant need to be watered or not  depending on the time of year, previous date it was wareted, etc.

### Conditionals

- An if statement checks a condition and if it evaluates to TRUE, then the code block will execute.

- What is the use of an else if?: else if is used when there are two or more conditions to test.

#### Types of comparison operators.

- === and !== — test if one value is strictly identical to, or not strictly identical to another
- < and > — test if one value is less than or greater than another
- <= and >= — test if one value is less than or equal to, or greater than or equal to, another.

#### Difference between the logical operator && and ||?

- && — AND; chain together two or more expressions. All the expressions have to individually evaluate to true for the whole expression to return true.
- \|\| — OR; chain together two or more expressions. At least one expression have to individually evaluate to true for the whole expression to return true.

## Things I want to know more about

Building functions using JavaScript.

*References:*

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

[https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

[https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
