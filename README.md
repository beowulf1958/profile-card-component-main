# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop Screenshot](./Screenshot%20Frontend%20Mentor%20Profile%20card%20component.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://magenta-pika-8e1eb0.netlify.app/)

## My process

I normally work locally, trying different approaches before creating a github repo, but this time I started from the Destop Github. I am still not 100% comfortable with github, but it's great for publishing on Netlify.
I think in the future I need to find a more organized approach to planning out my projects, rather than just spit-balling and hoping for the best. That said, I am fairly happy with the outcome, although I think the svg's in the background are not quite right.

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I started out with CSS grid, hoping to be able to place my items where I wanted them, but could not get the grid to behave when the screen resized. So I went old school and simplified with position:relative and a negative top, which overlapped the avatar nicely.

see below:

```css
.avatar {
  border-radius: 50%;
  position: relative;
  top: -2rem;
}
```

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)
