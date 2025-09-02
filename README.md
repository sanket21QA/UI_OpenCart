
---

# 🚀 OpenCart UI Automation Framework

## About Project
This project is an automation framework built using Java, Selenium, TestNG, and integrated with Jenkins.

<img width="843" height="518" alt="image" src="https://github.com/user-attachments/assets/cb95d52a-a8a7-42bf-93be-9576fbc5f7af" />

[![Java](https://img.shields.io/badge/Java-17-blue?logo=java)](https://www.oracle.com/java/)
[![Selenium](https://img.shields.io/badge/Selenium-4.0-brightgreen?logo=selenium)](https://www.selenium.dev/)
[![Maven](https://img.shields.io/badge/Maven-3.9-orange?logo=apache-maven)](https://maven.apache.org/)
[![TestNG](https://img.shields.io/badge/TestNG-Framework-yellowgreen)](https://testng.org/)
[![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red?logo=jenkins)](https://www.jenkins.io/)
[![GitHub repo](https://img.shields.io/badge/repo-GitHub-blue)](https://github.com/NitinPatil-SDET/OpenCartUIAutomation)
![Git](https://img.shields.io/badge/Version%20Control-Git-orange?logo=git)



---

## 📌 Overview

This project is a **Hybrid Automation Framework** built for automating the **OpenCart** application using **Selenium, TestNG, Maven and Jenkins**.

The framework supports:

* ✅ Page Object Model (POM) design pattern
* ✅ Data-driven testing (Excel-based)
* ✅ Cross-browser execution
* ✅ Jenkins CI/CD integration
* ✅ Extent Reporting & TestNG Listeners

---

## 📂 Project Structure

```


├── src/test/java/                 → Test scripts & page objects
│   ├── pageObjects/               → POM classes
│   ├── testBase/                  → Base setup class
│   ├── testCases/                 → TestNG test cases
│   └── utilities/                 → Helper classes (Excel, Reports)
├── src/test/resources/            → Config & log4j files
│   ├── config.properties/         → URL/PWD/Enviroment
│   └── log4j2.xml/                → Log4j execution logs
├── TestData/                      → Test data files (Excel)
├── reports/                       → HTML Extent Reports
├── screenshots/                   → Captured screenshots on failures
├── logs/                          → Log4j execution logs
├── test-output/                   → TestNG default reports
├── pom.xml                        → Maven dependencies & plugins
├── master.xml                     → Master TestNG suite
└── README.md                      → Project documentation
```

---

## ⚙️ Tech Stack

* **Language**: Java
* **Build Tool**: Maven
* **Test Framework**: Hybrid (POM + DataDriven + KeyWord Driven)
* **Automation Tool**: Selenium WebDriver
* **Logging**: Log4j2
* **Reporting**: Extent Reports + TestNG HTML Reports
* **CI/CD**: Jenkins, Git, GitHub

## 📊 Reports & Logs

* **Extent Reports** → `reports/`
* **Screenshots on Failure** → `screenshots/`
* **Log file** → `logs/automation.log`
* **TestNG Reports** → `test-output/`

4. View execution & reports in Jenkins




---
