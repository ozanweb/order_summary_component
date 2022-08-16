# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/ozanweb/order_summary_component/]
- Live Site URL: [https://ozanweb.github.io/order_summary_component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS resets
- CSS flex
- CSS table
- Mobile-first workflow

### What I learned

* It is mandatory to reset some default settings of browsers before starting typing down CSS styles. Following properties are some of them:
<!--
{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
-->

* ```display: table``` is a CSS property that is widely supported by most browsers including older version ones. This property with ```display: table-cell``` can be used to venter elements vertically.

* When ```display: table``` is used for aligning elements vertically, ```background-color``` should always be ```transparent``` for both ```table``` and ```table-cell``` elements.

* Getting the width of the elements resized proportional to the height is a bit of a hassle in CSS. If you fix the height of a parent element, the content of the child element might overflow the parent element's borders when the width is reduced. I have overcome this using ```rem``` unit for the width of the element which bases itself to font-size.

### Continued development

I want to learn more about how buttons and links are used in web apps.

### Useful resources

- [Site 1](https://baymard.com/blog/line-length-readability) - This helped me for determining the optimal ```font-size``` in ```vw``` unit.
- [Site 2](https://piccalil.li/blog/a-modern-css-reset/) - Information on this site is important for beginners. You should know how browser's behave with their default CSS settings. Resseting some of these settings will save you a lot of hair.

## Author

- Frontend Mentor - [@ozanweb](https://www.frontendmentor.io/profile/ozanweb)
- LinkedIn - [@ozanpalanci](https://www.linkedin.com/in/ozanpalanci/)
