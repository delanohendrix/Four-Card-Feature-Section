# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/)
- Live Site URL: [GitHub Pages](https://delanohendrix.github.io/Four-Card-Feature-Section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Initially I intended to tackle the 4 cards using Css grid with each card being a individual element. HOwever, I quickly relaized that wouldn't work so I then decided to combine the center two cards using a container and use flexbox instead, and from there I just needed to align all items in the center.

```html
<div class="card-stack">
  <section class="card red">
    <div class="card__content">
      <h2>Team Builder</h2>
      <p>Scans our talent network to create the optimal team for your project</p>
      <div class="card__icon">
        <img src="images/icon-team-builder.svg" alt="" />
      </div>
    </div>
  </section>
  <section class="card orange">
    <div class="card__content">
      <h2>Karma</h2>
      <p>Regularly evaluates our talent to ensure quality</p>
      <div class="card__icon">
        <img src="images/icon-karma.svg" alt="" />
      </div>
    </div>
  </section>
</div>
```

```css
.card-container {
  display: flex;
  align-items: center;
  column-gap: 30px;
}
```

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)
