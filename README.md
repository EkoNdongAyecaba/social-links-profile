# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of the solution](./preview.png)

### Links

- Solution URL: [Repository](https://github.com/EkoNdongAyecaba/social-links-profile)
- Live Site URL: [Social links](https://ekondongayecaba.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned many things about CSS with this project, things like:

- Create variables in CSS

```css
* {
  --green-color: hsl(75, 94%, 57%);
  --white-color: hsl(0, 0%, 100%);
  --grey-700-color: hsl(0, 0%, 20%);
  --grey-800-color: hsl(0, 0%, 12%);
  --grey-900-color: hsl(0, 0%, 8%);
}
```

- How to use a customized font-family

  To use a customized font-family in your CSS, you can use the `@font-face` rule to define the font and its source. Here's an example:

  ```css
  @font-face {
    font-family: "Inter";
    src: url("assets/fonts/Inter-VariableFont_slnt\,wght.ttf");
  }
  ```

After defining the font, you can apply it to your elements using the `font-family` property:

```css
body {
  font-family: "Inter", sans-serif;
}
```

This will apply the "Inter" font to the entire body of your document. Make sure the path to your font file is correct.

- Learned how to use `div`property

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```

- Learn the new `CSS` syntax

```css
.social-links {
  padding: 20px;
  & p {
    font-weight: 400;
    margin-bottom: 7px;
  }
  & a {
    text-decoration: none;
    color: var(--white-color);
    font-weight: 600;
  }
  .links {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    margin-top: 1rem;
  }
}
```

### Useful resources

- [Net Ninja](https://www.youtube.com/watch?v=k7mBXzv7trQ&list=PL4cUxeGkcC9hH1tAjyUPZPjbj-7s200a4&index=7&ab_channel=NetNinja) - It helped me to understand how to use customized fonts. I really liked this pattern and will use it going forward.
- [Frontend mentor](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) - This helped me to write and submit this solution.

## Author

- Frontend Mentor - [@EkoNdongAyecaba](https://www.frontendmentor.io/profile/EkoNdongAyecaba)
- Twitter - [@Sir Benjamin SHIITAKE](https://x.com/Shiitake_EGBM)
