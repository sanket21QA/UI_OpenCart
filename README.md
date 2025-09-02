
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

* **Extent Reports**
  
  <img width="1435" height="386" alt="image" src="https://github.com/user-attachments/assets/b7e6c601-62f6-4fa6-9651-79eaf7dbb686" />

* **Screenshots on Failure**
  
  <img width="1238" height="696" alt="image" src="https://github.com/user-attachments/assets/a3830988-96d7-4e54-9e3d-5783f12dded5" />

* **Log file**
  
<img width="1531" height="589" alt="image" src="https://github.com/user-attachments/assets/db28fb08-8704-4518-a414-b9c01a535c4b" />
 
* **TestNG Reports**
4. View execution & reports in Jenkins

  <img width="1634" height="739" alt="image" src="https://github.com/user-attachments/assets/7e7eb72e-e5a8-4959-89b3-ccd8375c4c18" />
