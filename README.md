# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![](./images/Screenshot.png)

### Links

- Solution URL: [https://github.com/hg770/hg770.qr-code-component.git](https://github.com/hg770/hg770.qr-code-component.git)
- Live Site URL: [https://hg770.github.io/](https://hg770.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Desktop-first workflow

### What I learned

I learned to use padding and margin, and also to use the position function.
```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.container {
  margin: auto auto;
}
.image {
  padding: 5% 5% 0% 5%;
}
```
I also learned to use border radius by wrapping the image with a div, and applying the border radius to it, using overflow:hidden.

```html
<div class="image" style="border-radius: 30px; overflow: hidden;">
  <img src="images/image-qr-code.png">
</div>
```
