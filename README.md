# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Screenshot%20(161).png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

How to change properties of elements to make the website responsive according to different sizes of website.
Change color of elements when hovered.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css

button{
    background-color: white;
    height: 3rem;
    width: 10rem;
    border:10px solid white;
    border-radius: 30px;
    color: hsl(257, 40%, 49%)
}

button:hover{
    background-color: hsl(300, 69%, 71%);
    color: white;
    border-color:hsl(300, 69%, 71%);
}

@media (max-width: 767px) {
    body {
        background-image: url(./images/bg-mobile.svg)
    }

    
    .content{
       flex-direction: column;
       text-align: center;
    }
    .content .illustration{
        width:95%;
        margin-inline: auto;
    }
    .content .headline{
        width: 95%;
       margin-inline: auto;
       align-items: center;
    }
    h1{
        font-weight: 400;
        font-size: 1.75rem;
    }
    p{
        font-size:16.5px;
    }
    button{
        width:200px;
        
    }

    .icons {
        margin-block: 5em 1.5em;
        justify-content: center;
      }
}
```



### Continued development

I need a good grasp of how to position elements when in responsive mode, for example it took a lot of time to figure out way of stacking element when in mobile view and also setting proper max-width and min-width.



## Author


- Frontend Mentor - [@Rutz1234](https://www.frontendmentor.io/profile/Rutz1234)




