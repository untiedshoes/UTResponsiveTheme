# UTResponsiveTheme

![GitHub repo size](https://img.shields.io/github/repo-size/untiedshoes/UTResponsiveTheme)
![GitHub last commit](https://img.shields.io/github/last-commit/untiedshoes/UTResponsiveTheme)
![GitHub license](https://img.shields.io/github/license/untiedshoes/UTResponsiveTheme)

A custom responsive SCSS-based theme developed for my website:  
👉 https://untiedshoes.co.uk/

Built as part of a bespoke frontend implementation for an Umbraco-powered site, this project focuses on maintainable, modular styling using modern SCSS practices.

---

## Overview

This repository contains the SCSS source for a fully responsive theme used in a custom Umbraco build. The structure is designed to support scalability, reusability, and clean separation of concerns.

**Key goals:**
- Maintainable and modular SCSS architecture  
- Responsive design across devices  
- Easy integration with Umbraco templates  
- Clear structure for ongoing development and extension  

---

## Features

- Modular SCSS structure (partials, variables, mixins)  
- Responsive layout design  
- Reusable components and utility styles  
- Designed to support a custom Umbraco frontend  

---

## Project Structure

```text
scss/
  ├── base/        # Base styles, resets, typography
  ├── components/  # Reusable UI components
  ├── layout/      # Layout and grid styles
  ├── utils/       # Variables, mixins, helpers
  └── main.scss    # Entry point
```
---

## Getting Started
```bash
npm install sass
```

---

## Compile SCSS
One-off build:
```bash
npx sass scss/main.scss css/main.css
```
**Watch mode (recommended during development):**
```bash
npx sass scss:css --watch
```

---

## Optional: npm Scripts
You can simplify the workflow by adding scripts to a package.json:
```json
{
  "scripts": {
    "build": "sass scss/main.scss css/main.css",
    "watch": "sass scss:css --watch"
  }
}
```
Then run:
```bash
npm run watch
```

---

## Legacy (Compass Support)
This project was originally built using Compass. While it can still be used if required, it is no longer actively maintained.

Migrating to **Dart Sass** is recommended as it is the current standard and does not require Ruby.

---

## Usage

The compiled CSS is used within a custom Umbraco theme powering:

👉 https://untiedshoes.co.uk/

---

## Author

Developed and maintained by:
👉 https://github.com/untiedshoes

---

## Notes

This repository represents part of a broader production system and demonstrates:

- Real-world SCSS architecture  
- Maintainable frontend design  
- Practical integration with a CMS (Umbraco)  

---

👉 **“This developer builds real, production-quality frontends”**