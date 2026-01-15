# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Meet landing page solution](#frontend-mentor---meet-landing-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Mobile Screenshot](./mobile-screenshot.jpg)
![Tablet Screenshot](./tablet-screenshot.jpg)
![Desktop Screenshot](./desktop-screenshot.jpg)

### Links

- Solution URL: [https://github.com/ChechiX/meet-landing-page](https://github.com/ChechiX/meet-landing-page)
- Live Site URL: [https://chechix.github.io/meet-landing-page/](https://chechix.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/)

### What I learned

This time I learned that to do what's in step 2 I could use grid and z-index to overlap one element with another.

```scss
.footer {
  display: grid;
  justify-items: center;

  .step {
    grid-row: 2 / 4;
    grid-column: 1;
    z-index: 5;
  }

  .footer__content {
    grid-row: 3 / 5;
    grid-column: 1;
    width: 100%;
  }
}
```

### Continued development

I feel I still need to improve in the area of ​​identifying what I could use when looking at a design to solve the problem.

## Author

- Frontend Mentor - [@ChechiX](https://www.frontendmentor.io/profile/ChechiX)

## Acknowledgments

I want to thank someone with the username Darkstar who is in the Frontend Mentor Discord community for suggesting using Grid for step 2 of the project, as I would probably still be stuck at that point.
