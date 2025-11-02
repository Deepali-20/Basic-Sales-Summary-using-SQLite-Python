# Basic-Sales-Summary-using-SQLite-Python
This project demonstrates how to: - Create and connect to a SQLite database (`sales_data.db`) - Run basic SQL queries inside Python using `sqlite3` - Summarize sales data (total quantity sold and revenue per product) - Display results using Pandas - Visualize revenue using a simple bar chart (Matplotlib)
---

## 📂 Project Files
| File Name | Description |
|-----------|-------------|
| `sales_summary.py` | Main script (connect DB → query → print → plot) |
| `sales_data.db` | SQLite database (auto-created when script runs) |
| `README.md` | Documentation |

---

## 🛠️ Requirements
Python libraries used:

```bash
sqlite3        # built-in, no installation required
pandas
matplotlib
SQL Query Used
SELECT product,
       SUM(quantity) AS total_quantity,
       SUM(quantity * price) AS revenue
FROM sales
GROUP BY product;
🧠 Learning Outcomes

After completing this task, you will know how to:

Use SQLite inside Python

Perform basic SQL operations

Load SQL results into Pandas

Create simple visualizations using Matplotlib
