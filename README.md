# 📱 **MobileTestPro – Appium Mobile Automation Framework**

> A modular, scalable Appium automation framework for Android mobile applications built with Java, TestNG, and Maven — designed for real project usage and interview showcase.

---

## 🧠 Project Overview

**MobileTestPro** is an automation framework focused on end-to-end mobile test automation for Android applications using **Appium** and **Java**. This framework showcases:

* Robust mobile automation using Appium
* TestNG for flexible test execution
* Maven for dependency and build management
* Modular structure for maintainability
* Capability to integrate with CI/CD pipelines
* Screenshots on failure
* Realistic test scenarios for Android apps

It is *portfolio-ready* and demonstrates practical mobile automation skills that matter in interviews.

---

## 🚀 Tech Stack

| Category          | Technology                                     |
| ----------------- | ---------------------------------------------- |
| Language          | Java                                           |
| Mobile Automation | Appium                                         |
| Test Runner       | TestNG                                         |
| Build Tool        | Maven                                          |
| Reporting         | TestNG Reports / ExtentReports (if configured) |
| Platform          | Android                                        |

---

## 📁 Repository Structure

```
MobileTestPro/
├── src/test/java/                    # Test code and utilities
│   ├── tests/                       # Mobile test classes
│   ├── utils/                       # Utilities (drivers, helpers)
├── src/test/resources/               # Test data / config
├── drivers/                         # Appium drivers (if any)
├── pom.xml                          # Maven configuration
├── testng.xml                       # TestNG suite config
├── logs/                            # Logs during execution
├── screenshots/                     # Screenshots captured on test failure
├── .gitignore                       # Ignored files
└── README.md                        # Project documentation
```

---

## ⚙️ Prerequisites

Before running tests:

1. **Java JDK 11+** installed
2. **Maven** installed and configured (`mvn -v`)
3. **Android SDK** and platform tools installed
4. **Appium server** installed (Appium Desktop or CLI)
5. Physical Android device or emulator configured
6. Set `ANDROID_HOME` and add platform tools to system PATH

---

## 🧪 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/MK-MAN0JKUMAR/Appium-app-automation.git
cd Appium-app-automation
```

Install dependencies and compile:

```bash
mvn clean install
```

---

## 📱 Appium Server Start

Start Appium (CLI):

```bash
appium
```

Or start via Appium Desktop.

---

## 🏃‍♂️ Running Tests

Execute all tests with Maven:

```bash
mvn clean test
```

Or execute with TestNG suite file:

```bash
mvn test -DsuiteXmlFile=testng.xml
```

---

## 📊 Key Features

### 📌 Appium Android Automation

* Automation for Android applications using Appium
* Flexible test scripts driven by TestNG
* Capable of handling real touch actions and gestures

### 🧩 Modular Structure

* Organized test packages
* Utility helpers for driver management

### 📸 Screenshots on Failure

* Captures screenshots on test failures and stores them in `screenshots/`

### 🔄 Integration Potential

* Can be integrated with CI/CD pipelines (GitHub Actions, Jenkins)
* Supports reporting improvements (ExtentReports can be added)

---

## Author
* Manoj Kumar | SDET-I | Automation Engineer | Selenium WebDriver, Java, Playwright, Javascript

