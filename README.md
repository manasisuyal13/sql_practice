# SQL Practice Journey 🚀


---

## 📅 Day 1: Basics & Sorting
**Key Learning:** How to retrieve and organize data.

* **Queries:** `SELECT`, `FROM`, `WHERE`.
* **Operators:** Filtering data using `=` and `!=`.
* **Sorting:** Using `ORDER BY` with `ASC` (ascending) and `DESC` (descending).
* **Multi-Level Logic:** Sorting by multiple columns (e.g., Country first, then Score).

---

## 📅 Day 2: Aggregations & Logic
**Key Learning:** Summarizing data and logical execution flow.

* **Aggregates:** `SUM()`, `AVG()`, `COUNT()`.
* **Grouping:** `GROUP BY` to calculate totals per category (e.g., Score by Country).
* **Advanced Filtering:** Using `HAVING` to filter grouped data (since `WHERE` only works on rows).
* **Refining Results:** `DISTINCT` for unique values and `TOP` to limit row counts.
* **Execution Order:** Learning that SQL processes queries in a specific order, not just top-to-bottom.

### 🧠 SQL Execution Order
1. `FROM` 2. `WHERE` 3. `GROUP BY` 4. `HAVING` 5. `SELECT` 6. `DISTINCT` 7. `ORDER BY` 8. `TOP`
