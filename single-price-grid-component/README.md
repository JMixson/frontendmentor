# Frontend Mentor - Single price grid component solution

![Design preview](./design/desktop-preview.jpg)

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshots

|          Desktop Version           |          Mobile Version          |
| :--------------------------------: | :------------------------------: |
| ![desktop screenshot](desktop.png) | ![mobile screenshot](mobile.png) |

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/price-grid-using-css-grid-rtHSLUynV](https://www.frontendmentor.io/solutions/price-grid-using-css-grid-rtHSLUynV)
- Live Site URL: [https://jmixson-single-price-grid-component.netlify.app/](https://jmixson-single-price-grid-component.netlify.app/)

## My process

### Built with

- HTML5
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow

### What I learned

I learned when to use the `grid-column` property and that a column amount or width doesn't need to be explicitly stated for it to work. For the layout, I first tried using grid areas but realized I would need to tweak my HTML. That solution was also more complicated than what I needed. Using `grid-column` and spanning two columns for the first area ended up working better for me.

I also learned the shorthand of `border-radius`. It differs from the box-model, so it took a little getting used to, but was more simple than I imagined.

### Continued development

I plan to improve my knowledge of CSS Grid. It has several properties, so it's difficult to know what each one does and when it's best to use them. I'm also curious on whether or not using flexbox would be easier and/or if I would need to rewrite any HTML.

### Useful resources

- [Box-Shadow CSS Generator](https://html-css-js.com/css/generator/box-shadow/) - This is a CSS box-shadow generated. It helped me visualize how each value of a box-shadow affects the outcome.

## Author

- Website - [https://jasminemixson.com/](https://jasminemixson.com/)
- Frontend Mentor - [@JMixson](https://www.frontendmentor.io/profile/jmixson)
- Github - [@JMixson](https://www.github.com/jmixson)

## Acknowledgments

- [Normalize.css](https://necolas.github.io/normalize.css/) - A CSS reset file that improves cross-browser consistency.
- [Box Sizing | CSS-Tricks](https://css-tricks.com/box-sizing/) - This article explains what the `box-sizing` property is and how to implement. I use the vendor prefixes for better sizing.
