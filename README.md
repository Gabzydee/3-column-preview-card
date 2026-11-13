# Frontend Mentor - 3-column preview card component

This is my solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92QYdhX).

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

- Desktop: 3 cards side-by-side - SEDANS / SUVS / LUXURY
- Mobile: 3 cards stacked, centered, max-width 330px

### Links

- Live Site URL: [https://comfy-puffpuff-a771cf.netlify.app]

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Flexbox for centering
- CSS in one file - all CSS is inside `<style>` in `index.html`
- Google Fonts - Big Shoulders Display & Lexend Deca

### What I learned

- How to center a page with `body { display: flex; justify-content: center; align-items: center; min-height: 100vh; }`
- How to make 3 columns with `.container { display: grid; grid-template-columns: 1fr 1fr 1fr; max-width: 920px; }`
- How to make it responsive with `@media (max-width: 600px)` - change to `1fr`, `max-width: 330px`, `margin: 20px auto`
- How to use `overflow: hidden` + `border-radius: 10px` on the container to round the outer corners only
- Button text color must match the card color, or it will look faint

### Continued development

I want to keep practicing responsive layouts, CSS Grid, and separating CSS into a `style.css` file next time.

## Author

- Frontend Mentor - [@Gabzydee]