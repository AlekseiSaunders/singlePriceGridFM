# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Single price grid component solution](#frontend-mentor---single-price-grid-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
      - [Desktop](#desktop)
      - [Mobile](#mobile)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot
#### Desktop
![](./images/Frontend%20Mentor%20_Single%20Price%20Grid%20Component_Desktop.png)
#### Mobile
![](./images/Frontend%20Mentor_Single%20Price%20Grid%20Component_Mobile.png)

### Links

- Solution URL: [Found at Github](https://github.com/AlekseiSaunders/singlePriceGridFM)
- Live Site URL: [Hosted at Vercel](https://single-price-grid-fm-git-main-alekseisaunders.vercel.app/)

## My process

I start with reviewing the design products, in this case a Figma file with desktop and mobile mock-ups. I'm looking first for low-hanging fruit: colors, typeface, general layout. For larger projects, if the design files don't have a Design System board already, I'd seriously consider creating one for myself. I've found that this front-end work makes the styling easier down the line. Looking at the designs closely enough to create a MD board also gets me looking at some of the smaller detials.

Next I either clone the respository into a project folder, or I create my own git repository. Rename master to main if it hasn't already been done, create a gitignore to remove packages, certain assests, and anything proprietary from the public repo. Put on some relaxing music, and start VS Code.

In VS Code I first create a boilerplate reset.css file (I use a modified version of [Andy Bell's reset](https://piccalil.li/blog/a-modern-css-reset/)). From there I create a main.css and begin creating the Custom Properties I'll need for the page by looking at either the Design System board, or my notes.

Once Custom Properties are done, I'll move onto creating Utility Classes if I'm using them for the project. If the HTML file is empty, this is the point at which I'll begin creating the base HTML. Starting with boilerplate HTML, linking to the style sheets, linking to any cdn for fonts, icons, etc. I'll make an effort to use semantic HTML, but the goal here is to get the skeleton done and start seeing the style come together. I'll keep accessibility in mind here as well.

I'm currently reading [Better Web Typography For A Better Web - by Matej Latin](https://betterwebtype.com/web-typography-book/) and he has convinced me to use actual, subject aligned text during styling, rather than Lorem Ipsum filler, to monitor how the typefaces are looking on the screen. If I need to write copy to help fill out the design, I'll keep Matej's recommendations in mind while doing so.

At this point I move the larger HTML components into the positioning system that makes the most sense to the design. Flexbox, Grid, a mix of the two, Flow if it is fairly simple. I'll start at the smaller viewports size and, moving back-and-forth between CSS and HTML work through large styling to smaller and smaller touches. 

Once I have the major, and some minor, elements matching the design specifications, I'll switch to the larger viewport sizes. This point is a little nebulous as it depends on whether I think I've covered all the components that might shift layout with additional styling. It can seem impossinle to avoid later surprises while styling for larger viewports, but I'd like to minimize any retooling I'd need to do later.

Often this stage requires media queries to get everything looking as it should. I'll test the flow between stages so that the transition isn't too jarring, although I sometimes wonder if it is really only designers and developers that slide back-and-forth between viewports in a session.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Figma
- VSCode

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Josh W. Comeau](https://www.joshwcomeau.com/) - Josh explains aspects of CSS that have really clicked with me and I'm finding his CSS course challenging, but well worth the expense for the insight he brings.
- [Kevin Powell goes through his CSS process](https://scrimba.com/learn/spacetravel/introduction-co9754ea5b87864fba221a504) - This is a free tutorial on Scrimba, in conjunction with Frontend Mentor that really clicked with me. I liked Kevin's approach to CSS development and hope to adapt my own flow along these lines. I'm now watching more and more of [Kevin's thought process on YouTube](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw)
- [Better Web Typography For A Better Web - by Matej Latin](https://betterwebtype.com/web-typography-book/) - Most of the copy is written already in these Frontend Mentor challenges. It has been interesting to compare what Matej would recommend vs what the design spec's indicate in regards to typeface usage and spacing. Switching back and forth between requested and recommended styles had been informative.

## Author

- Website - [Aleksei Saunders](https://www.your-site.com)
- Frontend Mentor - [@AlekseiSaunders](https://www.frontendmentor.io/profile/AlekseiSaunders)
- LinkedIn - [Aleksei Saunders](https://www.linkedin.com/in/alekseisaunders/)
