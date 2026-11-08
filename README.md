# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)



## Overview


### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot
![alt text](image.png)

### Links

- Solution URL: [https://github.com/Nnbq/block-preview-card]
- Live Site URL: [https://nnbq.github.io/block-preview-card/]

## My process

### Built with

- Semantic HTML5 markup
- Flexbox


### What I learned

During this project, I practiced working with Flexbox to align elements and learned how to properly center a card vertically in the viewport while keeping the footer pinned at the bottom. 

One specific CSS trick I'm proud of is using `margin: auto 0` on the card inside a column-direction flex container to achieve perfect vertical centering:

```css
body {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-height: 100vh;
}

.card {
    margin: auto 0; 
}
```

### Continued development

In future projects, I want to continue focusing on:
- Improving my understanding of Responsive Web Design using media queries to make sure designs look great on mobile phones, tablets, and desktop screens.
- Practicing more advanced CSS Layouts like CSS Grid to expand beyond Flexbox.
- Writing cleaner, more semantic HTML structure from the start.


### AI Collaboration

During this project, I worked closely with an AI assistant to build and structure the layout using Flexbox.


- I used (Gemini)
- I used the AI to help me write, understand, and debug all the Flexbox code. It guided me through setting up the flex containers, understanding main and cross axes, aligning items, and fixing layout challenges 
- What worked well? What didn't?
  - Worked well: The AI broke down complex CSS layout logic into easy, understandable steps and visual explanations. Instead of just copying code, I actually learned how and why Flexbox behaves the way it does.
  - Didn't work well: There were minor alignment adjustments needed along the way, but problem-solving them together made my understanding much stronger.


## Author

- Website - [Shahad](https://www.your-site.com)
- Frontend Mentor - [@Nnbq](https://www.frontendmentor.io/profile/Nnbq)



