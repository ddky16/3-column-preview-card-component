# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

- Desktop View
  ![Desktop View](/3-column%20preview%20card%20component%20Snapshot%20desktop%20view.png)
- Mobile View
  ![Mobile View](/3-column%20preview%20card%20component%20Snapshot%20mobile%20view.png)

### Links

- Solution URL: [Solution URL here](https://github.com/ddky16/3-column-preview-card-component)
- Live Site URL: [Live site URL here](https://bucolic-genie-6cefeb.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this challenge i learn a new things about the list item property in CSS i can select every single items on list with pseudo selector called nth-child() who stand for n'th child on list. the n value refer to the n list number property on the unordered list

```css
li:nth-child(1) {
  background-color: var(--color-bright-orange);
}

li:nth-child(1) a {
  color: var(--color-bright-orange);
}

li:nth-child(1) a:hover {
  background-color: var(--color-bright-orange);
  color: var(--color-light-gray);
}

li:nth-child(2) {
  background-color: var(--color-dark-cyan);
}

li:nth-child(2) a {
  color: var(--color-dark-cyan);
}

li:nth-child(2) a:hover {
  background-color: var(--color-dark-cyan);
  color: var(--color-light-gray);
}

li:nth-child(3) {
  background-color: var(--color-very-dark-cyan);
}

li:nth-child(3) a {
  color: var(--color-very-dark-cyan);
}

li:nth-child(3) a:hover {
  background-color: var(--color-very-dark-cyan);
  color: var(--color-light-gray);
}
```

## Author

- Frontend Mentor - [@ddky16](https://www.frontendmentor.io/profile/ddky16)
- Twitter - [@code_ddky](https://twitter.com/code_ddky)
