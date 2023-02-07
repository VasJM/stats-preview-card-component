# Frontend Mentor - Stats Preview Card Component Solution

This is a solution to the [Stats Preview Card Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Stats Preview Card Component - Desktop View](./screenshot.png)

### Links

- [Solution](https://your-solution-url.com)
- [Live Site](https://your-live-site-url.com)

## My process

### Built with

- Love 💖
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- I had my first encounter with a flex-item overflowing its flex-container when using `align-items` and `justify-content`. It was not pleasant to deal with at first, and there were obviously many ways to fix it, which lead me to a cool fix: the keyword `safe`! Unfortunately, this is only supported on 🦊**Firefox** atm (btw, it's the *superior* browser, everybody and their grandma needs to use it) so I needed another solution. I slept on it. Somehow I was able to fix it by simply removing the `align-items: center` from my `.card` class and it worked! I don't know how, but it did!

- I discovered the existence of the `mix-blend-mode` CSS property. At first I thought an image overlay was used, but it didn't look right, and that's when I knew it was time to spend *hours* trying to find out what was the exact CSS property to use here, and well, I spent an embarrassing amount of time researching, but I found it! 

- My Image Responsiveness Knowledge Bank got a new addition: the `object-fit` property. This was another head-scratcher that took a bit to find, but it was super handy when configuring the desktop view of the header image to look just right!

### Continued development

Building responsive websites is still a challenge for me so I'd like to continue working on that, discovering new CSS tricks along the way to ease the process. If I must suffer hours of research for it, then so be it ✌

Also, I need to look into how I fixed my overflow issue...

### Useful resources

- [The "Overflow" Issue](https://stackoverflow.com/questions/33454533/cant-scroll-to-top-of-flex-item-that-is-overflowing-container) - this Stack Overflow (funny, I know) question was a godsent when it came to understanding what problem I was actually facing and how to go about fixing it. Bless them.

- [Mix Blend Mode is the new Beast Mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - who am I without the MDN web docs? Nothing.

- [The Object-Fit Property is *Just Right*](https://www.freecodecamp.org/news/css-responsive-image-tutorial/) - now freeCodeCamp is another great resource that saved my life with this quick and simple tutorial on image responsiveness! Please go [support](https://www.freecodecamp.org/donate/) them, because they are doing God's work 🙏

- Also, while you are still here, do yourself a favour and download [🦊Firefox](https://www.mozilla.org/en-US/firefox/new/). You'll thank me later 💖