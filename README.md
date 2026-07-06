# 🎭 Playwright TodoMVC Automation Framework

A modern End-to-End (E2E) Test Automation Framework built using **Playwright** and **JavaScript** to automate the TodoMVC React application. This project demonstrates industry-standard automation practices, clean test design, and reliable web element interaction.

---

## 🚀 Project Overview

This framework automates the core functionalities of the TodoMVC application while following QA best practices.

### ✨ Key Features

- ✅ End-to-End UI Automation
- ✅ Page Object Model (POM)
- ✅ Robust Locator Strategy
- ✅ Atomic Test Design
- ✅ Dynamic Test Data
- ✅ Assertions for UI Validation
- ✅ HTML Test Reports
- ✅ Cross-Browser Testing
- ✅ Headless & Headed Execution

---

## 🛠 Tech Stack

| Technology | Usage |
|------------|-------|
| Playwright | UI Automation |
| JavaScript | Programming Language |
| Node.js | Runtime Environment |
| Playwright Test | Test Runner |
| HTML Reporter | Test Reporting |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```
PLAYWRIGHT_TODO
│
├── tests/
│   └── todo.spec.js
│
├── playwright.config.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

# ✅ Test Scenarios Covered

### 📝 Todo Creation
- Add a new Todo item
- Add multiple Todo items
- Verify Todo is successfully created

### ✔️ Todo Completion
- Mark Todo as completed
- Verify completed state

### 🔍 Todo Filtering
- Verify Active Todos
- Verify Completed Todos
- Verify All Todos

### 🧪 Validation & Assertions
- Verify element visibility
- Verify Todo count
- Verify completed status
- Validate application behavior

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Amritthukral/playwright-todomvc-automation.git
```

Navigate into the project

```bash
cd playwright-todomvc-automation
```

Install dependencies

```bash
npm install
```

Install Playwright browsers

```bash
npx playwright install
```

---

# ▶️ Run Tests

### Run all tests

```bash
npx playwright test
```

### Run tests in headed mode

```bash
npx playwright test --headed
```

### Run a specific test file

```bash
npx playwright test tests/todo.spec.js
```

### Run tests in Chrome

```bash
npx playwright test --project=chromium
```

---

# 📊 Generate HTML Report

After execution

```bash
npx playwright show-report
```

The report contains:

- Test Summary
- Passed & Failed Tests
- Execution Time
- Error Logs
- Screenshots (if configured)

---

# 💡 Skills Demonstrated

- Playwright Automation
- JavaScript
- UI Automation Testing
- End-to-End Testing
- Test Assertions
- Locator Strategies
- Page Object Model (POM)
- HTML Reporting
- Git & GitHub
- QA Best Practices

---

# 📸 Application Under Test

**TodoMVC React Application**

Features automated:

- Create Todo
- Complete Todo
- Filter Todos
- Verify UI Behavior

---

# 📈 Future Improvements

- Integrate Page Object Model for scalability
- CI/CD with GitHub Actions
- Parallel Test Execution
- Data-Driven Testing
- API Testing Integration
- Screenshot on Failure
- Trace Viewer Integration

---

# 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork this repository and submit a Pull Request.

---

# 👨‍💻 Author

**Amrit Pal Singh**

Computer Science Engineering Student

Aspiring QA Automation Engineer

Skilled in:
- Playwright
- JavaScript
- Manual Testing
- API Testing
- SQL
- Git & GitHub

---

## ⭐ If you found this project helpful, don't forget to Star the repository!
