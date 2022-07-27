# Frontend Mentor - Profile Card Component Solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- Build out the project to the designs provided.

### Screenshots

![](./images/profile-card-component-desktop.png)

![](./images/profile-card-component-mobile.png)

### Links

- Solution URL: [GitHub](https://github.com/wesleyjacoby/Profile-Card-Component)
- Live Site URL: [GitHub Pages](https://wesleyjacoby.github.io/Profile-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

The first challenge I ran into was the background. I learnt how to add multiple images to a background and also position them in the correct place using this CSS code:

To see how you can add code snippets, see below:

```css
body {
    background-image: url(./images/bg-pattern-bottom.svg), url(./images/bg-pattern-top.svg);
    background-position: right -7.5rem bottom -31.25rem, left -7.5rem top -31.25rem;
    background-repeat: no-repeat, no-repeat;
    background-size: auto, auto;
}
```

The next big challenge was positioning the profile image into place. This was finally achieved with this code:

```css
.profile-image {
    position: relative;
    margin: 0 auto;
    transform: translateY(-50%);
```

### Continued development

I am getting more comfortable using Flexbox and positioning elements onto the page. I still struggle with making the page responsive, but I am making progress slowly and starting to get more comfortable with it.

### Useful resources

- [w3schools](https://www.w3schools.com/Css/css3_backgrounds.asp) - This helped me with the positioning of the background images.

## Author

- Frontend Mentor - [@wesleyjacoby](https://www.frontendmentor.io/profile/wesleyjacoby)

## Acknowledgments

My brother, [Darren](https://github.com/darrenjacoby), helped me with the positioning of the profile image.