# 🖼️ JS Gallery DOM

> An interactive photo gallery implemented using vanilla JavaScript, DOM manipulation, and SCSS styles. The project features a complete configuration of code quality control tools and automated End-to-End (E2E) tests.

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Cypress](https://img.shields.io/badge/-Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![ESLint](https://img.shields.io/badge/-ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-CI/CD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

## 🎯 Project Overview

The main objective of the project is to create a smooth-running gallery with thumbnails and a main view, supporting dynamic interface state changes. As a project adhering to high engineering standards, it includes a rigorous configuration for static code analysis and UI test automation.

## 🛠️ Tech Stack & Tools

* **Frontend:** JavaScript (ES6+), HTML5, SCSS / Sass
* **E2E Testing:** Cypress (`cypress/integration/galleryDom.spec.js`)
* **Code Quality (Linters):** ESLint, Stylelint, Prettier, LintHTML
* **CI/CD:** GitHub Actions (`.github/workflows/test.yml`)

## 📂 Directory Structure

```text
js_gallery_DOM-master/
├── .github/workflows/     # CI/CD configuration (GitHub Actions)
├── cypress/               # Automated E2E tests (Cypress)
├── src/
│   ├── images/            # Graphic assets and thumbnails
│   ├── scripts/           # Application logic (main.js file)
│   ├── styles/            # SCSS stylesheets (main.scss)
│   └── index.html         # Main DOM template
├── package.json           # npm dependencies and scripts
└── ...
