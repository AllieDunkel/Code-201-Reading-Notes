## Reading Assignment 11

### Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

- Ever since the early 2000's when we started to have bandwidth fast enough to support any kind of videos we could finally use them unlike before. Then the HTML5 came out which had <video> and <audio> elements and some shiny new JavaScript APIs for controlling them. 

2. Describe the use of the src and controls attributes in the <video> element.

- Src= Source of the video (just like for the <img> tag)
- Controls= Users must be able to control video and audio playback. You must either use the controls attribute to include the browsers own control interface or build your interface using the appropiate JavaScript API. 

3. Why is it important to have fallback content inside the <video> element?

- Because if the browsers accessing the page doesn't support the <video> element, you can provide a fallback for older browsers.

4. Write a very short story where <audio> and <video> are characters.

- The audio element works just like the <video> element, with a few small differences.
- The audio element doesn't support the width/height attribute, the visual component or the poster attriubte (no visual component)
- Other than those they are the same like lines and lemons

### A Complete Guide To Grid

1. How does Grid layout differ from Flex?

- Grid layout is a 2-dimensional grid-based layout system that completely changes the way we design user interfaces 
- Flexbox is also a great tool but its a one-dimensional flow has different use cases- and they work together quite well

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid item: The children of the grid container. 
- Grid line: The dividing lines that make up the structure of the grid. They can be either vertical or horizontal and reside on either sides of a row or column. 
- Grid container: The element on which display: grid is applied. Its the direct parent of all of the grid items.
 

### Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- So the webpage can look similar no matter what device it is being displayed/ viewed on

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

- srcset= defines the set of images we will allow the browser to choose between, and what size each image is
- sizes= defines a set of media conditions and indicate what image size would be best to choose 

3. How is srcset more helpful for responsive images than CSS or JavaScript?

- When the browser starts to load a page, it starts to download (preload) any images before the main parsar has started to load ans interpret the pages CSS and JavaScript. The mechanisms is useful in general for reducing page load times, but it is not helpful for responsive images

## Things I Want to Know More About