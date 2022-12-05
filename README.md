# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Live Site URL: [View site](https://7h3xxx.github.io/front-end-challenge-1/)

## My process

### Built with

- Semantic HTML5 markup (I did my best :-))
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

In this project i learned how to use CSS grid to make a simple layout that adapts itself based on the screen size. I also learned how to use the HTML picture element to display responsive images based on the resolution or on the screen size. I thought we need to use CSS but HTML picture element did the job pretty well. It's something like this.

```html
<picture>
  <source media=(max-width: 640px) srcset="url_to_your_image"/>
  <img src="url_to_your_image"/> <!-- Very important ! Otherwise the image won't render -->
</picture>
```
With this we basically tell the browser to load the image based on the size of the screen. In this case For screen sizes under 640px it's the default image (in the ```<img/>``` tag) that will be displayed.

### Useful resources

- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This helped me for displaying the right image based on the screen size. You can learn more on responsive images by following the link.


## Acknowledgments

One of my inspiration when it comes to CSS it's Kevin Powell. I learned a lot by watching his videos and using his tips. Maybe you will too, check his [Youtube channel](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw).
