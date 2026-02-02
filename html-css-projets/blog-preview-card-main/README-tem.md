# Frontend Mentor - Blog Preview Card

This is my solution to the [Blog Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). This project helped me practice **HTML, CSS, Flexbox, and responsive design** using a real-world card layout.

---

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

---

## Overview

### The challenge

Build a **blog preview card** that is visually close to the design. Users should be able to:

- See hover and focus states for all interactive elements (links, buttons).  
- Experience a responsive layout for **mobile-first design**.  

The card includes:  
- Article image  
- Badge (category)  
- Published date  
- Title with hover/focus effect  
- Short description  
- Author avatar + name  

---

### Screenshot

![Screenshot of the Blog Preview Card](./preview.jpg) 


---

### Links

- Solution URL: [GitHub Repository](https://github.com/yauwalu94/frontend-mentor-projects/tree/main/html-css-projets/blog-preview-card-main)  
- Live Site URL: [Deployed Project](https://blog-preview-card-htmlcss.netlify.app/)  

---

## My process

### Built with

- Semantic HTML5  
- CSS custom properties  
- Flexbox  
- Mobile-first workflow  
- Responsive layout  
- Google Fonts: [Figtree](https://fonts.google.com/specimen/Figtree)  

---

### What I learned

During this project, I focused on **clean layout and spacing**. Key takeaways:

- **Image wrapper** to control left/right spacing while keeping the image responsive:

```css
.card_img_wrapper {
  padding: 20px;
}

.card_img {
  width: 100%;
  display: block;
  border-radius: 10px;
}
```
- Used Flexbox to align the avatar and author name inline with proper spacing:
```
.card_avatar {
  display: flex;
  align-items: center;
  gap: 0.75rem;
}
```
- Implemented hover and focus-visible states for links to improve accessibility.
- Practiced mobile-first design with a card that scales on different screen sizes.

## Continued development

- Learn to refactor the card into a reusable component in React or another framework.
- Add micro-interactions like subtle hover effects on the card itself.
- Experiment with CSS Grid to create more complex layouts for multiple cards.

## Useful resources

- Frontend Mentor Blog Preview Card Challenge([Official challenge.](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS))

- Google Fonts: Figtree ([Used for typography](https://fonts.google.com/specimen/Figtree))

– Helped with avatar alignment ([Helped with avatar alignment](https://css-tricks.com/snippets/css/a-guide-to-flexbox/))


# Author

    Name: Yahaya Auwalu
    GitHub: @yauwalu84
    LinkedIn: Yahaya Auwalu

#Acknowledgments

   - Frontend Mentor for providing the challenge and design files.
   - Myself for experimenting with responsive design, Flexbox, and proper spacing.