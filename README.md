# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![desktop preview](./desktop.png)


### Links

- Solution URL: [Frontend Mentor]()
- Live Site URL: [GitHub Pages]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

In this project, I learned how to make cards by wrapping the cards in a ``<ul>``. Add `box-shadow` on the card is shown on hover and pressing TAB on keyboard to move to different cards. 

 HTML and CSS Snippets below:

```html
<ul>
  <li>
    <article></article>
  </li>
</ul>
```
```css
.card__list-item:is(:hover, :focus-within) {
  box-shadow: 0 0 0 0.25rem;
}
```

### Useful resources

- [Cards](https://inclusive-components.design/cards/) - I used this article to help me build the cards in the Bento grid layout.


## Author

- Frontend Mentor - [@bccpadge](https://www.frontendmentor.io/profile/bccpadge)
- LinkedIn - [@rebeccapadgett121](https://www.linkedin.com/in/rebeccapadgett121/)



## Acknowledgments

[Bento grid solution](https://villager88.github.io/cwrap-bento-grid/) - This solution helped me with the bento grid layout and CSS styles for titles.