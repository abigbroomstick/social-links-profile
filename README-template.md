# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

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
This is a front-end challenge from Frontend Mentor. The task is to build out an social link profile and to make it as similar as possible to the original design.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop](./Screenshot%20(desktop).png)
![Active](./Screenshot%20(active).png)
![Mobile](./Screenshot%20(mobile).png)


### Links

- Solution URL: [https://github.com/abigbroomstick/social-links-profile](https://github.com/abigbroomstick/social-links-profile)
- Live Site URL: [https://abigbroomstick.github.io/social-links-profile/](https://abigbroomstick.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Pure CSS

### What I learned

I learned how to work faster with Flexbox & Media Queries and could use them more comfortably now.

```html
<h1>I am very proud to make these buttons :D</h1>
<div class="btn-container">
        <a class="btn" title="Visit GitHub" target="_blank" href="https://github.com/abigbroomstick">GitHub</a>
        <a class="btn" title="Visit FrontendMentor" target="_blank" href="https://www.frontendmentor.io/profile/abigbroomstick">Frontend Mentor</a>
        <a class="btn" title="Visit LinkedIn" target="_blank" href="https://www.linkedin.com/in/albert-nguyen-380218270/">LinkedIn</a>
        <a class="btn" title="Visit Twitter X" target="_blank" href="https://x.com/AlbertN38734367">Twitter</a>
        <a class="btn" title="Visit Instagram" target="_blank" href="#Instagram">Instagram</a>
</div>
```
```css
.proud-of-this-css {
  .btn {
   background-color: hsl(0, 0%, 20%);
   text-decoration: none;
   color: white;
   font-weight: 600;
   text-align: center;
   border-radius: 5px;
   padding: 15px;
   font-size: 0.875rem;
   transition: background-color 0.2s ease-in-out, color 0.2s;
}

.btn:hover, .btn:focus {
    cursor: pointer;
    background-color: hsl(75, 94%, 57%);
    color: hsl(0, 0%, 20%)
}
}
```
### Continued development

I still want to refine and perfect my skills using Flexbox so I will practice using it more in the future.

### Useful resources

- [How to take control of Flexbox](https://youtu.be/Ns12ALe8aqI?si=eq2fQFD8bN3mjDHq) - Shout out to Kevin Powell for providing such useful videos on how to work with Flexbox or just anything web development related.

## Author

- Github - [@abigbroomstick](https://github.com/abigbroomstick)
- Frontend Mentor - [@abigbroomstick](https://www.frontendmentor.io/profile/abigbroomstick)
- Facebook - [@Nam Nguyen](https://www.facebook.com/nam.nguyenbathanh/)

## Acknowledgments

Ashleynguci- she gave me huge motivation to learn web development :D
Colt Steele- best Udemy Front-End class I've taken so far
Nheo Hi- my lovely girlfriend who puts up with me every time I stayed up late to code.
