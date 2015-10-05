## Outline

### Topic -- writing media queries

Besides creating a responsive grid, writing the appropriate media queries for devices is the second part of responsive design. 

Media queries allow for the webpage to be sized proportionately to the size of the viewport. This simply means that webpage need to be able to scale to the screen size of that specific device. Furthermore, there are certain sizes we need to be comfortable before tackling the simple process of writing a media query. 

Common device sizes: 

320px
480px
600px
768px
900px
1200px


Thinking about what DOM elements or font need to be emphasized at certain sizes is a crucial step when styling for different device size.

Most developers will design for mobile first. When designing for mobile, we can use a min: 320px and a max of 768px; 

## Steps for Media Queries 

1. Decide which device you want to write a media query. Remember designing for mobile and then writing media queries for the next largest screen size may be an easier solution
2. `@media screen and (min-width: 320px) { /* properities you want to focus on or not focus on at this size */}`
3. Save and test your code in the broswer. My previous tutorial introduce a developer tool that could potentially help you with this
