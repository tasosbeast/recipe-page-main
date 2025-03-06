# Frontend Mentor - Recipe Page Solution

This is a solution to the [Recipe Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![First Screenshot](./Screenshot%202025-03-06%20215318.png)

![Second Screenshot](./Screenshot%202025-03-06%20215338.png)

### Links

- Solution URL: [https://github.com/tasos/recipe-page-main](https://github.com/tasosbeast/recipe-page-main)
- Live Site URL: [https://recipe-page-tasosbeast.netlify.app/](https://recipe-page-tasosbeast.netlify.app/)

## My process

### Built with

- HTML5
- CSS Custom Properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to create a reusable flow utility class that helps manage consistent vertical spacing between elements. This pattern is also known as "Stack" layout in some methodologies.

```css
.flow > * + * {
  margin-top: var(--flow-space, var(--space-300));
}
```

This CSS creates consistent spacing between elements:

- Uses the lobotomized owl selector (> _ + _)
- Allows custom spacing with --flow-space
- Falls back to default --space-300 if not specified

### Continued development

I plan to incorporate JavaScript to add interactivity and further optimize the responsive design of the site.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org) - Quick reference and documentation.
- [W3Schools](https://www.w3schools.com) - Basic examples and tutorials.

```

```
