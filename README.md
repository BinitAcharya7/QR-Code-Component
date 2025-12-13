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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Solution URL](https://github.com/BinitAcharya7/QR-Code-Component)
- Live Site URL: [QR Code Component](https://binitacharya7.github.io/QR-Code-Component/)

## My process
- I opened the design file in Figma and looked for what layouts and spacing would work best.
- I then structured my HTML with the three main elements.
- I then styled those elements using CSS Flexbox.
- After comparing the design with my results, and making some tweaks I concluded the design was finished.

### Built with

- HTML5
- CSS custom properties
- Flexbox

### What I learned

- How to set up custom variables
- Use more percentages for easier responsive setup
- Background image property
- Using flexboxes inside flexboxes


```css
.qr-code{
    height: 288px;
    width: 288px;
    background-image: url("images/image-qr-code.png");
    background-position:center;
    background-repeat: no-repeat;
    background-size:contain;
    border-radius: 10px;
    overflow: hidden;
    margin-bottom: var(--spacing-300);
}
```

### Continued development

- Must get more comfortable with using flebox.
- Must learn how to plan out in advance what i must do by looking at the required design.
- Must use Figma dev tools better
- Must learn to tackle responsiveness easier using things like rem and percentages.


### Useful resources

- [CSS Units](https://www.youtube.com/watch?v=N5wpD9Ov_To) - This helped learn what units are appropriate in what situations. I plan to use this approach going forward.
- [CSS Flexbox](https://www.youtube.com/watch?v=fYq5PXgSsbE&t=1s) - Greatest video on Flexbox ever.
-[Flexbox Froggy](https://flexboxfroggy.com/) - Great way to practice flexbox.


## Author

- Website - [Binit Acharya](https://binitacharya.medium.com/)
- Frontend Mentor - [@BinitAcharya7](https://www.frontendmentor.io/profile/BinitAcharya7)
- Twitter - [@Binit_Acharya](https://www.twitter.com/Binit_Acharya)


## Acknowledgments

Thanks Web Dev Simplified and Kevin Powell for making my life easier.

