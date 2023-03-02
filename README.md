# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

In this project my three biggest challenges were making making the page responsive, making the CIRCLE in the results,
and making text next to each other different colors and styles. I would say I did somewhat do those things successfully, 
but it feels like it wasn't the most optimal solution. However, I am still proud of the results. I really learned that I don't
know what tag to use sometimes. If I was to add little amounts of text such as "70" do I add a <p> tag or something else?

  CIRCLE EXAMPLE:
.actualresult {
    background-image: linear-gradient(hsla(256, 72%, 46%, 1), hsla(241, 72%, 46%, 0));
    width: 10rem;
    display: inline-block;
    border-radius: 100%;
    line-height: 0%;
    padding-bottom: 2rem;
    padding-top: 1rem;
}
  The positioning of this in the page was very difficult for me until I used inline-block on it, still not fully understanding it. 

  DIFFERENT COLOR/STYLE:
<p>92 <span class="outof">/ 100</span></p>
  This was the way I split the text so that I could style different text in a <p> differently but im not sure if this is correct.

  RESPONSIVE:
@media (max-width: 575px) {
    .resultandsummary {
        display: block;
    }
}
  This query was the only responsive part of my page. I'm still not comfortable using queries and I would like to dive more into min and max and things like that.


### Continued development

This is one of my very first little projects. After working on it, I am much more aware of what I need to focus on. I want to keep making projects like these that are HTML and CSS focused until I feel more comfortable with it. Then once I feel like I have a good grasp of these languages I want to start implementing JS and working on more complex projects.

### Useful resources

- [Resource 1](https://developer.mozilla.org/) - This was more useful for broad questions such as certain properties I can target.
- [Resource 2](https://stackoverflow.com/) - Stack Overflow was probably the most useful resource for more specific questions and looking at examples.
- [Resource 3](https://codecademy.com) - All of my prior knowledge came from Codecademy.
- [Resource 3](https://www.youtube.com/@KevinPowell) - This youtube channel is the best channel for learning anything CSS related.

## Author

- Frontend Mentor - [@michaelcgre](https://www.frontendmentor.io/profile/michaelcgre)