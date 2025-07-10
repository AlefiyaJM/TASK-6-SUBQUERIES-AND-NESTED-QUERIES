# Task 6: Subqueries and Nested Queries


### 📌 Topics Covered:

#### 1. Scalar Subqueries
Scalar subqueries return a single value and are used in SELECT clauses or WHERE conditions. This project includes examples such as:
- Comparing the average and sum of order amounts.
- Fetching category names based on product category ID.

#### 2. Correlated Subqueries
These subqueries reference columns from the outer query and are re-evaluated for each row. Examples include:
- Selecting products that appear in more than two distinct orders.
- Finding users who have placed more than one order.

#### 3. Subqueries with IN, EXISTS, and =
Demonstrates how subqueries can be used to:
- Select users who have placed at least one order (`IN`).
- Check the existence of related data (`EXISTS`).
- Retrieve specific information using `=` for comparison (e.g., user who placed a specific order, lowest priced product).

---

### 📚 Skills Practiced:
- Advanced SQL querying
- Data filtering using subqueries
- Understanding of relational data operations
- Use of aliases, nested SELECTs, and filtering logic

### 🔧 Tools Used:
- MySQL (Command Line Interface)
- Sample relational database with tables such as `User`, `Orders`, `Product`, `Orders_Contains_Product`, and `Product_Category`.

---

