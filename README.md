# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![screenshot of the nft card](/images/nft-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-nft-card-preview-0CQsCyrAsw)
- Live Site URL: [Add live site URL here](https://obikaviola.github.io/nft-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Through this challenge, I was able to learn image colour overlay, css position and image display on hover. 

```css
.image-equilibrium {
    width: 18.5rem;
    border-radius: 0.9rem;
    position: relative;
    top: 0;
    left: 0;
}

.image-equilibrium:hover {
    opacity: 0.5;
}

.image-view {
    position: absolute;
    top: 42%;
    left: 42%;
    display: none;
}

.card:hover .image-view {
    display: inline;
    cursor: pointer;
}
```

### Continued development

I will be learning more about css positions and background styles.

### Useful resources

- [Two ways to create an image with a colour overlay in CSS](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio) - This article helped me understand how to create colour overlay in images.

- [How to change image on hover with CSS](https://www.tutorialrepublic.com/faq/how-to-change-image-on-hover-with-css.php) - This is an amazing article which helped me finally understand how to make an image appear and change on hover.

## Author

- Frontend Mentor - [@Obikaviola](https://www.frontendmentor.io/profile/Obikaviola)
- Twitter - [@obika_viola](https://www.twitter.com/obika_viola)
