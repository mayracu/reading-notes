# Class 9: Forms and JS Events

## HTML Forms

### Why are forms so important in web development?

- Web forms are one of the main points of interaction between a user and a website or application.
- They allow users to enter data, which then can be sent to a web server for processing and storage, or used on the client-side to update the user interface.

### When designing a form, what are some key things to keep in mind when it comes to user experience?

- The bigger your form, the more you risk frustrating people and losing users.
- Ask only for the data you absolutely need.

### List 5 form elements and explain their importance

- `<fieldset>`: it is used to group several controls as well as labels (`<label>`) within a web form.
- `<legend>`: represents a caption for the content of its parent `<fieldset>`
- `<label>`: represents a caption for an item in the form.
- `<input>`: it's used to create interactive controls for web-based forms in order to accept data from the user.
- `<button>`: allows the user to send, or "submit", their data once they have filled out the form.

## Javascript: Events

### How would you describe events to a non-technical friend?

Events are things that happen in the system we are programming. The system sends a signal that a certain event happened so that the program can react to the event.

### When using the addEventListener() method, what 2 arguments will you need to provide?

objects that can fire events have an addEventListener() method.
This method needs two arguments: one is the event that we want to listen, and the other one is a function to call when the event happens.

### Describe the event object. Why is the target within the event object useful?

The target property of the event object references the element the event occurred upon.

### What is the difference between event bubbling and event capturing?

Event capturing is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.

## Things I want to learn more about

I'd like to build more forms and tables using JS.

*References*

[https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

[https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[https://developer.mozilla.org/en-US/docs/Web/Events](https://developer.mozilla.org/en-US/docs/Web/Events)
