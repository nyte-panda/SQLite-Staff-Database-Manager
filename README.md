# 📋 SQLite Staff Database Manager

This project demonstrates how to create, query, and manage a simple SQLite database using Python and Pandas. It reads staff data from a CSV file, inserts it into a database table, performs basic queries, and appends new data dynamically.

---

## 📂 Project Description

The script:
- Connects to a SQLite database (`STAFF.db`).
- Loads data from a CSV file (`INSTRUCTOR.csv`) into a database table called `INSTRUCTOR`.
- Executes multiple SQL queries using Pandas:
  - Display all rows.
  - Display only the first names (FNAME) of instructors.
  - Count the total number of records.
- Appends a new instructor record to the table.
- Verifies the row count after insertion.

---

## 🛠️ Built With

- Python 3
- sqlite3
- pandas

---

## 🚀 How to Run

1. Clone the Repository
   ```bash
   git clone https://github.com/your-username/SQLite-Staff-Database-Manager.git
   cd SQLite-Staff-Database-Manager
