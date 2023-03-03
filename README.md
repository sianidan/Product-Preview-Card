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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop](./screenshot-desktop.png)
![Mobile](./screenshot-mobile.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/responsive-product-preview-card-using-flexbox-vNWyrk-edq)
- [Live Site URL](https://sianidan.github.io/Product-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Flexbox

### What I learned

The major thing I learned while completing this project was how to switch images based on browser size. 

In my first version of this solution, I included both the desktop and mobile images in their on ```img``` tags in my HTML. Then I used media queries to display or hide the images depending on the browser width. For my second attempt, I switched to the ```picture``` element and its corresponding elements/attributes. The MDN has an article about this topic, which I linked below.

```html
<picture class="img">
        <source class="imgMobile" media="(max-width: 700px) and (min-height: 640px)" srcset="./images/mobile.jpg 686w" />
        <img src="./images/desktop.jpg" alt="Glass bottle of Chanel Gabrielle Perfume">
      </picture>
```

### Continued development

Moving forward, I want to keep learning and practicing methods to make each project I build as responsive as possible. Accessibility is a priority of mine, as well as ensuring folks are able to view things that I create whether or not they have access to a desktop.

### Useful resources

- [Changing images for responsive design](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This MDN article describes in depth how to use the ```img``` or ```picture``` elements and their attributes in order to make images responsive.

- [Responsive images cont.](https://css-tricks.com/responsive-images-css/) - This is another really good resource for making images responsive in HTML and CSS. 

- [Responsive typography](https://stevenloria.com/responsive-typography/#:~:text=Responsive%20Typography%20Using%20Modern%20CSS%201%20Recommended%3A%20PostCSS,Typographic%20Scale%20-%20Primer%20on%20modular%20scales%20) - This blog post helped to explain how to make typography on a web page responsive based on the browser size.

## Author

- GitHub - [Siani Dan](https://github.com/sianidan)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/sianidan)
- Twitter - [@devbysiani](https://www.twitter.com/devbysiani)

