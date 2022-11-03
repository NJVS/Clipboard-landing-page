# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

<table>
  <tr>
    <td valign="top">
        <img src="./assets/design/ssDesktop.png">
    </td>
    <td valign="top">
        <img src="./assets/design/ssMobile.png">
    </td>
  </tr>
</table>

### Links

- [Live Demo](https://njvs.github.io/Clipboard-landing-page/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- [SASS/SCSS](https://sass-lang.com) - CSS preprocessor
- Flexbox
- CSS Grid
- Responsive Web Design

### What I learned

(My English is bad. Sorry in advance.)

A very simple and straight-forward landing page, nothing much to say but there's something that piqued my interest, The navigation bars inside the footer are arranged from top to bottom, then wrap to the left, instead of left to right, then wrap down. 

My initial solution for this is to use flex -> column -> wrap, but to automatically wrap the elements, the the height of the parent element must be set. Tho this works, I still need to set a height or max-height on the parent element for each breakpoints. 

But what I want is to auto-wrap the elements like in Flex without setting the height of the parent element. I know that Flex columns work fine, but I just want the height of the footer to be auto-adjusted. 

I just want to ask the community if there's another way to do this.

Here's what I've done: (It works but tbh I don't truly get it LOL)
```css
ul.footer-nav {
    column: 4 180px;
}
```

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [columns CSS Propery](https://developer.mozilla.org/en-US/docs/Web/CSS/columns)
- [An opinionated styleguide for writing sane, maintainable and scalable Sass.](https://sass-guidelin.es/)