# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](../blog-preview-card/screenshots/Screenshot-desktop.png)
![](../blog-preview-card/screenshots/Screenshot-mobile.png)

### Links

- Solution URL: (https://github.com/Tainicknackz/blog-preview-card.git)
- Live Site URL: (https://joyful-florentine-5753c7.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- Mobile-first workflow

### What I learned

I explored with CSS's::after pseudo-element, which lets us to put extra content after an element's closing tag, allowing us to create unique effects and modifications.

To see how you can add code snippets, see below:

```css
.container::after {
  display: block;
  content: "";
  width: 320px;
  height: 501px;
  border: 1.5px solid hsl(0, 0%, 7%);
  position: absolute;
  top: 8px;
  left: 8px;
  z-index: -1;
}
```

### Continued development

- Responsiveness Breakpoints: Evaluate if additional breakpoints are necessary for optimal user experience across a wider range of screen sizes.
- Performance Optimization: Analyze and optimize the CSS code for efficient rendering, especially on mobile devices.
- Advanced CSS Features: Dive deeper into CSS Grid, Flexbox, and other advanced layout techniques for greater design flexibility.

## Author

- GitHub - [Tainicknackz](https://github.com/Tainicknackz)
- Frontend Mentor - [@Tainicknack00](https://www.frontendmentor.io/profile/Tainicknack0505)
