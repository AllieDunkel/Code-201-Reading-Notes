## Reading Assignment 9

### HTML Forms

1. Why are forms so important in web development?

- one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- the relationship
- the conversation  
- the appearance

3. List 5 form elements and explain their importance.

- The <fieldset> element is a convenient way to create groups of widgets that share the same purpose
- <legend> formally describes the purpose of the <fieldset>
-  <label> element is the formal way to define a label for an HTML
- it's common practice to wrap a label and its widget with a <li> element within a <ul> or <ol> list. <p> and <div> elements are also commonly used
- In addition to the <fieldset> element, it's also common practice to use HTML titles


### Learn JS

1. How would you describe events to a non-technical friend?

- events are actions or occurrences that happen in the system you are programming

2. When using the addEventListener() method, what 2 arguments will you need to provide?

- the name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.

3. Describe the event object. Why is the target within the event object useful?

- it is automatically passed to event handlers to provide extra features and information.

4. What is the difference between event bubbling and event capturing?

- Capturing: he browser checks to see if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase, and runs it if so. Then it moves on to the next element inside <html> and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.
- bubbling: The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so. Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the <html> element.

## Things I Want to Know More About