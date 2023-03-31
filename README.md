# <img src="https://user-images.githubusercontent.com/13468728/222973742-9133bdb5-61f0-4f53-8b08-bb3c349e2056.png" title="Frontend Mentor" alt="Frontend Mentor" width="50" height="50"/> Frontend Mentor - QR Code Component Solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](assets/images/qr.png)
![](assets/images/qr-responsive.png)

### Links

- [Solution URL](https://github.com/emre-02/QR-code-component)
- [Live Site URL](https://emre-02.github.io/QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM
- Pure CSS

### What I learned

In this project, I learned exactly how to center the qr code and use flex in more detail. I applied the BEM methodology using pure CSS.

- I tried to use BEM methodology in class naming:

```html
<div class="qr">
  <div class="qr__img"></div>
  <div class="qr__img-text"></div>
</div>
```

- I centered the qr by giving display flex and width-height to the body:

```css
body {
  font-family: "Outfit", sans-serif;
  background-color: hsl(212, 45%, 89%);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
}
```

## Author

- Frontend Mentor - [@Voldemort-07](https://www.frontendmentor.io/profile/Voldemort-07)
- Linkedin - (https://www.linkedin.com/in/yunus-emre-%C3%B6zt%C3%BCrk-83a794250/)
