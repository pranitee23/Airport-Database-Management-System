# ✈️ Airport Database Management System

> Managing airports is no small feat — thousands of flights, passengers, crew members, and gates all operating in perfect sync. This project brings that complexity into a well-structured, secure, and queryable relational database.

---

## 🧭 What Is This Project?

This is a **full-scale Airport Database Management System** built entirely in **T-SQL (Transact-SQL)**. It was designed to simulate the real-world data operations of an airport — from tracking flights and passengers to managing gates, crew, and baggage — all while keeping performance and data security at the forefront.

What makes this more than just a schema dump? It's packed with **stored procedures, triggers, views, CTEs, UDFs, and column-level encryption** — the kind of engineering that makes a database actually production-worthy. On top of that, the data is brought to life through **Power BI dashboards** that visualize large-scale flight data in an intuitive, interactive way.

---

## 📁 Project Structure

```
Airport-Database-Management-System/
│
├── Create.sql                        # DDL — All table definitions & schema creation
├── Insert.sql                        # DML — Sample data population
├── Project_Operation_Queries.sql     # Core queries, procedures, triggers, views & more
├── PowerBI_Data_Visualization/       # Power BI reports & dashboards
├── AIRPORT MANAGEMENT SYSTEM.pptx   # Project presentation
└── LICENSE                           # MIT License
```

---

## 🛠️ Tech Stack & Features

This project isn't just about writing tables — it's about writing them *right*. Here's what's packed inside:

- 🗃️ **DDL & DML** — Clean, normalized schema design with well-defined relationships across all airport entities
- ⚙️ **Stored Procedures** — Reusable, parameterized logic for operations like booking, scheduling, and lookups
- 🔔 **Triggers** — Automated responses to data changes, ensuring business rules are always enforced
- 👁️ **Views** — Simplified, role-friendly interfaces to complex joins and aggregated data
- 🔁 **CTEs (Common Table Expressions)** — Readable, hierarchical query logic that keeps things clean
- 🧩 **UDFs (User-Defined Functions)** — Custom functions for reusable calculations and data transformations
- 🔐 **Encryption** — Column-level encryption to protect sensitive passenger and staff information
- 📊 **Power BI Visualizations** — Interactive dashboards built on large-scale flight data

---

## 🚀 Getting Started

Want to run this locally? Here's how:

**Prerequisites:**
- Microsoft SQL Server (2016 or later)
- SQL Server Management Studio (SSMS)
- Power BI Desktop *(for dashboards)*

**Steps:**

1. **Clone the repository**
   ```
   git clone https://github.com/pranitee23/Airport-Database-Management-System.git
   ```
2. **Set up the database** — Open `Create.sql` in SSMS and execute it to build the full schema.
3. **Populate sample data** — Run `Insert.sql` to load the database with realistic test data.
4. **Explore the operations** — Open `Project_Operation_Queries.sql` to run stored procedures, triggers, views, and more.
5. **View dashboards** — Open the files inside `PowerBI_Data_Visualization/` using Power BI Desktop.

---

## 💡 Key Highlights

A few things that make this project stand out:

- **Security-first mindset** — sensitive fields are encrypted at the column level, not just the application layer
- **Trigger-driven integrity** — business logic lives inside the database so rules are always enforced
- **Scalable design** — built and tested on large-scale flight data, not just toy examples
- **End-to-end coverage** — from schema creation all the way to visual reporting, nothing left halfway

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, fork, and build on it.
See the [LICENSE](LICENSE) file for full details.

---

## 🙋‍♀️ About the Author

Built with 💙 by **[Pranitee Majukar](https://github.com/pranitee23)**

*If you found this project useful or interesting, drop a ⭐ — it genuinely means a lot!*
