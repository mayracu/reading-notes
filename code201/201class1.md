# How the web works

There are many elements that take part in the process of connecting to the internet and access a website. The main elements involved are the following:

- Clients and servers
- Clients internet connection
- TCP/IP: Transmission Control Protocol and Internet Protocol. These are communication protocols that define the way data travels across the internet. 
- DNS: Domain Name System (web address)
- HTTP: Hyper Text Tranfer Protocol. Defines a language for clients and servers to speak to each other.
- Component files: code files, assets.

## How HTTP sends data between computers

When you type a web address into your browser
the browser goes to the DNS server
and using TCP/IP protocols
an HTTP request message is sent

When the server approves
the client request
it likes to reply "200 OK"
then data packets are sent to your browser
and just like magic the website is built!

## How HTML/CSS/Javascript files are parsed in the browser?

Order in which files are parsed in the broswer:

1. HTML files are parsed first. This allows the browser to recognize any `<link>` element references to external CSS files and any `<script>` element references to scripts.
2. CSS and Javascript files are parsed by the browser.
3. The browser creates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
4. The visual representation of the website is shown on the user's screen.

## How to find images to add to a website

[Google Images](https://www.google.com/imghp?gws_rd=ssl) is a useful tool to choose images. It's recommendable to review the licensing requirements and choose images with Creative Commons licenses.

## How to create a String or a Number in JavaScript?

- To signify that a specific value is a string, it should be enclosed in single or double quote marks.
``
  let myVariable = 'car'; or
  let myVariable = "car";
``
- To signify that a specific value is a number, don't use quotes  around it.

## Why are variables important in Javascript?

Variables are containers that store values. Values of variables can be changed and that's what makes Javascript dynamic.

## HTML

### Anatomy of an HTML element

An HTML element contains an opening tag, content, and a closing tag.

### What is an HTML attribute?

Attributes contain extra information about the html elements that won't appear in the content. Attributes should have an attribute value wrapped with opening and closing quote marks.

### What is the difference between `<article>` and `<section>` element tags?

A`<article>` encloses a block of related content that makes sense on its own.

`<section>` is similar to `<article>`, but it's usually used for grouping together a single part of the page that possess one single piece of functionality.

### What elements does a typical website include?

- header: `<header>`
- navigation bar: `<nav>`
- main content: `<main>`
- subsections:`<article>`, `<section>`, and `<div>` elements.
- sidebar: `<aside>`(often placed inside `<main>`).
footer: `<footer>`

### How does metadata influence Search Engine Optimization?

Specifying a description in the metadata section that includes keywords relating to the content of the website can improve the performance of the page in search engines, making the page appear higuer in the list of results.

### How is the `<meta>` HTML tag used when specifying metadata?

- Many `<meta>` elements include name and content attributes.
- the name attribute specifies what type of information it contains.
- the content attribute specifies the meta content, e.g. `<meta name="author" content="John Doe" />`

## How to start to design a website

### What is the first step to designing a Website?

Project ideation! It is important to answer the following questions:

- What exactly do I want to accomplish? (This is the most important questions. The answer to this question will help to prioritize a list of goals).
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

## Semantics

### Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

The h1 element is a semantic element, which gives the text it wraps around the role of a top level heading.

### What are the benefits of using semantic tags in our HTML?

- Search engines will consider the content of semantic tags as important keywords and that will have an impact on the page's search rankings.

- For accessibility reasons: Screen readers can use the content of semantic tags as markers to help visually impaired users navigate a website.

- It helps developers to find blocks of meaningful code.

## What is JavaScript?

JavaScript is a scripting language that enables the creation of dynamic and interactive websites.

### Describe 2 things that require JavaScript in the Browser?

Browser APIs and Third party APIs.

### How can you add JavaScript to an HTML document?

JavaScript can be added to an HTML document using an external file or using JavaScript internally in the HTML file.

## Things I want to know more about

I'd like to know more about APIs and Third Party APIs.

*References:*

[https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

[https://developer.mozilla.org/en-US/docs/Glossary/Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
