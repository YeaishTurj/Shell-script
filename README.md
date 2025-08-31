# Bash Expense Tracker

A simple **Expense Tracker** built with Bash shell scripting.  
Track your daily expenses, update records, filter by tag or date, and view summaries—all in your terminal.

---

## Demo

### GIF Demo

![Expense Tracker Demo](demo/expense_tracker_demo.gif)

### Video Demo

[Watch the demo video](demo/expense_tracker_demo.mp4)

---

## Features

- Add, update, and delete expenses
- View all expenses with neat formatting
- Show top N highest expenses
- Filter expenses by tag
- View expenses within a date range
- Overview of total spending and spending by tag

---

## Setup

1. **Clone the repository**

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2. **Make the script executable**

```bash
chmod +x ExpenseTracker.sh
```

3. **Run the script**

```bash
./ExpenseTracker.sh
```

---

## Usage

Once running, you'll see a menu:

1. Add Expense
2. Show All Expense
3. Update Expense
4. Delete Expense
5. Show Top N Expenses
6. Show Expense of Tag
7. Show Expense of a Date Range
8. Show Expense Overview
9. Exit

Just enter the corresponding number to perform an action.

---

## File Format

All expenses are saved in `Expense.csv` with columns:

- `ID` – auto-incremented unique identifier
- `DATE` – in `YYYY-MM-DD` format
- `AMOUNT` – numeric value of the expense
- `TAG` – category or label for the expense

---

## Notes

- Dates must follow the `YYYY-MM-DD` format.
- Amounts should be numeric.
- The script automatically creates `Expense.csv` if it doesn’t exist.

---
