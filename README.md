# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop view solution](./my-solution/screenshot-1.png)
![Mobile portrait view solution](./my-solution/screenshot-2.png)
![Mobile landscape view solution](./my-solution/screenshot-3.png)

### Links

- Solution URL: [Solution URL]https://github.com/Matondo99/product-preview-card-component/)
- Live Site URL: [product-preview-card-component](https://matondo99.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

## What I learned

Using the html picture element to shift images according to screen sizes.

```html
<picture>
  <source media="(min-width: 430px)" srcset="images/image-product-desktop.jpg">
  <img src="images/image-product-mobile.jpg" alt="bottle of parfume">
</picture>
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

Thanks to frontendMentor for providing best practice.
