# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview




### Links


- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```css
ol{
   
   list-style: none;
   counter-reset: item;
}
ol li{
    position: relative;
    padding-left: 20px;
}
ol li::before{
    content: counter(item) ".";
    counter-increment: item;
    position: absolute;
    left:0;
    color:rgb(169, 64, 64) ;
}
```

## Author

- Website - [Pandyan Anandhi](https://www.your-site.com)
- Frontend Mentor - [@anandhi3275](https://www.frontendmentor.io/profile/anandhi3275)



