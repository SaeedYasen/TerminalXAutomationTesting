# 🛒 Terminal X - End-to-End Automation Framework

This repository contains a comprehensive **E2E Automation Testing Suite** for the [Terminal X](https://www.terminalx.com/) e-commerce platform. The project demonstrates a full testing lifecycle, from structured **QA Planning (STP/STD)** to a scalable **Automation Infrastructure** built from scratch.

---

## 🎯 Project Overview
The goal of this project was to validate critical business flows of the Terminal X website, focusing on the sales funnel, search filters, and user experience stability. 

### Key Highlights:
* **Infrastructure from Scratch:** Built a modular and reusable testing architecture (Page Object Model).
* **Multi-Layer Testing:** Combined UI-based testing with API validation.
* **Professional Documentation:** Includes a full Test Plan (Word) and detailed Test Cases (Excel).
* **Advanced Automation:** Implementation of Parameterized tests and custom annotations (e.g., *slow* tests handling).

---

## 🛠 Tech Stack
* **Framework:** Playwright
* **Language:** TypeScript / JavaScript
* **Pattern:** Page Object Model (POM)
* **Tools:** Postman (API Testing), Git, Excel (Test Cases), MS Word (Test Plan)

---

## 📂 Project Structure

- **`infra/`** | Core infrastructure and environment configuration.
- **`logic/`** | Page Objects and core business logic for test scenarios.
- **`tests/`** | Automated test suites with full coverage for sales filters and E2E flows.
- **`utils/`** | Reusable helper functions and consolidated utilities.
- **`Terminal X Test cases.xlsx`** | Comprehensive Excel file with manual test cases (STD).
- **`Test Plan - Terminal X.docx`** | Detailed Software Test Plan (STP) document.

---

## ⚙️ Key Automation Features
* **Parameterized Testing:** Highly flexible tests running against multiple datasets to maximize coverage.
* **Smart Wait Mechanisms:** Global configurations and specific handling for "Slow" annotated tests to ensure stability.
* **Filter Logic Coverage:** Full automated coverage for complex sales filter scenarios.
* **Logging & Reporting:** Integrated tracing for efficient debugging and investigation of test results.

---

## 🚀 Getting Started

### Prerequisites
* Node.js (v16 or higher)
* Playwright

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/SaeedYasen/TerminalXAutomationTesting.git](https://github.com/SaeedYasen/TerminalXAutomationTesting.git)
