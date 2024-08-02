# Frontend Mentor - Four card feature section solution 🃏🃏🃏🃏

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge 🎯

Users should be able to:

- View the optimal layout for the site depending on their device's screen size 📱💻

### Screenshot 📸

![](./design/desktop-design.jpg)

*Add a screenshot of your solution here. You can use Firefox to take a screenshot of your page, or use a tool like [FireShot](https://getfireshot.com/).*

### Links 🔗

- Solution URL: [Four Card Solution](https://www.frontendmentor.io/solutions/css-grid-and-flexbox-4oACA5tAS0)
- Live Site URL: [Four Card Feature](https://four-card-feature-beryl.vercel.app/)

## My process

### Built with 🛠️

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned 🧠

During this project, I improved my skills in creating responsive layouts using CSS Grid and Flexbox. I learned how to structure HTML semantically and use CSS to create a visually appealing design that adapts to different screen sizes.

Here's an example of the CSS Grid layout I used for the desktop version:

```css
@media (min-width: 1110px) {
  .card-container {
    grid-template-columns: repeat(3, 1fr);
  }

  .cyan {
    grid-column: 1;
    grid-row: 1 / 3;
  }

  .red, .orange {
    grid-column: 2;
  }

  .blue {
    grid-column: 3;
    grid-row: 1 / 3;
  }
}
```

This code creates a 3-column layout for larger screens, with the "Supervisor" and "Calculator" cards spanning two rows.

### Continued development 🚀

In future projects, I want to focus on:

- Improving my CSS Grid skills for more complex layouts
- Enhancing accessibility features ♿
- Optimizing performance for faster load times ⚡

### Useful resources 📚

- [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand Flexbox layouts better.
- [MDN Web Docs on CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - A comprehensive resource for learning CSS Grid.

## Author ✍️

- Website - [Abdullah](https://social-links-profile-rose-mu.vercel.app/)
- Frontend Mentor - [Abdullah](https://www.frontendmentor.io/profile/Ayyubiy90)
- Twitter - [Abdullah](https://www.x.com/ayyubiy10)