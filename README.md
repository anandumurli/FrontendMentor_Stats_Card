# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

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

- View the optimal layout depending on their device's screen size

### Screenshot
The desktop version looks like.
![](./screenshots/screenshot-desktop.png)

The mobile version looks like.
![](./screenshots/screenshot-mobile.png)

### Links

- [Live Site URL](https://anandumurli.github.io/FrontendMentor_Stats_Card/)

## My process

### Built with

- HTML5 markup
- CSS
- Flexbox

### What I learned

The one thing that did pose an issue was to get the image on the side of the card to work the way as provided in the requirement. Instead of using the tint idea, where you work with opacity only or with the linear gradient option, the 
```html
    <div>
        <div class="background">
            <div class="background-image">
            </div>
        </div>
    </div>
```
```css
    .background{
        background-color: red;
    }
    .background-image{
        mix-blend-mode: multiply; 
        opacity: 0.5;
    }
``` 
was a better solution.

### Useful resources

- [Kevin Powell - Mix-Blend-Mode Tutorial](https://youtu.be/TAA89nkEuhw) - This video is a treasure, just like all of his other videos. It goes in depth enough to understand the hows and whys of mix-blend-mode.

## Author

- Frontend Mentor - [@anandumurli](https://www.frontendmentor.io/profile/anandumurli)


