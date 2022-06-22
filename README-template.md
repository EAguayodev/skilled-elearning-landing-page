# Frontend Mentor - Skilled e-learning landing page solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#skilled-learning-landing-page)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#html5 #css3)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#Eric Aguayo)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



### Links

- Solution URL: [github](https://your-solution-url.com)
- Live Site URL: [vercel](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
 <picture>
          <source srcset="assets/image-hero-desktop.png 1400w,
          assets/image-hero-desktop@2X.png 1200w," 
          media="(max-width: 1440px) and (min-width: 1200px)">
          <source srcset="assets/image-hero-tablet.png 1023w,
          assets/image-hero-tablet@2X.png 1000w, 
          assets/image-hero-tablet.webp 900w, 
          assets/image-hero-tablet@2X.webp 800w" 
          media="(max-width:1023px) and (min-width: 767px)">
          <source srcset="assets/image-hero-mobile.png 767w, 
          assets/image-hero-mobile@2X.png 600w, 
          assets/image-hero-mobile.webp 500w, 
          assets/image-hero-mobile@2X.webp 350w" 
          media="(max-width:767px) and (min-width: 375px)">
          <img class="hero__image" src="assets/image-hero-desktop.png" alt="hero__desktop">
      </picture>
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



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [caniuse](https://caniuse.com/) - This site helped me with understanding which browsers had the strongest support for the picture tag.

- [webdesign.tutsplus](https://webdesign.tutsplus.com/tutorials/quick-tip-how-to-use-html5-picture-for-responsive-images--cms-21015) - This is an amazing article which helped me finally understand when to approach making an image responsive with img tag included with sizes and srcset, and when to use the approach of the picture tag with the img, srcset, and media included inside the source tag inside the picture tag element.


## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@EricAguayo90](https://www.frontendmentor.io/profile/EricAguayo90e)
- Twitter - [@DevEric90](https://www.twitter.com/DevEric90)
