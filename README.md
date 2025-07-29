# Playwright Object Model Example

This repository showcases a simple implementation of the **Page Object Model (POM)** design pattern using [Playwright](https://playwright.dev/) and TypeScript. It demonstrates how to organize UI tests for better readability, maintainability, and scalability.

## 🧩 What’s Inside

- 🎯 Sample tests using Playwright Test
- 📄 Clear folder structure separating test logic from page definitions
- 🧼 Use of `beforeEach`, `expect` assertions, and locators
- 🔄 Test flows based on real-world UI interactions (e.g. login)
- 📸 Playwright’s screenshot and report generation

## 🛠 Tech Stack

- [Playwright](https://playwright.dev/)
- TypeScript
- Node.js

## 📁 Folder Structure

```
playwright-object-model/
├── pages/             # Page object classes
│   └── login.page.ts  # Example: LoginPage class
├── tests/             # Test files using POM
│   └── login.test.ts
├── utils/             # Optional: utilities or helpers
├── playwright.config.ts
└── README.md
```

## 🚀 Getting Started

### 1. Prerequisites

- Node.js v18+
- npm or yarn

### 2. Installation

```bash
npm install
```

### 3. Run tests

```bash
npx playwright test
```

### 4. View HTML report

```bash
npx playwright show-report
```

## 🔍 Key Concepts Demonstrated

- Page Object Model (POM) design
- Test separation and modular structure
- Reusable selectors and page methods
- Test assertions using `expect`
- Playwright configuration setup

## 🤝 Contributing

This repo is mainly for learning purposes, but feedback and suggestions are welcome!
