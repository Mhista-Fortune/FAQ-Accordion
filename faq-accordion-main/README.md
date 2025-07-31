# Frontend Mentor - FAQ Accordion

This is a solution to the [Frontend Mentor FAQ Accordion challenge](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). The goal is to build a responsive FAQ accordion component using HTML, CSS, and JavaScript.

## Table of Contents

- [Overview](#overview)
- [Screenshot](#screenshot)
- [Built With](#built-with)
- [Features](#features)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [How It Works](#how-it-works)
- [Responsive Design](#responsive-design)
- [Attribution](#attribution)

---

## Overview

This project is a simple FAQ accordion card. Users can click on each question to expand or collapse the answer. Only one answer is visible at a time. The design is responsive and adapts to both desktop and mobile screens.

## Screenshot

![FAQ Accordion Screenshot](./screenshot.png)

## Built With

- Semantic **HTML5**
- **CSS3** (Custom properties, Flexbox, Media Queries)
- Vanilla **JavaScript**
- [Google Fonts - Work Sans](https://fonts.google.com/specimen/Work+Sans)

## Features

- Responsive layout for desktop and mobile
- Smooth accordion transitions
- Only one FAQ open at a time
- Accessible: uses `aria-expanded` for toggle buttons
- Customizable with CSS variables

## Getting Started

To get a local copy up and running follow these simple steps:

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/faq-accordion-main.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd faq-accordion-main
   ```

3. **Open `index.html` in your browser**

No build tools or dependencies are required.

## Folder Structure

```
faq-accordion-main/
├── index.html
├── style.css
└── README.md
```

## How It Works

- The FAQ section is made up of `.faq-item` elements.
- Clicking a question toggles its answer open and closes any other open answer.
- The toggle icon (`+` or `−`) and color update based on the open state.
- The accordion uses CSS transitions for smooth opening/closing.
- On mobile, FAQ questions wrap to multiple lines for readability.

## Responsive Design

- **Desktop:** The FAQ card is centered with a max width and a decorative background.
- **Mobile:** The card shrinks to fit the screen, and question text wraps as needed.

## Attribution

Challenge by [Frontend Mentor](https://www.frontendmentor.io?ref=challenge).  
Coded by [Your Name Here](#).

---

Feel free to use, modify, and share this