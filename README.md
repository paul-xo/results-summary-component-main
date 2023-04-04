# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/screenshots/desktop%20design.png)
![](./assets/screenshots/active%20states.png)
![](./assets/screenshots/mobile%20design.png)

### Links

- Solution URL: [Click here to view my solution URL](https://your-solution-url.com)
- Live Site URL: [Click here to view my live site URL](results-summary.pages.dev)

## My process

I created a main tag a and i divided it into two parts. The first part for the results and the second part for the summary. I had issues with chhosing the right colour for the boxes so i went on youtube to watch a tutorail video of selcting the right colours.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt how to create a perfect circle with a div tag and how to use variables and color gradients.

```html
<div class="row">
  <div class="badge">
    <img src="assets/images/icon-reaction.svg" alt="icon-reaction" />
    <p>Reaction</p>
  </div>
  <p><b>80</b> / 100</p>
</div>
```

```css
.circle {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background: linear-gradient(
    to bottom,
    var(--Violet-blue-circle),
    var(--Persian-blue-circle)
  );
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  line-height: 3rem;
}
.circle h2 {
  font-size: 60px;
  color: var(--White);
  margin-top: 2rem;
}
.circle p {
  color: var(--Light-lavender);
}
```

### Continued development

- All HTML and CSS challenges on frontend mentor
- Portfolio

### Useful resources

- [Youtube](https://www.youtube.com/watch?v=Hd3QVIwul3s) - This helped me in choosing the right colors to use and understanding how to use variables and color gradient. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@paul-xo](https://www.frontendmentor.io/profile/paul-xo)
- GitHub - [@paul-xo](https://www.twitter.com/paul-xo)

## Acknowledgments

I went to "code with ali" youtube's channel to leanr and understand how to build my deign and it helped me alot. Thanks!
