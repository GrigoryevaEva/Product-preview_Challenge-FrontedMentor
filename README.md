# Frontend Mentor - Product preview card component solution

Hi! I'm Eva.
Thank you for deciding to familiarize yourself with my solution of one of the Frontend Mentor challenges.
This is **the Second Version** of my solution.

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Link](#link)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

[Brief](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa):
“Your challenge is to build out this product preview card component and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- view the optimal layout depending on their device's screen size;
- see hover and focus states for interactive elements”.

### Screenshot

Design sources:
[Desktop](design/desktop-design.jpg)
[Mobile](design/mobile-design.jpg)

My solution:
[Desktop](screenshots/Desktop.png)
[Mobile](screenshots/Mobile.png)

### Link

[Project page](https://grigoryevaeva.github.io/Product-preview_Challenge-FrontedMentor/)

## My process

### Built with

- HTML5 
- CSS
- Flexbox
- CSS Grid
- Position
- Media query

### What I learned

This is project was my first experience of adaptive design for the mobile format.
In general, I have strengthened my existing knowledge of HTML and CSS.

However, during the implementation of the project, I encountered a problem, namely the vertical centering of the element relative to the entire page.
Here I want to share my solution:

```css
.container-main {
    position: fixed;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container-footer {
    position: fixed;
    bottom: 0;
    right: 0;
    left: 0;
}
```

### Continued development

My development plans:

- improve your knowledge of Grid CSS
- start using SASS
- try to adapt the layout according to the principle of (mobile-tablet-desktop), and not (desktop-tablet-mobile)
- accordingly, connect the tablet format to the adaptive layout

### Useful resources

- [Фрілансер по життю](https://www.youtube.com/@FreelancerLifeStyle) - This YouTube channel helped me a lot in the implementation of this project, especially in terms of adaptive layout.
- [Grid or Flexbox](https://codecoda.com/en/blog/entry/css-layout-grid-vs-flexbox) - this article helped me a lot in the implementation of this project, and also had a great impact on understanding the importance of Grid.

## Author

- Frontend Mentor - [@GrigoryevaEva](https://www.frontendmentor.io/profile/GrigoryevaEva)
