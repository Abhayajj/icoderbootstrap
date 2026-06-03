# iCoder | Premium Developer Community Platform

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Bootstrap Version](https://img.shields.io/badge/bootstrap-5.3.3-blue.svg)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Welcome to **iCoder**, a premium, production-ready, fully responsive developer community platform designed for modern programmers. Built using Bootstrap 5.3.3 and custom advanced CSS, this platform offers a sleek glassmorphic layout, dynamic light/dark theme persistence, and interactive widgets. It is optimized to showcase software engineering skills, clean semantic structures, and polished UX design in a professional portfolio.

## 🚀 Live Preview & Interactive Features

- **Dynamic Theme Switcher**: Automatically load and persist user-selected dark or light modes across page loads using `localStorage`.
- **Interactive Coding Trivia**: A custom JavaScript-driven coding trivia widget on the landing page that dynamically loads questions, handles answer validations (visual red/green cues), and keeps score.
- **Client-Side Live Filtering & Search**: Instant filter widgets on the projects directory allowing search queries and tag filters (`Web Dev`, `Python`, `AI/ML`, `Cloud`) to hide/show cards dynamically with zero-page-reload.
- **Bootstrap 5 form validation**: Full client-side error validation with native input feedback on the Contact page.
- **Advanced Glassmorphic Styling**: Elegant custom CSS rules (`style.css`) leveraging CSS variables, overlay borders, and lift hover micro-animations to deliver a modern, state-of-the-art developer brand look.

## 🛠️ Technology Stack

- **Structure**: HTML5 (Semantic elements, metadata optimization for SEO, responsive layouts).
- **Styling**: Bootstrap v5.3.3 (CDN), custom CSS variables, Google Fonts (Inter & Outfit).
- **Interactions**: Vanilla JavaScript (ES6+).
- **Icons**: FontAwesome v6.4.0.
- **Dev Tooling**: Node.js & `lite-server` for instant hot-reload local development.

---

## 📂 Project Structure

```text
├── index.html          # Landing page (Hero, Stats, Trending Topics, Quiz Widget)
├── about.html          # Our journey timeline & creator profile card
├── projects.html       # Featured carousel, live search & tag filtering projects grid
├── contact.html        # Responsive two-column contact details & validation form
├── style.css           # Custom theme variables, styles, and animation tokens
├── package.json        # Project setup scripts & local server configurations
└── .gitignore          # Excludes temporary cache and build dependencies
```

---

## 💻 Getting Started Locally

To run and preview this project on your local system, follow these simple steps:

### 1. Clone the Repository
```bash
git clone https://github.com/Abhayajj/icoderbootstrap.git
cd icoderbootstrap
```

### 2. Install Development Dependencies
Make sure you have [Node.js](https://nodejs.org/) installed, then run:
```bash
npm install
```

### 3. Run the Development Server
Launch the local dev server with automatic reload:
```bash
npm run dev
```
The application will open automatically in your browser at `http://localhost:3000` (or another port outputted in the terminal).

---

## 🙋‍♂️ Author & Community
Crafted with passion by **[Abhay Gupta](https://github.com/Abhayajj)**. Connect with me on:
- **GitHub**: [github.com/Abhayajj](https://github.com/Abhayajj)
- **LinkedIn**: [Abhay Gupta](https://linkedin.com)

Feel free to open issues or pull requests to suggest additions, topics, or formatting improvements!