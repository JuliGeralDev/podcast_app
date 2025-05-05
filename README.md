# 🎙️ Podcast App – Responsive Web Design with SASS & Gulp

**Podcast App** is a *study project* developed as part of a Udemy course by Juan Pablo De la Torre Valdez. It is designed as a landing page prototype to demonstrate my skills in web design using **SASS**, **CSS Grid**, and **Flexbox**. This is not a functional application, but a design-focused exercise to showcase responsive layouts and front-end architecture. The project also integrates **Gulp** for task automation.

## 🔗 Live Preview

[👉 View the Demo on Netlify](https://podcast-app-dev.netlify.app/)

## 📁 Project Structure

The project is organized as follows:

├── gulpfile.js  
├── package.json  
├── build/  
│   ├── css/  
│   ├── img/  
├── src/  
│   ├── img/  
│   ├── js/  
│   ├── scss/  
│       ├── base/  
│       │   ├── _globales.scss  
│       │   ├── _variables.scss  
│       │   ├── _mixins.scss  
│       ├── ui/  


## ✨ Features

- **Responsive Design:** Built with CSS Grid and Flexbox for a seamless experience across devices.  
- **SASS Architecture:** Modular SASS files for better maintainability and scalability.  
- **Image Optimization:** Uses Gulp to optimize images

- **Task Automation:** Gulp automates tasks like compiling SASS, optimizing images, and watching for changes during development.

## ⚙️ Installation

1. Clone the repository:  
   `git clone <repository-url>`  
   `cd podcast_app`  

2. Install dependencies:  
   `npm install`  


## 🧪 Development

To start the development process and watch for changes, run:  
`npm run dev`  

This will:  
- ✅ Compile SASS files into CSS  
- ✅ Optimize images  
- ✅ Watch for changes in `src/scss` and `src/img`  

## 🎨 SCSS Overview

The SCSS files are modular and follow a structured approach:  

### 📌 _globales.scss  
- Base font size set to 62.5% for easier rem calculations  
- Layout class `.contenedor` for consistent width  
- Basic styling for elements like body, p, a, img, h1, h2, h3, ul  
- `.seccion` class with responsive padding via mixin  

### 📌 _variables.scss  
- `$fuente_principal`: primary font for the app  
- `$negro`: main text color  

### 📌 _mixins.scss  
- Reusable mixins for media queries (e.g., `tablet`)


## 👩‍💻 Author

**Juliana García Corredor**  
[@JuliGeralDev](https://github.com/JuliGeralDev)
