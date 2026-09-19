# 🧪 QA Automation Portfolio: Interactive Gallery DOM Validation

> About this repository: This project demonstrates automated UI testing of dynamic DOM manipulation (an interactive photo gallery with thumbnail switching and main view state changes) using Cypress. It also highlights a modern "Shift-Left" QA approach through extensive static code analysis and Continuous Integration (CI/CD).

![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Static Analysis](https://img.shields.io/badge/Static_Analysis-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

## 🎯 Project Overview

This application is a Vanilla JavaScript implementation of an interactive photo gallery supporting dynamic interface state changes, thumbnails, and a main image view.

As a QA Automation Engineer, my focus in this repository is to validate UI interactions, dynamic DOM updates, and state transitions to ensure a smooth and reliable user experience.

## 🛠️ QA Tech Stack & Tools

* **E2E / UI Automation:** Cypress
* **CI/CD Pipeline:** GitHub Actions (Automated test execution on push/PR)
* **Static Code Analysis (Shift-Left QA):** ESLint, Stylelint, LintHTML, Prettier
* **Core Technologies:** HTML5, SCSS, Vanilla JS (ES6+)

## 📊 Test Strategy & Coverage

### 1. Automated UI Testing (Cypress)
Located in `cypress/integration/galleryDom.spec.js`, the test suite simulates real user interactions to verify:
* Proper rendering of thumbnails and the main view container.
* Smooth switching of the active image upon clicking thumbnails.
* Stability and integrity of the DOM structure post-interaction.

### 2. Continuous Integration (CI/CD)
The project utilizes GitHub Actions (`.github/workflows/test.yml`) to enforce quality gates. Every commit automatically triggers a pipeline that:
* Lints the HTML, CSS, and JS files to catch syntax and formatting issues early.
* Runs the Cypress E2E test suite in a headless environment.

## 🚀 How to Run the Tests Locally

To evaluate the test scripts and static analysis tools on your local machine, follow these steps:

### 1. Environment Setup
Clone the repository and install the Node.js dependencies:
```bash
npm install
