# Unleash Creativity

A training project created as part of a front-end course.  
The main goal was to practice adaptive layout, SCSS modular structure, and project bundling with Gulp.

## ✨ Features
- Responsive layout (mobile-first).
- **SCSS** with modular file structure.
- Project build system based on **Gulp**.
- Modern CSS units and techniques (`clamp`, `rem`, `flex`, `grid`).
- Custom header implementation **without JavaScript** (two identical headers used to create a background-change effect on scroll).

## 📂 Project Structure
- `src/` — source files (HTML, SCSS, images).
- `dist/` — compiled project.
- `gulpfile.js` — Gulp configuration.

## 🚀 How to Run
1. Install dependencies:
   ```bash
   npm install



Start development server:
npm run dev 



📝 Notes

This project intentionally uses two identical headers.
The purpose is to demonstrate a custom sticky-header effect where the background changes on scroll.
The implementation had to be CSS-only (no JavaScript) as per the course requirements.
In production, such an effect would usually be implemented differently, but here it serves as an exercise in CSS capabilities.
