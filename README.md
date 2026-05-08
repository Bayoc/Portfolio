# Manual Testing, API (Postman) & SQL Portfolio

This repository contains my projects focused on manual testing methodologies, API validation using Postman, and database verification with SQL. 

---

## 🛒 E-commerce Manual Testing Project: Militaria.pl
*Comprehensive functional and usability analysis of a major Polish e-commerce platform.*

* **Scope:** UI/UX analysis, cross-browser testing, mobile responsiveness via Chrome DevTools.
* **Execution:** Designed 5 Test Scenarios and 30+ Test Cases covering happy paths, edge cases, and social logins.
* **Documentation:** Jira bug reporting, Test Plans, and Summary Reports.

#### 📁 Project Documentation
* 📄 **[Live Test Suite (Google Sheets)](https://docs.google.com/spreadsheets/d/1_gszuUNTEtNfG3AQptmJbks0TZzhoaXkgLZSZ03MdS8/edit?gid=0#gid=0)** – Interactive Test Cases and execution status.
* 📋 **[Test Plan](./MILITARIA_PROJECT/TESTS/TEST_PLAN_MILITARIA.md)** – Detailed strategy, scope, and environment details.
* 📊 **[Test Summary Report](./MILITARIA_PROJECT/TESTS/MILITARIA_TESTS_SUMMARY.md)** – High-level execution results and quality assessment.
* 🐞 **[Bug Reports](./MILITARIA_PROJECT/BUGS)** – Jira bug documentation.

---

## 🧪 API Testing Project: Restful-Booker (Postman)
*Automated API testing suite designed to verify CRUD operations within a reservation system.*

* **Environment:** [Restful-Booker API](https://restful-booker.herokuapp.com/)
* **Highlights:** Dynamic request chaining (extracting IDs and passing as variables), automated token generation.
* **Assertions:** JavaScript scripts for verifying response integrity, status codes (200 OK, 401/403), and JSON schema validation.

#### 📁 API Documentation & Resources
* 📁 **[Postman Collection (JSON Export)](https://github.com/Bayoc/Portfolio-ManualTesting-API-SQL/blob/main/API/API_TEST_PLAN.md)** – Import this into Postman to see the full test suite.
* 📋 **[API Test Plan](./API/API_TEST_PLAN.md)** – Documentation of endpoints, test data, and expected status codes.

#### 🛠️ How to run the API tests:
1. **Import:** In Postman, click "Import" and select both `.json` files (Collection and Environment).
2. **Environment:** Select the `Restful-Booker-Env` from the environment dropdown.
3. **Run:** Open the Collection Runner, select the collection, and click "Run Restful-Booker".

---

## 🗄️ Database Testing (SQL)
*Practical application of SQL for data validation and backend testing.*

* 📂 **[Business Scenarios (Militaria.pl simulation)](./SQL/MILITARIA_SQL.md)** – GDPR compliance and data persistence.
* 📂 **[Sakila DB Study](./SQL/SAKILA_STUDY.md)** – Queries ranging from simple data retrieval to complex JOINs and relational logic.
