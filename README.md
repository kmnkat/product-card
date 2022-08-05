# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshoots/desktop.jpg)
![](./screenshoots/mobile.jpg)

### Links

- Solution URL: [Github](https://github.com/kmnkat/product-card)
- Live Site URL: [Github Pages](https://kmnkat.github.io/product-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SCSS
- BEM
- CSS grid

### What I learned

In this project I use BEM and SASS and combine both grid and flexbox to get the optimal responsive layout.

```css

.product-cart {
  max-width: 50rem;
  width: 50%;
  display: grid;
  grid-template-columns: repeat(2, minmax(20rem, 1fr));
  min-width: 40rem;
  align-self: center;

  .product-cart__photo > img {
    width: 100%;
    min-width: 200px;
    min-height: 100%;
  }

  .product-cart__content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 2rem;
   }
 }

```


