# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

```html
<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset = "UTF-8">
        <meta name = "viewport" content = "width=device-width initial-scale = 1.0">
        <link rel = "stylesheet" href = "styles.css">
    </head>
    <body>
        <div class = "right-buttons">
            <h1>Summary</h1>
        
                <button class="a1"></button>
                <button class="a2"></button>
                <button class="a3"></button>
                <button class="a4"></button>
                <button class="continue"><span class="text">Continue</span></button>
            </div>
    </body>
</html>
```css
.right-buttons {
    height: 350px;
    width: 300px;
     margin: auto;
    background: hsl(0, 12%, 97%);
    display: flexbox;
    flex-direction: row;
    border-radius: 30px;
}   

h1 {
    margin-top: 200px;
    position: relative;
    margin-top: 15px;
    margin-left: 30px;
    font-size: 1.5em;
}

button {
    display: flex;
    flex-direction: column;
    height: 10%;
    width: 80%;
    margin: auto;
    border-radius: 10px;
    margin-top: 10px;
    margin-bottom: 10px;
    border: none;
}

### Continued development
Accessibility: I would like to focus on  Accessibility to ensures that websites can be used by people with disabilities. and also focus on creating websites that are accessible to everyone, including those with visual, auditory, and motor impairments.

### Useful resources

- [Example resource 1](https://www.freecodecamp.org/learn/2022/responsive-web-design/) - This helped me for  responsive web design. I really liked this pattern and will use it going forward.
- [Example resource 2](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer) - This is an amazing article which helped me finally understand tables, building blocks, styling text and layout . I'd recommend it to anyone still learning this concept.

## Author

- Website - [Chia Raissa](https://www.linkedin.com/in/chia-raissa-70841619a)
- Frontend Mentor - [@ChiaRaissa](https://www.frontendmentor.io/profile/ChiaRaissa)
- Twitter - [@raissa_chia](https://twitter.com/raissa_chia)

