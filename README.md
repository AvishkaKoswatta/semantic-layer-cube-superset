# Cube Semantic Layer for Banking Data

### What is a Semantic Layer?

A semantic layer is an abstraction on top of database tables that makes it easy for BI tools to query data without writing complex SQL.

- Gold Layer → Semantic Layer → BI Tool.
- For this semantic layer practice project, Cube and Apache Superset is used.
--------------

## Cubes

Cubes are logical representations of datasets in Cube.js. Each cube can be either a **fact table** (events) or a **dimension table** (entities).

**Cubes in this project:**

- `fact_transactions` – Transaction events (Fact Table)  
- `dim_accounts` – Account information (Dimension Table)  
- `dim_customers` – Customer information (Dimension Table)  
- `transactions_view` – Combined business-friendly dataset for dashboards

---

### Key Concepts

- **Dimensions** – attributes for grouping or filtering (e.g., account type, customer name, transaction status)  
- **Measures** – aggregated metrics (e.g., total amount, transaction count, average transaction size)  
- **Joins** – relationships between cubes (e.g., transactions linked to accounts and customers)

--------------
### Dashboard
Answered to following questions:

- Total transaction volume.
- Distribution of transaction types.
- Total deposit amount.
- Transactions over time.
