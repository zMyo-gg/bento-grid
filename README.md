# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Steps I followed](#steps-i-followed)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements
- Experience a responsive design that adapts from mobile (375px) to desktop (1440px) screens

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid for layout
- CSS Flexbox for component alignment
- Mobile-first responsive design
- DM Sans font family (weights: 400, 500)
- CSS custom properties (HSL color variables)
- Media queries for responsive breakpoints

### Steps I followed

- First, I analyzed the preview.jpg image and style-guide.md to understand the exact Bento Grid layout, color palette, and typography requirements.
- I structured the HTML using semantic elements (`<article>` for cards, `<main>` for grid container) following accessibility best practices.
- I implemented a 4-column CSS Grid as the primary layout for desktop screens, with strategic `grid-area` positioning for each card to create the Bento Grid pattern.
- I styled all cards according to the design specifications, using the color palette provided: Purple 500 and 100 for primary accents, Yellow 500 and 100 for secondary accents, with proper contrast for text.
- I added comprehensive responsive design with two main breakpoints:
  - **Tablet (768px):** Grid adjusts to single column with proper card stacking
  - **Mobile (375px and below):** All cards stack vertically, with optimized typography and spacing
- I implemented a third breakpoint for ultra-mobile devices (275px) to ensure the design remains readable on very small screens.
- I added hover and focus states for interactive elements to enhance user experience and accessibility.

### What I learned

- **CSS Grid Advanced Usage:** I deepened my understanding of CSS Grid's `grid-area` property for complex layouts. This approach is more flexible than using `grid-column` and `grid-row` for intricate designs like Bento Grid patterns.
- **Responsive Design Challenges:** Building a layout that works seamlessly across 275px to 1440px screens required careful planning of breakpoints and fluid typography scaling.
- **Mobile-First Workflow:** Starting with mobile and progressively enhancing the design for larger screens led to a more maintainable and performance-friendly codebase.
- **Color Contrast & Accessibility:** Using HSL color values from the style guide and ensuring proper contrast ratios between text and backgrounds is crucial for accessibility and readability.

### Continued development

- Implement smooth transitions and animations when cards appear on the page for a more polished feel
- Add interactive hover effects with subtle scale and shadow changes to improve user feedback
- Consider adding JavaScript to dynamically adjust grid areas based on user preferences or screen orientation changes
- Explore CSS variables more deeply to create a design system that scales better across projects
- Optimize images with modern formats (WebP) and lazy loading for improved performance

### Useful resources

- [MDN CSS Grid Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - This comprehensive guide helped me master CSS Grid positioning and `grid-area` syntax.
- [MDN Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - Essential concepts for creating mobile-first, responsive layouts.
- [Frontend Mentor Style Guide](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj) - Provided exact color values, typography rules, and layout specifications.
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Quick reference for flexbox properties used in card alignment.
- [CSS Grid Generator](https://cssgrid-generator.netlify.app/)

## Author

- Frontend Mentor - [zMyo-gg](https://www.frontendmentor.io/profile/zMyo-gg)
- Twitter/X - [zMyo_gg](https://x.com/zMyo_gg)
- GitHub - [zMyo-gg](https://github.com/zMyo-gg)

## Acknowledgments

Thanks to the Frontend Mentor team for providing this challenging project that helped me practice advanced CSS Grid techniques and responsive design principles.
