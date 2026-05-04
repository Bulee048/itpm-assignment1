# ITPM Assignment 1 – Transliteration Accuracy Testing

## 📌 Overview

This project tests the accuracy of a web-based Singlish to Sinhala transliteration system.

The system under test:
https://www.pixelssuite.com/chat-translator

The goal is to identify incorrect conversions (failures) and automate testing using Playwright.

---

## 🎯 Objectives

* Identify 50 negative test cases where the system fails
* Cover all 24 Singlish input types
* Automate testing using Playwright
* Record results in an Excel file

---

## 🛠 Technologies Used

* Python
* Playwright
* OpenPyXL
* Microsoft Excel

---

## 📂 Project Structure

* `test_automation.py` – main automation script
* `Assignment 1 - Test cases.xlsx` – test cases and results
* Other supporting files for automation

---

## ⚙️ Setup Instructions

### 1. Install Python

Install Python 3.11 or above

### 2. Install dependencies

Run:

```
pip install -U pip
pip install playwright openpyxl
playwright install
```

---

## ▶️ Run the Automation

Run the following command:

```
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## 📊 Test Case Details

* 50 negative test cases (Neg_0001 – Neg_0050)
* Covers all 24 Singlish input types
* Includes:

  * Input
  * Expected Output
  * Actual Output
  * Status
  * Type classification
  * Evidence

---

## ⚠️ Notes

* Do not manually fill "Actual Output" and "Status"
* Ensure Excel file is closed before running script
* Repository is public for evaluation

---

## 👨‍💻 Author

Student ID: ITXXXXXXXX
