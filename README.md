# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [How I did it](#how-i-did-it)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./design/active-states.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMlandingPageHuddle/)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMlandingPageHuddle/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS and CSS3
- CSS Flexbox & Grid

### How I did it

Only one svg is used for both logos. Used combined CSS filter method to convert logo from the color version to white one for the footer. Link to Barrett Sonntags Codepen tool below.

```scss
.footer-logo {
  filter: invert(94%) sepia(73%) saturate(3%) hue-rotate(104deg) brightness(
      200%
    ) contrast(100%);
}
```

### Useful resources

- [CSS filter generator](https://codepen.io/sosuke/pen/Pjoqqp) - CSS filter generator to convert from black to target hex color - Codepen Barrett Sonntag

## Author

- Ayula Boyilo
