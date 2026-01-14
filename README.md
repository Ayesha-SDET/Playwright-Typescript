## Overview

This repository showcases a **professional Playwright automation framework** built with **TypeScript** — designed to demonstrate real-world automation engineering skills.  
It highlights key automation concepts such as Page Object Model, CI integration with GitHub Actions, and ** HTML test reporting** 

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| 🧪 Playwright + TypeScript | Automated web UI testing |
| 📐 Page Object Model (POM) | Framework design for maintainability |
| ⚙️ GitHub Actions | CI/CD test automation |
| 📊 HTML Reporter | Detailed execution reports |
| 🎯 npm | Dependency management |

---

## 📁 Project Structure


```

├── .github/
│   └── workflows/
│       └── playwright.yml        # GitHub Actions CI pipeline
│

├── reports/                       # HTML / screenshots
├── testdata/                       # HTML / screenshots
    └── loginData.js

├── pages/                         # Page Object Model classes
│   ├── LoginPage.ts
│   └── HomePage.ts
    └── LogoutPage.ts
│
├── tests/                         # Test specifications
│   ├── Login.spec.ts
│   └── LoginDataDriven.spec.ts
│
├── utils/                         # Reusable utilities & test data
│   └── randomDataGenerator.js
    └── dataProvider.ts
│
├── playwright.config.ts           # Playwright configuration
├── package.json                   # Project dependencies & scripts
├── test.config.ts                  # TypeScript configuration


```



