# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://jaycgreenwald.github.io/18-testimonials-grid-section/](https://jaycgreenwald.github.io/18-testimonials-grid-section/)

## My process

- Hold on for dear life.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SASS/SCSS

### What I learned

How to use SASS functions. Here are a couple of the articles I reviewed while building my first function.
https://dev.to/nikolab/convert-px-to-rem-using-sass-3-methods-4ep2
https://gil0mendes.io/blog/sass-rem-to-px/

How to trim decimal places from numbers in SASS.
https://css-tricks.com/snippets/sass/fix-number-n-digits/
https://www.sitepoint.com/a-tale-of-css-and-sass-precision/

How to create a VS Code snippet. Which I used to insert my new SASS function thankyouverymuch. 
https://code.visualstudio.com/docs/editor/userdefinedsnippets


```scss
// functions 
@function pxToRem($pxValue) {
    $remValue: round(($pxValue / 13) * 100) / 100; 
    @return #{$remValue}rem;
}
```

### Continued development

  1. Should I be using rem unit for EVERYTHING? Like, what are the cases in which I would want to use px instead of REM as the unit?
  2. Can grid automatically layout content? I think this answer may be depends...? I started watching Jen Simmons grid videos so I'm on my way to obtaining that sacred knowledge.
  3. The rest of it (moves arm in sweeping motion).


### Useful resources

Mostly sourced in "What I Learned" above. Here's a bonus resource and it appears to be a dandy:

 - [YouTube Channel Layout Land by Jen Simmons](https://www.youtube.com/channel/UC7TizprGknbDalbHplROtag)


## Author

- Website - [My GitHub](https://github.com/jaycgreenwald)
- Frontend Mentor - [@jaycgreenwald](https://www.frontendmentor.io/profile/jaycgreenwald)
- Twitter - [@jaycgreenwald](https://www.twitter.com/jaycgreenwald)