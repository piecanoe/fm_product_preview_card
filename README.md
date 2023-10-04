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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./solution.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/piecanoe/fm_product_preview_card.git)
- Live Site URL: [Add live site URL here](https://fm-product-preview-card-kd.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries for Responsiveness
- Font Awesome Icons
- Google Fonts

### What I learned

In this exercise, I learned how to make a website responsive using media-queries at the bottom of my CSS file:

```css
@media (max-width: 412px){
    #box{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        filter: none;
        width: 100%;
        height: 100%;
    }
}
```

I learned how to use two different images for different screen sizes using media queries:

```css
.bigscreen{
        display: none;
    }

    .smallscreen{
        display: block;
        width: 100%;
        border-radius: .7rem .7rem 0 0;
    }
```

### Continued development

This was one step further into learning how to build responsive websites. I'm getting more comfortable using media queries and learning new syntax with each project. Next project I want to do is one that includes Javascript.

### Useful resources

- [Example resource 1](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Best flexbox cheat sheet online
Stack Overflow Thread on Centering Divs - After painstakingly searching for solutions for hours, this was the solution that worked for me.

## Author

- Website - [Karen Du](https://karendu.netlify.app/)
- GitHub - [@piecanoe](@piecanoe)
- Frontend Mentor - [@piecanoe](https://www.frontendmentor.io/profile/piecanoe)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
