## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This particular project is a challenge from Frontend Mentor, (https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7/hub/testimonials-grid-section-mYejrBlBz). The challenge wasn't difficult in the least bit if you're familiar with CSS Grid or Flexbox, which I used. I'm a newbie and I completed the challenge in a few hours, so head over to their website because they have many great challenges to help get better at coding.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5
- CSS Grid
- Very little Flexbox

### What I learned

Doing this challange has taught me more about CSS Grid and Flexbox and how they work so well together. I started off with learning Floats and I can say first-hand CSS Grid is a godsend. Spanning rows and columns helped me devlop a seamless and identical layout to the reference material.

Below is the main CSS that created the layout:

```css
.testimonials {
  margin: 100px 75px;
  padding: 20px;
  gap: 30px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}

.card--bg-purple {
  background: rgba(117, 65, 200, 1);
  grid-column: 1/3;
}

.card--bg-gray {
  background: rgba(72, 85, 106, 1);
  grid-column: 3/4;
}

.card--bg-white {
  background: rgba(255, 255, 255, 1);
  grid-column: 1/2;
}

.card--bg-black {
  background: rgba(25, 33, 46, 1);
  grid-column: 2/4;
  grid-row: 2;
}

.card--bg-whitetoo {
  background: rgba(255, 255, 255, 1);
  grid-column: 4/5;
  grid-row: 1/3;
}
```

## Author

- Frontend Mentor - [@quanthedev](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@quanthedev](https://www.twitter.com/yourusername)
