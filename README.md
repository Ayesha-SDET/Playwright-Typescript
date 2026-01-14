## Overview

This repository showcases a **Playwright automation framework** built with **TypeScript** — designed to demonstrate real-world automation engineering skills.  
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
│
├── pages/                         # Page Object Model classes
│   └── LoginPage.ts
│   └── HomePage.ts
│   └── LogoutPage.ts
│
├── reports/                       # HTML / screenshots
│
├── testdata/                       # test data
│    └── loginData.js
│
├── tests/                         # Test specifications
│   └── Login.spec.ts
│   └── LoginDataDriven.spec.ts
│
├── utils/                         # Reusable utilities 
│   └── randomDataGenerator.js
│   └── dataProvider.ts
│
├── playwright.config.ts           # Playwright configuration
├── package.json                   # Project dependencies 
├── test.config.ts                  # TypeScript configuration

```

##  Running the Tests

### Run Locally

```bash
npm install
npx playwright install
npx playwright test
```

### View HTML Report

```bash
npx playwright show-report
```

### CI Execution

* Tests run automatically via **GitHub Actions**
* Triggered on push / pull requests
* Results available in the **Actions** tab

---


