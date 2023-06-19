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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/images/screenshot.png)
![](/images/screenshot-mobile.png)




### Links

- Solution URL: [url](https://github.com/motuncoded/product-preview-card-component-main)


### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
-SASS


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned
l learnt about the use of image srcset in the HTML, which help the browser tt to pick the image suitable to its viewport



To see how you can add code snippets, see below:

```html
<picture>
  <source media="(min-width:400px)" srcset="/images/image-product-desktop.jpg">
  <source media="(min-width:0px)" srcset="/images/image-product-mobile.jpg">
<img src="/images/image-product-desktop.jpg" alt="Product preview images"/>
</picture>
```
```scss
$dark-cyan: hsl(158, 36%, 37%);
$cream: hsl(30, 38%, 92%);
$dark-blue: hsl(212, 21%, 14%);
$dark-grayish-blue: hsl(228, 12%, 48%);
$white: hsl(0, 0%, 100%);
$gray:hsl(0, 0 ,50%);
$black:hsl(0, 0%, 0%);
$primary-font:"Montserrat", sans-serif;
$secondary-font:"Fraunces", sans-serif;

```




### Useful resources

- [SASS Installation documentation](https://sass-lang.com/install) - This helped me on how to install and use SASS on my local machine
- [SASS Youtube tutorial](https://www.youtube.com/watch?v=_a5j7KoflTs&t=451s) - This is an amazing video i got from youtube to help in the use of SASS


- Frontend Mentor - [@motuncoded](https://www.frontendmentor.io/profile/motuncoded)
- Twitter - [@motunadeneye](https://twitter.com/motunadeneye)



