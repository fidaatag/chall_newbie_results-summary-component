# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Link](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Design preview for the Results summary component coding challenge](./design/screenshoot.gif)


### Links

- Live Site URL: [Results summary component](https://chall-results-summary-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - CSS pre-processor


### What I learned

The recap that is recorded here is basic css which I often rarely use.

- gradient color in css:

```css
.sec-1 {
    background: linear-gradient($Light_slate_blue_bg, $Light_royal_blue_bg);
}
```

- hide scrollbars for different browsers :
```css
.container {

    // mozila
    -ms-overflow-style: none; 
    scrollbar-width: none;

    // chrome
    &::-webkit-scrollbar{ 
        display: none;
    }
}
```


### Continued development

The Sass code here can be simplified even more. The use of @import is deprecated, so the future of this project will be adapted to the latest version of SASS. In addition, use font files that can still be optimized using SASS.


### Useful resources

- [CSS Grid](https://learncssgrid.com/) - the easiest guide to use the grid, there is a picture of each code that will be generated, cool
- [Hide Scroll bar](https://stackoverflow.com/questions/16670931/hide-scroll-bar-but-while-still-being-able-to-scroll) - Hide scroll bar, but while still being able to scroll
- [@font-face rules in SASS](https://gist.github.com/jonathantneal/d0460e5c2d5d7f9bc5e6) - guide to using font files on a project in SASS with @mixin


## Author

- Frontend Mentor - [@fidaatag](https://www.frontendmentor.io/profile/fidaatag)
- Twitter - [@fidaatag](https://twitter.com/fidaatag)
- Linkedin - [Fidaa Mustaghfiroh](https://www.linkedin.com/in/fidaatag/)

