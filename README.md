# Frontend Mentor - QR code component solution
This is a solution to the [Social Links Profile Card](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [Overview](#overview)
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
This project is a Frontend Mentor challenge solution where the goal was to build a simple, responsive webpage that displays a Social Links Profile card. The card includes a profile image with short descriptive text underneath and 5 hyperlink buttons below that. The focus of the project was on HTML structure, and CSS styling.
The project also demonstrates basic Git and GitHub workflow, including adding and updating files such as HTML, CSS, and images.
This simple project is a great exercise in layout, styling, and design precision, making it ideal for practicing frontend fundamentals.


### Screenshot
Here is a link to the images of my final solution:

- [Desktop View](images/final-desktop.png)
- [Mobile View](images/final-mobile.png)


### Links
Live Site URL: 
(https://fm-challenge-3-six.vercel.app/)


## My process
- I started off with adding the HTML to the document. This was a quick and simple process as it only required a elements, link the CSS to the HTML, adding the image, and using semantic elements.
- I then moved on to my CSS.
- Finally, I put it all together to be the final solution (seen in the links above).

### Built with
- HTML5 markup
- CSS custom properties
- Bootstrap CSS Framework
- Flexbox
- Media Queries


### What I learned
For this challenge I decided to learn Bootstrap as a CSS framework. I took this challenge more as a playground to test what I learned and what I could apply in the challenge. I really wasn't expecting to work, but with constant refinement - and 4 hours of work - I actually somehow managed to get it to work.

There was a lot this time that I learnt, both theoretically and practically. 

- I learnt that Bootstrap is built/based on Flexbox (or on the basis of it).
- I learnt that you can't override Bootstrap classes (realised this when i tried to set breakpoints with media queries).
- I learnt that Bootstrap is hacks (lol, no I'm joking). I learnt that Bootstrap uses predefined/preconfigured styles for CSS. I learnt how to apply the CSS into my HTML and CSS, how to edit the predefined class styles, how to copy the code from the Bootstrap official website, etc.
- I also learnt about TailwindCSS, which I've set out in a challenge for myself later on when I feel more comfortable with Flexbox and Bootstrap.
- I learnt a simple little shortcut for implementing a div with a class in html: '.class name' --> Obviously without the inverted comma's.

Integrating Bootstrap:
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
```

Using breakstops in CSS and overriding the Bootstrap:
```css
@media (min-width: 1440px){
    #lg-card{
        width: 400px; 
    }

    #location{
        font-size: 1rem;
    }

    #user-info{
        font-size: 1rem;
    }
}
```

Neat shortcut: 
- .class-name  ---> this will provide the following output:
```html
<div class="class-name"></div>
```
- #id-name  ---> this will provide the following output:
```html
<div id="id-name"></div>
```


### Continued development
I really enjoyed Challenge 3, especially using flexbox again, and setting out the challenge for myself to learn about other things like CSS frameworks (such as Bootstrap and TailwindCSS). I also recently connected with someone who has a lot more experience than myself, I learnt about PHP, Pagebreeze, and a few other things. My main focus now is just continuing to learn more about Bootstrap, more practice with Flexbox, Media Queries, breakpoints, ':before' & ':after', and the whole shabang. I'm really enjoying myself, and I admire my growth and continued dedication to learning. Although, in a few more days I'm going to get really busy again with classes so I'm going to try my best to stay consistent with learning, networking, and building up my portfolio and GitHub.


### Useful resources
- [Bootstrap 5 Crash Course - Web Dev Simplified](https://youtu.be/Jyvffr3aCp0)
- [Bootstrap Official Website](https://getbootstrap.com)
- [What is Bootstrap? / Beginner CSS Framework - Liz Rowe](https://youtu.be/MyCvTSjkD74)

Overall useful videos, very good introduction into the Bootstrap framework.

## Author
- LinkedIn - [Ashton Blaze Berridge](https://www.linkedin.com/in/ashton-berridge-6ba4ab255/)
- Frontend Mentor - [@ashyb13](https://www.frontendmentor.io/profile/ashyb13)
- GITHUB - [@ashyb13](https://github.com/ashyb13)


## Acknowledgments
I took this project on my own, but I do give credit to those mentioned in the [Useful resources](#useful-resources)
