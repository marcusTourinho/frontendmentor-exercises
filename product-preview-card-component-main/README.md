# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./my-solution/my-solution2.PNG)
![](./my-solution/my-solution-responsive2.PNG)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Here I practiced Mobile-first workflow and learned how to change background image in different display widths.

Using the following code I was able to change the background image and fit according to the display width:

```css
@media (min-width: 1440px) {
  #img-container {
    background-image: url("./images/image-product-desktop.jpg");
    border-radius: 10px 0 0 10px;
    background-size: cover;
    height: 385px;
    width: 280px;
  }
}
```
## Author

- Linkedin - [Marcus Tourinho](https://www.linkedin.com/in/marcus-tourinho/)

## Acknowledgments

Here I used the mobile first workflow and it was easier to achieve the expected result.
