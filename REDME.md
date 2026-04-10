# 🧪 Automation Exercise Testing Project

## 📌 Project Overview

This project focuses on **Manual Testing and API Automation Testing** of the [Automation Exercise](https://automationexercise.com/) e-commerce platform.
It demonstrates end-to-end testing skills including **test case design, API validation, and automation using Postman & Newman**.

---

## 🎯 Objectives

* Validate core functionalities of an e-commerce website
* Perform **manual testing** on UI workflows
* Automate **API testing using Postman**
* Execute automated tests using **Newman CLI**
* Generate and analyze **test reports**

---

## 🔧 Tools & Technologies

* Postman (API Testing)
* Newman (CLI Automation Tool)
* JavaScript (Postman Test Scripts)
* Git & GitHub (Version Control)

---

## 🧩 Test Coverage

### ✅ Manual Testing

* User Registration
* Login & Logout
* Product Search
* Add to Cart
* UI Validation

### ✅ API Testing

Tested multiple API endpoints including:

* GET All Products List
* POST Search Product
* GET Brands List
* POST Verify Login
* POST Create User Account
* PUT Update User Account
* DELETE User Account

---

## ⚙️ Test Execution

### ▶️ Run using Postman

1. Import the Postman collection
2. Set environment variables (if needed)
3. Click **Run Collection**

---

### ▶️ Run using Newman (CLI)

```bash
newman run automation-exercise.postman_collection.json -r html
```

---

## 📊 Test Results

* Total Requests: 14
* Total Assertions: 14
* ✅ Passed: 100%
* ❌ Failed: 0
* ⏱️ Average Response Time: ~357ms

---

## 🔍 Key Validations

* Status Code Verification (200 OK)
* Response Body Validation
* Error Handling (Invalid Inputs, Missing Parameters)
* CRUD Operations Testing

---

## 🚀 Features

* Covers both **positive and negative test scenarios**
* Automated API validation using **Postman scripts**
* CLI-based execution with **Newman reporting**
* Clean and structured test collection

---

## 📁 Project Structure

```
├── automation-exercise.postman_collection.json
├── newman-report.html
└── README.md
```

---

## 📌 Future Improvements

* Add **UI Automation using Selenium / Playwright**
* Integrate with **CI/CD (GitHub Actions)**
* Add **Performance Testing using JMeter**
* Increase test coverage with more edge cases

---

## 👨‍💻 Author

**Bipro Saha**

* GitHub: https://github.com/yourusername
* LinkedIn: https://linkedin.com/in/yourprofile

---

## ⭐ Acknowledgment

This project is based on the practice platform:
👉 https://automationexercise.com/
