# 📊 SQL Learning Journey
---

## 📅 Day 1: Basics & Sorting
**Key Concepts:**
* **Basic Retrieval:** Using `SELECT` and `FROM`.
* **Filtering:** Using `WHERE` with operators like `=` and `!=`.
* **Sorting:** Using `ORDER BY` with `ASC` (default) and `DESC` (highest first).
* **Multi-Sorting:** Prioritizing sorts by listing multiple columns (e.g., Country then Score).

---

## 📅 Day 2: Aggregations, Logic & Execution
**Key Concepts:**
* **Static Values:** Selecting strings and numbers directly (e.g., `SELECT 'hello'`).
* **Aggregate Functions:** `SUM()`, `AVG()`, and `COUNT()`.
* **Grouping:** Using `GROUP BY` to summarize data per category.
* **Having vs. Where:** `WHERE` filters rows; `HAVING` filters aggregated groups.
* **Refining:** `DISTINCT` for unique lists and `TOP` for limiting results.

### ⚙️ SQL Execution Order
Understanding the difference between **Coding Order** and **Execution Order** is crucial for debugging complex queries:



1. `FROM` (Source data)
2. `WHERE` (Filter rows)
3. `GROUP BY` (Group rows)
4. `HAVING` (Filter groups)
5. `SELECT` (Choose columns)
6. `DISTINCT` (Remove duplicates)
7. `ORDER BY` (Sort results)
8. `TOP` (Limit final rows)
