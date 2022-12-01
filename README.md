# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

The challenge is to build out this product preview card component and get it looking as close to the design as possible.

### Screenshot

![Final Product](images\screencapture-127-0-0-1-5500-2022-11-30-17_23_34.png)

### Links

- Github Repo URL: [Add solution URL here](https://github.com/mountaindriver/Product-Card)
- Live Site URL: [Add live site URL here](https://mountaindriver.github.io/Product-Card/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned a lot of things form Kevin Powells walk throught of this challenge but specifically how locally scope a custom property, how to name classes professionally, and add a accesbility feture for screen readers when two prices are present.

```html
    <p class="product__price"><span class="visually-hidden">Current price:</span>$149.99</p>

```
```css
.visually-hidden:not(:focus):not(:active){
    clip: rect(0 0 0 0);
    clip-path: inset(50%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px;
}
```


### Useful resources

- [Kevin Powell's Taking on a Frontend Mentor challenge Responsive Product Preview Card Componet](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - This helped me for most the porject and really help me understand a professional way to comment css. I really liked how he made things moble first and responsive.

## Author

- Website - [Lucas Freigenberg](lucasfreigenberg.dev)
- Frontend Mentor - [@mountaindriver](https://www.frontendmentor.io/profile/mountaindriver)
- GitHub - [@mountaindriver](https://github.com/mountaindriver)


## Acknowledgments

Kevin Powell, the CSS King
