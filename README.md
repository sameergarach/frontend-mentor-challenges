# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: https://www.frontendmentor.io/solutions/qr-code-solution-using-css-transform-property-SkRgK1QLq
- Live Site URL: https://sameergarach.github.io/frontend-mentor-challenges/

## My process

### Built with

- HTML5
- CSS 3



### What I learned

In order to arrive at my solution, which is compatible with the required desktop design and mobile design,
I had to center my QR code. All the content of my QR code, the image, the heading, and the paragraph, are in a div.
The code below, found on w3schools, helped in centering my div.
To have only the desktop design, place the following in the css external file using a tag selector for the body: width: 1440px;
To have only the mobile design, place the following in the css external file using a tag selector for the body: width: 375px; 


```css
.div {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}


### Continued development

I want to further understand how to center content on a webpage. The above method is new to me, and I understand it somewhat.
I am more familiar with text-align, padding, and margin.

### Useful resources

- Resource 1 (https://www.w3schools.com/css/css_align.asp) - This helped me for centering the div. I really liked this pattern and will use it going forward.


## Author

- Frontend Mentor - [@sameergarach](https://www.frontendmentor.io/profile/sameergarach)

