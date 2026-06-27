# 🧪 QA Intern Technical Assignment – Tichi Web Application

## 📖 Overview

This repository contains my submission for the **QA Intern Technical Assignment**. The project focuses on validating the core functionality of the Tichi web application through manual testing, defect reporting, and automated regression testing using Playwright.

---

# 📁 Repository Contents

### ✅ Task 1 – Test Case Design

Prepared a detailed test case document covering the **Signup** and **Login** modules. The document includes:

- Positive test scenarios
- Negative test scenarios
- Boundary value test cases
- Expected and actual results

---

### 🐞 Task 2 – Bug Report

Documented the identified issues in a structured defect report with supporting evidence, including:

- Bug description
- Steps to reproduce
- Expected vs Actual behavior
- Network observations
- Frontend analysis
- Investigation of the **Invalid Email Validation** issue and associated **404 Not Found** responses

---

### 🤖 Task 3 – Test Automation

Developed an automated regression suite using **Playwright (JavaScript)** to validate the login functionality across supported browsers.

---

# ⚙️ Tools & Technologies

| Category | Technology |
|----------|------------|
| Automation Framework | Playwright |
| Programming Language | JavaScript |
| Runtime | Node.js |
| Browser Support | Chromium, WebKit |
| Execution Environment | Headless Linux / Google Colab |

---

# 🚀 Getting Started

## Step 1 – Verify Installation

Make sure Node.js (v18 or above) is installed.

```bash
node -v
npm -v
```

---

## Step 2 – Install Dependencies

Install all required packages and Playwright browser binaries.

```bash
npm install

npx playwright install --with-deps
```

---

## Step 3 – Run the Automation Suite

Execute all Playwright test cases.

```bash
npx playwright test
```

---

## Step 4 – Open Test Report

View the generated HTML report after execution.

```bash
npx playwright show-report
```

---

# 🔍 Automation Approach

The automation suite is designed to handle dynamic web elements commonly encountered in cloud-based execution environments.

### Reliability Techniques

- Utilized stable locator strategies for consistent element identification.
- Implemented fallback mechanisms where dynamic rendering could affect element availability.
- Wrapped critical actions inside `try...catch` blocks to improve execution resilience.
- Minimized flaky test failures caused by asynchronous page loading.
- Designed the suite to support continuous regression execution in CI/CD pipelines.

---

# 📌 Key Highlights

- ✔️ Comprehensive manual testing
- ✔️ Well-structured defect documentation
- ✔️ Playwright automation framework
- ✔️ Robust locator implementation
- ✔️ Headless execution support
- ✔️ CI/CD compatible automation
- ✔️ Clean and maintainable test scripts

---

## 📄 Summary

This assignment demonstrates practical QA engineering skills across manual testing, defect analysis, and automation testing. The automation framework is built with a focus on maintainability, execution stability, and scalability for future test enhancements.
