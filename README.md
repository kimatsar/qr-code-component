# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Screenshot](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/kimatsar/qr-code-component)
- Live Site URL: [GitHub Pages](https://kimatsar.github.io)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to use CSS custom properties, how to import fonts from a CDN, how to include the padding and border _inside_ the specified width using border-box, and how to use the :root selector instead of the body selector.

```css
:root {
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);

  font-family: "Outfit", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
}
```

```css
box-sizing: border-box;
```

### Continued development

I want to continue learning about CSS syntax.

### Useful resources

- [W3Schools](https://www.w3schools.com) - Good CSS reference.
- [TailwindCSS](https://www.tailwindcss.com) - Another good CSS reference.

### AI Collaboration

I used Gemini to ask questions about CSS problems, but I did not copy paste or ask the AI to build the page entirely or build things for me.

## Author

- Website - [GitHub](https://www.github.com/kimatsar)
- Frontend Mentor - [@Kimatsar](https://www.frontendmentor.io/profile/kimatsar)

## Acknowledgments

Thanks everyone
