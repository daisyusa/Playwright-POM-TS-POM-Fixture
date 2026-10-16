# Playwright + TypeScript + Page Object Model + Fixture Example

> A minimal, beginner-friendly POM + Fixture starter

---

## 🚀 Quick start

```bash
# 1 Clone
git clone {find the URL on the github}

# 2 Run the tests by default
npx playwright test

# 3 Run the tests with UI
npx playwright test --ui

```

---

## 🗂️ Project main structure

```
.
├─ pages/
│  ├─ BasePage.ts          # shared helper methods
│  ├─ CheckboxesPage.ts    # reusable-locator example
│  ├─ LoginPage.ts         # inline-locator example
│  ├─ ManagePage.ts        # lazy POM factory
│  └─ SecurePage.ts
├─ tests/
│  ├─ checkboxes.spec.ts
│  └─ login.spec.ts
├─ playwright.config.ts
├─ package.json
└─ README.md
```

---

### Prerequisites

- **Node.js ≥ 18**
- **Playwright** Install by "npm init playwright@latest"

---
