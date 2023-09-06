# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This challenge took about a week to complete. It was done in two phases. The main.html was styled using plain css and the webbootstrap.html was styled using bootstrap classes. I submitted both solutions because they felt complementary. The latter favours a mobile friendly experience with room for improvement on the grid alignment. The former favours a large screen with good grid alignment but room for improvement on the mobile-responsiveness

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

 ![](./screenshot.jpg) ![](./screenshot.jpg) ![](./assets\images\web with  Bootstrap.png)



### Links

- Solution URL: [Add solution URL here](https://github.com/DaFlusher/news-homepage-main.git)


## My process

I first built the site using plain  html and CSS, then reproduced it using Bootstrap styling

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Bootstrap - For styles



```html

This challenge made me tinker quite a lot with grid manipulation.
Prior to now, I was more comfortable with flexbox layouts, grids were on the 'need to know' basis.


```
```css
.proud-of-this-css {
    grid-template-areas: 'header''hero' 'title' 'texti' 'sidebar' 'footer';
        grid-template-columns: fit-content;
        grid-template-rows: repeat(auto-fit, minmax(100px, auto));
        column-gap: 20px;
}



### Continued development


I would try to practice more of mobile first designs. Its easier for me to remember to design for mobile first when using bootstrap, because I tend to jump headfirst into designing for bigger screens. Going on I would also focus on using SASS forr boostrap customization, especially the grids.



### Useful resources

- [Example resource 1](https://w3schools.com) - This helped me with brushing up on bootstrap. I really liked their quick and to the point pattern of teaching and will use it going forward.

- [Example resource 1](https://codeacademy.com) - This helped me with brushing up on grids. I really liked their handson practice based teaching and will use it going forward.


## Author

- Yet to review my portfolio site. It should be ready soon
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/DaFlusher)
- Twitter - [@Joyibe17](https://www.twitter.com/JoyIbe17)


## Acknowledgments

I would like to thank Shaun from NetNinja Channel on youtube. His bootstrap tutorials really helped a lot.
