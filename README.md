# Frontend Mentor - Skilled e-learning landing page

![Design preview for the Skilled e-learning landing page coding challenge](./preview.jpg)

## Welcome! 👋

Thanks for purchasing this premium Frontend Mentor coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects. These premium challenges are perfect portfolio pieces, so please feel free to use what you create in your portfolio to show others.

**To do this challenge, you need a decent understanding of HTML and CSS.**

## The challenge

Your challenge is to build out this landing page and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

Want some support on the challenge? [Join our Slack community](https://www.frontendmentor.io/slack) and ask questions in the **#help** channel.

## Where to find everything

Your task is to build out the project to the design file provided. We provide both Sketch and Figma versions of the design, so you can choose which tool you prefer to use. You can download the design file on the platform. **Please be sure not to share them with anyone else.** The design download comes with a `README.md` file as well to help you get set up.

All the required assets for this project are in the `/assets` folder. The assets are already exported for the correct screen size and optimized. Some images are reusable at multiple screen sizes, some are for specific layouts. We also include WEBP and PNG versions and different resolutions of the hero image, so you can choose to use whichever format and resolution you like or even look into letting the browser choose which image to use based on specific conditions. For this, you can look into [responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) to learn more.




 [have a read-through of this Try Git resource](https://try.github.io/). **⚠️ IMPORTANT ⚠️: There are already a couple of `.gitignore` files in this project. Please do not remove them or change the content of the files. If you create a brand new project, please use the `.gitignore` files provided in your new codebase. This is to avoid the accidental upload of the design files to GitHub. With these premium challenges, please be sure not to share the design files in your GitHub repo. Thanks!**


## Create a custom `README.md`

We strongly recommend overwriting this `README.md` with a custom one. We've provided a template inside the [`README-template.md`](./README-template.md) file in this starter code.

The template provides a guide for what to add. A custom `README` will help you explain your project and reflect on your learnings. Please feel free to edit our template as much as you like.

Once you've added your information to the template, delete this file and rename the `README-template.md` file to `README.md`. That will make it show up as your repository's README file.

## Submitting your solution

Submit your solution on the platform for the rest of the community to see. Follow our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) for tips on how to do this.

Remember, if you're looking for feedback on your solution, be sure to ask questions when submitting it. The more specific and detailed you are with your questions, the higher the chance you'll get valuable feedback from the community.

**⚠️ IMPORTANT ⚠️: With these premium challenges, please be sure not to upload the design files to GitHub when you're submitting to the platform and sharing it around. If you've created a brand new project, the easiest way to do that is to copy across the `.gitignore` provided in this starter project.**

## Sharing your solution

There are multiple places you can share your solution:

1. Share your solution page in the **#finished-projects** channel of the [Slack community](https://www.frontendmentor.io/slack). 
2. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor**, including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.
3. Share your solution on other social channels like LinkedIn.
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.


**Have fun building!** 🚀
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



### Links

- Solution URL: [github]()
- Live Site URL: [vercel]()

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

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.



### Useful resources

- [caniuse](https://caniuse.com/) - This site helped me with understanding which browsers had the strongest support for the picture tag.

- [webdesign.tutsplus](https://webdesign.tutsplus.com/tutorials/quick-tip-how-to-use-html5-picture-for-responsive-images--cms-21015) - This is an amazing article which helped me finally understand when to approach making an image responsive with img tag included with sizes and srcset, and when to use the approach of the picture tag with the img, srcset, and media included inside the source tag inside the picture tag element.


## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@EricAguayo90](https://www.frontendmentor.io/profile/EricAguayo90e)
- Twitter - [@DevEric90](https://www.twitter.com/DevEric90)
