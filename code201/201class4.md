# Class 4: HTML Links, JS Functions, and Intro to CSS Layout

## HTML: Creating Hyperlinks

### To create a basic link, we wrap text or other content inside what element?

Inside an `<a>` element.

### The href attribute contains what information?

The href attribute contains the web address of a link.

### What are some ways we can ensure links on our pages are accessible to all readers?

- Including keywords in a link text to describe what is being linked to: this can help search engines to index target files.
- Descriptive link texts are useful when using visual readers to identify page features that stand out.

## CSS Layout: Normal Flow CSS Layout: Positioning

### What is meant by “normal flow”?

Normal flow is the default layout for CSS elements. We can change how elements behave either by adjusting their position in normal flow or by removing them from it.

### What are a few differences between block-level and inline elements?

- A block-level element's content fills the available inline space of the parent element containing it
- The size of inline-level elements is just the size of their content.
- By default, block-level elements are laid out in the block flow direction. Each element will appear on a new line below the last one, with each element separated by the margin that has been specified.
- Inline elements don't appear on new lines; instead, they all sit on the same line along with any adjacent text content as long as there is space for theme inside the width of the parent block level element. If there isn't space, then the overflowing content will move down to a new line.

### What is the default positioning for every html element?

- Static positioning

### Name a few advantages to using absolute positioning on an element

- Since an absolutely positioned element sits on its own layer separate from everything else, this means that we can create isolated UI features that don't interfere with the layout of other elements on the page like popup information boxes, control menus, rollover panels, and other UI features.

### What is a key difference between fixed positioning and absolute positioning?

- whereas absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), fixed positioning usually fixes an element in place relative to the visible portion of the viewport.

## JavaScript: Reusable Blocks of Code

### Describe the difference between a function declaration and a function invocation

When we create a function we are defining a function, but in order to use it later on in our code we have to invoke it.

### What is the difference between a parameter and an argument?

Function parameters are the names listed in the function declaration, whereas function arguments are the real values passed to and received by the function.

## Things I want to know more about

Write CSS code changing CSS normal flow layout.

*References:*

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

[https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

[https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)