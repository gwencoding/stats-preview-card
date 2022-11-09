# Frontend Mentor - Stats preview card component solution

![](./design/desktop-preview.jpg)

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Stats-soluce-desktop.png) 

### Links

- Solution URL: [https://github.com/gwencoding/stats-preview-card]
- Live Site URL: [https://stats-preview-card-gc.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

For this challenge I continue learning responsive design using media query.
I also implement the DRY principle with --root{} and var() according to FEM user and a new tool mix-blend-mode by colorizing the image.


See some code snippets, see below:

```css
:root{
    /*Primary*/
    --main-background:hsl(233, 47%, 7%);
    --card-background:hsl(244, 38%, 16%);
}

.content-txt-color{
    color:var(--accent);
}

img{
    height: 100%;
    opacity:0.8;
    mix-blend-mode: multiply;
}
```
### Continued development

With this challenge I had some difficulty with responsice design and I will check with people to know where to improve so I still need to work on responsive design breakpoints.
I want to refine the mix-blend-mode that I find thanks to a user.

### Useful resources

- [Solution in comments by vcarames](https://www.frontendmentor.io/solutions/responsive-design-using-flexbox-5ivtnODFt0) - This helped me to find the mix-blend-mode technique

## Author

- Frontend Mentor - [@gwencoding](https://www.frontendmentor.io/profile/gwencoding)

## Acknowledgments

Thanks to the community feedback in FEM, it helps me polish my code.

