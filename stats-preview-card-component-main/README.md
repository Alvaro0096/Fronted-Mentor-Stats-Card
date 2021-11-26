# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview]
  - [The challenge] The challenge is to build out this card component and get it looking as close to the design as possible.
- [My process] 
  - [Built with] HTML, CSS.
- [Author] AlvaroJorge
- [Acknowledgments] FrontedMentor 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- Desktop view:

![Stats_card_component_desktop](https://user-images.githubusercontent.com/86804019/143623845-e138bbe2-da5a-44e2-a246-b671833e3d03.png)

- Mobile view: 

![Stats_card_component_mobile](https://user-images.githubusercontent.com/86804019/143623950-a7ba9b9a-c754-4123-87d4-5011d77a5b62.png)


### Links

- Solution URL: https://www.frontendmentor.io/profile/Alvaro0096/solutions
- Live Site URL: https://alvaro0096.github.io/Fronted-Mentor-Stats-Card/stats-preview-card-component-main/

## My process

I beggin creating a main class to contain all the tags to center both vertical and horizontal in a display grid. 
Then put a tag in each text or number and group the stadistics in his how div box. Finally create anoter
display grid to organice them in colums. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I did not now until now how easy is to order and center with a grid display. It saves a lot of time and you don't need
to bother with margins and positions.

```html
<h1>Some HTML code I'm proud of</h1>
```
<div class="detail">
    <h2>10k+</h2>
    <p>templates</p>
  </div>    
  <div class="detail">
    <h2>314</h2>
    <p>companies</p>
  </div>  
   <div class="detail">
    <h2>12m+</h2>
    <p>queries</p>
  </div>
</div>

```css
section{
    display: grid;
    grid-template-columns: 50% 50%;
    align-content: center;
    justify-content: center;
    background: hsl(244, 38%, 16%);
    border-radius: 10px;
}
.stadistic{
    grid-row: 3;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    margin-top: 70px;
    margin-left: 10%;
    margin-right: 10%; 
    margin-bottom: 50px;
}
.img_box{
    grid-column: 2;
    grid-row: 1 / 4;
    background: hsl(277, 64%, 61%);
    background-image: url(images/image-header-desktop.jpg);
    max-height: 100%;
    background-size: cover;
    background-blend-mode: multiply;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
}
```
### Continued development

I wanna continue learning grid and flexbox properties. Both have a lot of useful tools to make really bigs improvements
in a short time.

## Author

- Frontend Mentor - @Alvaro0096 https://www.frontendmentor.io/profile/Alvaro0096
