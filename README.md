# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](/QRCodeSolution_Screenshot.png)

### Links

- Solution URL: ( https://www.frontendmentor.io/solutions/qr-code-using-css-styles-RQqlFprBoN)
- Live Site URL: (https://josenegrete123.github.io/QRCode-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Style for font used [Outfit] (https://fonts.google.com/specimen/Outfit)

### What I learned

Used custom made classes to manipulate the text. Learned how to add an image while also it not repeating and fitting into the content box.
Had to add elements to the HTML file to input the QR code image. Redefined the text into paragraphs and added custom classes to each.

To see how you can add code snippets, see below:

```html
  <div class="qr-image"></div>
  <p class="outfit-bold">Improve your front-end skills by building projects</p>
  <p class="outfit-regular">  Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>  
```
```css
.qr-image {
  background-image: url("./images/image-qr-code.png");
  background-size: cover;
  background-repeat: no-repeat;
}
```
### Continued development

Need to figure out a better or faster way to use an image and fit it into the content box. Took a lot of googling to find the answer.
Also would love to figure out how to get the right measurements for the project. On this one I was eyeballing it.

### Useful resources

- [Resizing an image using CSS](https://www.browserstack.com/guide/how-to-resize-image-using-css) - This helped me to resize the QR code image to fit inside the given width and height.
- [Background](https://web.dev/learn/css/backgrounds) - This is an amazing article which helped me understand how to not repeat an image when it doesn't fit the content box.

## Author

- Website - [Jose Negrete](https://github.com/josenegrete123)
- Frontend Mentor - [@josenegrete123](https://www.frontendmentor.io/profile/josenegrete123)