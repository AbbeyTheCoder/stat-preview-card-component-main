# Frontend Mentor - Stats preview card component solution

## Table of contents

- [Overview]
  - [The challenge]
- [My process]
  - [Built with]
  - [What I learned]
  - [Continued development]

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## My process

- HTML structure first.
- Mobile CSS view.
- Desktop CSS view.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- Flexbox and Grid Layout.
- Overlaying a image with a colour.

```css
header {
    position: relative;
    & > img {
      border-radius: 8px 8px 0px 0px;
      width: 100%;
      height: 100%;
    }
    &::before {
      content: "";
      background-color: hsla(277, 64%, 61%, 0.6);
      border-radius: 8px 8px 0px 0px;
      width: 100%;
      height: 100%;
      z-index: 1;
      position: absolute;
    }
```

- Nesting in CSS, like as in SASS.

### Continued development

- CSS Layout.
