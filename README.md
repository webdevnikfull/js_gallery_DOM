# 🖼️ JS Gallery DOM

> Interaktywna galeria zdjęć zaimplementowana przy użyciu czystego JavaScriptu, manipulacji drzewem DOM oraz stylów SCSS. Projekt posiada pełną konfigurację narzędzi do kontroli jakości kodu oraz automatycznych testów End-to-End (E2E).

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Cypress](https://img.shields.io/badge/-Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![ESLint](https://img.shields.io/badge/-ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-CI/CD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

## 🎯 Opis Projektu

Głównym celem projektu jest stworzenie płynnie działającej galerii z miniaturkami i widokiem głównym, obsługującej dynamiczne zmiany stanu interfejsu. Jako projekt o wysokich standardach inżynieryjnych, zawiera rygorystyczną konfigurację statycznej analizy kodu oraz automatyzację testów UI.

## 🛠️ Tech Stack i Narzędzia

* **Frontend:** JavaScript (ES6+), HTML5, SCSS / Sass
* **Testowanie E2E:** Cypress (`cypress/integration/galleryDom.spec.js`)
* **Kontrola jakości kodu (Linters):** ESLint, Stylelint, Prettier, LintHTML
* **CI/CD:** GitHub Actions (`.github/workflows/test.yml`)

## 📂 Struktura Katalogów

```text
js_gallery_DOM-master/
├── .github/workflows/     # Konfiguracja CI/CD (GitHub Actions)
├── cypress/               # Automatyczne testy E2E (Cypress)
├── src/
│   ├── images/            # Zasoby graficzne i miniatury
│   ├── scripts/           # Logika aplikacji (główny plik main.js)
│   ├── styles/            # Arkusze stylów SCSS (main.scss)
│   └── index.html         # Główny szablon DOM
├── package.json           # Zależności i skrypty npm
└── ...
