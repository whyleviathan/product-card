# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](screenshot-desktop.png)
![](screenshot-mobile.png)



### Links

- Solution URL: [My Solution](https://your-solution-url.com)



### Built with

- Non-Semantic HTML5 markup
- CSS 
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to use @media queries on screens.

if the screen is 550px wide or less,
then the mobile image will be displayed and if it is 550px wide or more the desktop image will be displayed.

```css

@media only screen and (max-width: 550px){
    .carta{
        margin-top: 1rem ;
        margin-bottom: 1rem;
    }

    .img-contenedor{
        width: 100%;
        height: 40%;
    }

    .img-contenedor img{
        content: url(images/image-product-mobile.jpg);
    }
    
    .carta{
        flex-direction: column ;
    }

    .detalles{
        width:100% ;
    }

    .detalles .nombre{
        padding-right: 0;
    }

    .img-contenedor img{
        border-top-left-radius: 10px;
        border-top-right-radius:10px ;
        border-bottom-left-radius: 0px;
    }
}
```
### Useful resources
-[CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries_ex.asp)

## Author

- Github - [Leviathan](https://github.com/whyleviathan)
- Frontend Mentor - [@whyleviathan](https://www.frontendmentor.io/profile/whyleviathan)



