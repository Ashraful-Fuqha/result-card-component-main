# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/resultsummarycardcomponentmain-XxdvPmYIBl)
- Live Site URL: [Live site URL here](https://ashraful-fuqha.github.io/result-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS
- GulpJS and BrowserSync

### What I learned

In this project i have learned about the gulpjs,browserSync and awaited SCSS.

```html
<div class="main-sec">
      <h1>Your Result</h1>
      <h2>76<span>of 100</span></h2>
      <h3>Great</h3>
      <p>You scored higher than 65% of the people who have taken these tests.</p>
    </div>
```
```css
@forward 'color';
@forward 'global';
@forward 'typography';
```
```js
exports.default = series(stylesTask,scriptsTask,browserSyncServe,watchTask);
```

### Continued development

I want to dig a little bit more on these concepts to be concreted.

## Author

- Website - Yes
- Frontend Mentor - [@Mjafarsadiq](https://www.frontendmentor.io/profile/Ashraful-Fuqha)