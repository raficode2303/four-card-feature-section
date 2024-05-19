# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: [github](https://github.com/raficode2303/four-card-feature-section.git)
- Live Site URL: [Netlify](https://four-card-feature-section-flip.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Solution retrospective

- What are you most proud of, and what would you do differently next time?
  to solve the challenge without using `@media`, next time i try to make the cards carousel.

- What challenges did you encounter, and how did you overcome them?
  HOW TO MAKE FLEX ITEMS EQUAL WIDTH? i overcome it by reading an article of Kevin Powell about this issue.

- What specific areas of your project would you like help with?
  to learn new ways of best practices for challenges like this.

### What I learned

- FireFox’s DevTools advantages
- to maneuver between flex and grid
- The `<i>` and `<span>` elements are widely used to add icons.

```css
.card {
  box-shadow: 0px 0px 10px 0px var(--grayish-blue, gray);
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

## Acknowledgments

Kevin Powell
[Equal Columns With Flexbox: It’s More Complicated Than You Might Think](https://css-tricks.com/equal-columns-with-flexbox-its-more-complicated-than-you-might-think/#top-of-site)

- explain why `flex: 1` causes a problem in cases of borders or padding on some elements, and how to solve it.
