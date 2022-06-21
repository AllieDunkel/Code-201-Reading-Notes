## Reading Assignment 1 

1. Compose a short poem describing how HTTP sends data between computers.

- Step 1: The browser finds the website
- Step 2: The browser request a copy of the website
- Step 3: If the server approves the request you get to '200 ok' message and then sends the website small chunks called data packets  
- Step 4: The small chunks turns into a webpage

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

- Before anything is rendered to the screen, the HTML, CSS, and Javascript.
- 1st Step: Starts with the HTML (building the document tree)
- 2nd Step: Processes CSS and building the CSSOM tree. While this is happening, other assets, including Javascript files download.
- 3rd Step: Combines the DOM and CSSOM into a render tree
- 4th Step: The last step paints the individual nodes to the screen

3. How can you find images to add to a Website?

- You can go to Google Images to find something suitable or you can add a file from your computer 
- Google Images are copyright so you can use "Google license Filter".  Click on the tools button, then on the resulting usuage right option that appears below. You should choose the option creative commons licenses

4. How do you create a String vs a Number in JavaScript?

- String is enclosed by single quote marks
- Numbers do not have quotes

5. What is a Variable and why are they important in JavaScript?

- A variable are containers that store values
- They are important because you can change them and allow them to be reused
- Note that variables hold values that have different data types 

### Introduction to HTML

1. What is an HTML attribute?

- contains extra information about the element that wont appear in the content. For example, naming a class.

2. Describe the Anatomy of an HTMl element.

- Opening tag
- Closing tag
- Content 

3. What is the Difference between <article> and <section> element tags?

- <article> encloses a block of text that makes sense on its own
- <section> grouping together a single part of the page

4. What Elements does a “typical” website include?

- header
- navigation bar
- main content
- side bar
- footer

5. How does metadata influence Search Engine Optimization?

- Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines

6. How is the <meta> HTML tag used when specifying metadata?

- Metadata is the data that describes data. <meta> is the "offical" way to name the element 

### Designing a Website

1. What is the first step to designing a Website?

- Project ideation

2. What is the most important question to answer when designing a Website?

- "What exactly do I want to accomplish?"

### Semantics

1. Why should you use an <h1> element over a <span> element to display a top level heading?

- Using a <h1> element will give the element a semantic tag, along with all the benefits

2. What are the benefits of using semantic tags in our HTML?

- Search engines will consider its contents as important keywords to influence the pages search rankings 
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier then searching through endless divs
- Suggests to the developer the type of data will be populated 
- Semantic naming mirrors proper custom element/component naming 

### What is Javascript?

1. Describe 2 things that require JavaScript in the Browser?

- HTML and CSS

2. How can you add JavaScript to an HTML document?

- Similar to CSS
- Use <script> 
- External call file script.js and add <script src = "script.js" defer> </script>

## Things I Want to Know More About

- Does the Javascript have to be in the head tag?