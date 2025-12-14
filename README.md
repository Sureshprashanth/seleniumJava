🚀 Selenium Java Automation Framework

This repository contains a Selenium automation framework built using Java, designed to demonstrate scalable UI test automation, clean architecture, and best practices followed in real-world enterprise projects.

📌 Overview

The framework is built to:

Automate web UI test cases using Selenium WebDriver

Follow Page Object Model (POM) for maintainability

Support data-driven testing

Be easily integrated with CI/CD pipelines

Serve as a learning and reference project for automation engineers

🧪 Tech Stack

Language: Java

Automation Tool: Selenium WebDriver

Test Framework: TestNG

Build Tool: Maven

Design Pattern: Page Object Model (POM)

Reporting: TestNG Reports

Version Control: Git & GitHub

🏗 Framework Architecture
seleniumJava
│
├── src/main/java
│   ├── base        → Driver setup & base classes
│   ├── pages       → Page Object classes
│   └── utilities   → Reusable utilities (config, waits, helpers)
│
├── src/test/java
│   └── tests       → TestNG test cases
│
├── testng.xml      → Test suite configuration
├── pom.xml         → Maven dependencies
└── README.md

✨ Key Features

✅ Page Object Model (POM) implementation

✅ Reusable WebDriver setup

✅ Explicit waits & stable locator strategy

✅ Data-driven test execution

✅ Clean separation of test logic and page actions

✅ Easily extendable for new test scenarios

▶️ How to Run Tests
Prerequisites

Java 8 or above

Maven installed

Chrome browser

Run via Maven
mvn clean test

Run via TestNG

Import project into IntelliJ / Eclipse

Run testng.xml or individual test classes

📈 Learning & Use Case

This project demonstrates:

How to structure a real-world Selenium framework

Best practices for maintainable automation

How automation can reduce manual regression effort

How frameworks are designed in enterprise QA teams

👨‍💻 Author

Suresh Prashanth
SDET Lead | QA Automation Architect | Mentor

🔗 GitHub: https://github.com/Sureshprashanth

🔗 LinkedIn: https://www.linkedin.com/in/suresh-prashanth-11a617168

📧 Email: sureshraviprashanth@gmail.com

⭐ Future Enhancements

Add cross-browser support

Integrate reporting (Extent / Allure)

CI/CD integration (Jenkins / GitHub Actions)

Add API automation examples

Dockerised execution

🙌 If this repository helps you, feel free to ⭐ star it!
