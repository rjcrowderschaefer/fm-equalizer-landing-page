# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements (iOS and Android download buttons)

### Screenshot

![Mobile](https://i.imgur.com/sFmZ4rE.png)
![Tablet](https://i.imgur.com/BUVSUML.png)
![Desktop - Top](https://i.imgur.com/EuEWSGI.png)
![Desktop - Bottom](https://i.imgur.com/hq55NLF.png)
![Desktop - Hover iOS button](https://i.imgur.com/IWb41rt.png)
![Desktop - Hover Android button](https://i.imgur.com/IndItH7.png)

### Links

- [GitHub Repo](https://github.com/rjcrowderschaefer/fm-equalizer-landing-page)
- [Live Site URL](https://main--prismatic-pasca-d19214.netlify.app/)

## My process

I used a mobile first approach when developing the site, beginning with the mobile layout and expanding to the tablet and desktop layouts. Using the mobile first approach, I was able to adjust for other screen breakpoints with as little additional code as possible. Where possible I used semantic HTML, including the primary grid areas of the site (header, article, aside, footer).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was a great project to practice my use of CSS Grid when developing a site across multiple breakpoints. I also was able to practice how to best use the CSS position declaration -- when to use relative vs absolute and how the two values complement each other to achieve the desired result. Through this project I also had the opportunity to continue working with SVGs and once again leveraged the viewBox property to adjust the SVG size as necessary.

To see how you can add code snippets, see below:

```css
.content-container {
  display: grid;
  grid-template-areas:
    "header header header"
    "article article article"
    "aside aside aside"
    "footer footer footer";
  grid-auto-rows: min-content;
  grid-template-columns: repeat(3, 1fr);
  height: 100vh;
  margin: 0;
  overflow-x: hidden;
}
```
<!-- I was pleased with how I approached the development using CSS Grid and successfully troubleshooting some spacing issues using the 'fr' value -->

### Continued development

I'm still learning how to best design for mobile so that the additional breakpoints (in this case, tablet and desktop) are accounted for as much as possible. This was definitely the case with how I implemented the black background on the site, having to adjust the code across all breakpoints when I realized what worked for the mobile layout won't work for the other breakpoints.

I also need to continue to troubleshoot how certain elements with the position:absolute declaration applied adjust dynamically as the screen width increases and decreases -- primarily in between the 3 major breakpoints.

## Author

- LinkedIn - [RJ Crowder-Schaefer](https://www.linkedin.com/in/rjcrowderschaefer/)
- Frontend Mentor - [@rjcrowderschaefer](https://www.frontendmentor.io/profile/rjcrowderschaefer)
- GitHub - [@rjcrowderschaefer](https://github.com/rjcrowderschaefer)
