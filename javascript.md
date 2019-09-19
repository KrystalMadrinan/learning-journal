# Notes on Javascript thus far

### ***Javascript Reading 6 Notes***

- One of the main purposes of javascript is for page functionality - for example, pop ups!
- It's also responsible for interaction and animations.
- Basically things that move around. 
- It's written in plain text just like HTML and CSS.
- The extension for javascript is .js
- *Use the HTML `<script>` element when using JS with a webpage. The src attribute indicated where the JS file is stored.*

- You can set conditionals in Javascript. example:

`var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
    greeting = 'Good evening!';
} else if (hourNow > 12) {
    greeting = 'Good afternoon!';
} else if (hourNow > 0) {
    greeting = 'Good morning!';
} else {
    greeting = 'Welcome!';
}`

#### ***Helpful Resources***
- Lecture
- Javascript textbook pages 43-49