# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop](./screenshot-desktop.png)
![Tablet](./screenshot-desktop.png)
![Mobile](./screenshot-desktop.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

One of the things I really struggle with on this project was setting up the hero image to live simultaneously within the columns as a grid item, and also go beyond the grid container to achieve the look of the design. I was able to make this work by creating a negative margin property and upping the width to 125%. I imagine there is better ways to achieve the same result, but I was happy with being able to figure it out and learned quite a bit from the challenge it presented. If you have any suggetions on a better method, I would appreciate the insight!

```css
.hero-img {
    z-index: -1;
    margin-top: -200px;
    max-width: 250%;
    max-height: 100%;
    align-self:center;
}
```

### Useful resources

- [CSS Grid Crash Course 2022 - Brad Traversy](https://www.example.com) - Brad Traversy's recent CSS Grid course really helped me understand how to utizilite grid for this project with little prior knowledge. I highly recommend checking it out.

## Author

- Frontend Mentor - [@idmike](https://www.frontendmentor.io/profile/idmike)
