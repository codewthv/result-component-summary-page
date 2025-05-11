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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page


### Screenshot

![](./screenshot.jpg)

Desktop View:
<img width="953" alt="image" src="https://github.com/user-attachments/assets/8cb957c1-98b7-423d-8369-7bbbbdb6c44f" />

Mobile View:

<img width="391" alt="image" src="https://github.com/user-attachments/assets/a1d5b401-9a29-4574-a940-5c0604701693" />


### Links

- Solution URL: (https://github.com/codewthv/result-component-summary-page)
- Live Site URL: (https://codewthv.github.io/result-component-summary-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Float
- Mobile-first workflow


### What I learned

I learnt how to use float to achieve this design.

```html
<div class="container">
    <div class="firstbox">
      <h3 class="h3">Your Result</h3>
      <div class="circle">
        <p>76</p>
        <p class="wrap">of 100</p>
      </div>
```
```css
.firstbox{
    background: linear-gradient(180deg, var(--light-slate-blue), var(--light-royal-blue));
    float: left;
    width: 50%;
}
```

### Useful resources

- [W3schools](https://www.w3schools.com) - This helped me to understand float, flexbox and CSS grid. I really liked this pattern and will use it going forward.


## Author
- Frontend Mentor - [@codewthv](https://www.frontendmentor.io/profile/codewthv)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
