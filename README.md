# Frontend Mentor - Single Price Grid Component Solution

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](/Screenshot.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/single-grid-card-fOxhOflyv3)
- [Live Site URL ](https://single-price-grid-solution.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- Working within CSS grid was what I learned the most! It was a little difficult to find the right code that applies to manipulate the grid that I was looking for. I understand that all grids are completely different and there are a lot of properties to manipulate the grid but here are a couple pieces of code that I learned along the way

```html
<div class="item-1"></div>
<!-- Appropriately naming a class that I am going to target based on the design. -->
```

```css
.parent-grid {
  grid-template-columns: 1fr 1fr; /* Having two columns to fix the design needs*/
}

.item-1 {
  grid-column: span 2; /* Spanning the grid item across 2 columns. */
}

@media (max-width: 700px) {
  .parent-grid {
    grid-template-columns: 1fr;
  }
  .item-1 {
    grid-column: span 1;
  }
} /* Responsively making the grid into one single column while giving equal width and height of the first grid item */
```

### Continued development

- I will continue to work on projects with FEM that use grids in addition to expanding my knowledge in terms of syntax.

### Useful resources

- [Grid Video 1](https://youtu.be/-66-ctvXHGY?si=W_-ogyC4dlUU5mob)
- [Grid Video 2](https://youtu.be/EiNiSFIPIQE?si=y7Tav-lHdKJ5Cm_O)
- [Grid Video 3](https://youtu.be/rg7Fvvl3taU?si=Q8emaGWxNJsSAE7f)

### Author

- Website - [Clyde Forland](https://www.clydeforland.com)
- Frontend Mentor - [@clydehenry3](https://www.frontendmentor.io/profile/clydehenry3)
- Twitter - [@clydehenry3](https://www.twitter.com/clydehenry3)
