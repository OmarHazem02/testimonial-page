# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

This project is a solution to the Frontend Mentor Testimonials Grid Section Challenge.
It demonstrates the use of semantic HTML, CSS Grid layout, and responsive design principles to create a visually appealing testimonial section.

### The challenge

The main challenge was using CSS grid to make the layout

### Screenshot

![webpage screenshot](webpage-screenshot.jpg)


### Links

- Live Site URL: [Testimonial-site](https://omarhazem02.github.io/testimonial-page/)

## My process

I began by structuring the testimonials with semantic HTML5 elements, ensuring that each testimonial had a consistent markup pattern.
Once the structure was complete, I implemented CSS Grid to arrange the testimonials into a visually balanced layout.
I then customized each card with unique background colors, border styles, and box shadows to give depth and personality to the design.
Special attention was given to responsive behavior, ensuring that the grid adapts smoothly to various screen sizes.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid



### What I learned

This project helped me deepen my understanding of CSS Grid and how grid-column and grid-row can be used to create complex, magazine-style layouts.
I also learned how to:

  . Apply different styles to elements using targeted classes and background images

  . Create circular profile images using border-radius: 50%

  . Use box shadows to add subtle depth without overwhelming the design
  
  . Manage consistent spacing between elements using the gap property in Grid

  . Control element order in a grid layout using the order property


```html
<article class="container">
  <article class="testimonial-daniel">...</article>
  <article class="testimonial-jonathan">...</article>
  <article class="testimonial-jeanette">...</article>
  <article class="testimonial-patrick">...</article>
  <article class="testimonial-kira">...</article>
</article>

```
```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 30px;
}

.testimonial-daniel {
  grid-column: span 2;
}

.testimonial-kira {
  grid-row: span 2;
}

.testimonial-patrick {
  grid-column: span 2;
}

```

### Continued development
To continue learning css gird to make it easier to build layouts like this 

### Useful resources

- MDN Web Docs helped me expand my knowledge on certain topics while creating this page..
- Chat GPT and Claude supported me as  mentors by helping evaluate and review my code throughout the project.

## Author

- Website - [Omar Hazem](https://www.linkedin.com/in/omar-hazem-aa287a273/)
- Twitter - [@Omarhaz67778375](https://x.com/OmarHaz67778375)


## Acknowledgments

I would like to acknowledge AlMadersa, where I am currently studying in the Front-End Development Diploma program. Special thanks to my course tutor, Mohamed Abu Sarea (محمد أبو سريع), for his valuable guidance and support.
