# Expenses_Tracker
#  Expense Tracker (Java 8 Console App)

A simple command-line **Expense Tracker** written in Java 8 that helps you manage and analyze your daily spending.

---

## Features

-  Add a new expense (amount, category, date, note)
- 📃 View all expenses
- 🔍 Filter expenses by **category** or **date range**
- 📊 Group expenses by category
- 📅 View total and average monthly expenses

---

## Technologies Used

- Java 8
- Stream API
- Lambda Expressions
- Optional
- LocalDate (Java Time API)
- Collectors (grouping, summing, filtering)

---

## Java 8 Concepts Applied

| Feature             | Usage                                       |
|---------------------|---------------------------------------------|
| Stream API          | Filtering, grouping, aggregating expenses   |
| Lambda Expressions  | Functional iteration & behavior logic       |
| Optional            | Safe average calculation                    |
| Collectors API      | `groupingBy`, `summingDouble`, `toList()`   |
| LocalDate API       | Date filtering and formatting               |

---

## Project Structure
expense-tracker/
├── src/
│ ├── model/
│ │ └── Expense.java
│ ├── service/
│ │ └── ExpenseService.java
│ ├── util/
│ │ └── InputUtils.java
│ └── MainApp.java
├── README.md
