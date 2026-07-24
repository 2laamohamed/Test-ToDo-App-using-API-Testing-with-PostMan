# 🧪 ToDo App API Testing Project
API Testing for **ToDo App** using **Postman**.

---

## 📌 Project Overview
This repository contains a comprehensive Postman Collection and Environment setup for testing the ToDo Application APIs. It includes functional test cases, assertions, negative testing, and security authorization checks.

---

## 🛠️ Test Coverage Included
* **Authentication:** User Sign-up & Login token extraction.
* **Task Management (CRUD):** 
  * `POST` Add new tasks.
  * `GET` Retrieve tasks by dynamic ID.
  * `PUT` Update / Mark tasks as completed.
  * `DELETE` Delete completed tasks.
* **Negative & Boundary Testing:** 
  * Validation for missing/empty fields (`400 Bad Request`).
  * Non-existing endpoint handling (`404 Not Found`).

---

## 🚀 How to Run the Tests

1. Download or clone this repository.
2. Open **Postman**.
3. Import both files into Postman:
   - `ToDo App Api's.postman_collection.json`
   - `ToDo App Api's Environment.postman_environment.json`
4. Select the **ToDo App Api's Environment** from the top right environment selector.
5. Run the full collection using the **Postman Collection Runner**.

