# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

Your challenge is to build out this recipe page and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

### Screenshot

<img src="/desktop.jpg" width="660"> <img src="/mobile.jpg" height="450"> 

### Links

- Live Site URL: [Recipe Page](https://ataylorn.github.io/FrontendMentor-Recipe-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

After reviewing the challenge, my thought was that it would be best to try to do the mobile version of this project first and then move to the desktop version. It also seemed like it would be best to focus on the HTML part first, focusing 	primarily on semantic HTML elements. For this project, I didn't feel like I necessarily NEEDED Vue or React. I do want to use React at some point to practice, but for now, I'm focusing purely on HTML and CSS.

Figuring out how to create spacing between bullet points and the list item and how to change just the color of the bullet points without changing the color of the list item, took me a moment to figure out, a lot of trial and error. 

This allowed me to change the bullet points' color:
```css
li::marker {
  color: hsl(332,51%,32%);
}
```

I ran into a similar issue when it came to getting a solid bottom border for each row of the table, the border-collapse property helped with this:
```css
table {
  border-collapse: collapse; width: 100%; 
}
table,td{
  border-bottom: 1px solid hsl(30, 18%, 87%);
}
```

This project was also good practice for nth child and marker selectors which I used to change the color of only the second column: 
```css
td:nth-child(2){
    color: hsl(14,45%,36%);
    font-weight: 700;
}
```

### Continued development

This was great practice on using semantic HTML and CSS. I've completed a couple of projects using Vue.js and would like to do similar projects in React in the future.

## Author

- Website - [Portfolio Site](https://amandataylor-portfolio.netlify.app/)
- Frontend Mentor - [@ATaylorN](https://www.frontendmentor.io/profile/ATaylorN)
- GitHub - [@ATaylorN](https://github.com/ATaylorN)
- LinkedIn - [@amanda-taylor1](https://www.linkedin.com/in/amanda-taylor1/)
