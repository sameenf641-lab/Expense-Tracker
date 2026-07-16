# 💰 Expense Tracker

A simple command-line Python script that lets you enter multiple expenses, then calculates the **total**, **average**, **maximum**, and **minimum** expense using the accumulator pattern.

## 📌 Features

- Add as many expenses as you want in a single session
- Input validation — rejects non-numeric entries and invalid y/n responses
- Displays a numbered list of all entered expenses
- Calculates:
  - **Total** expense
  - **Average** expense
  - **Maximum** expense
  - **Minimum** expense

## 🧠 Concept Practiced

This project is built around the **accumulator pattern**:

```python
total = total + new_expense
```

Along with:
- Variables
- User input (`input()`)
- Type conversion (`int()`)
- Loops (`while`)
- Lists (`append()`)
- Built-in aggregation functions (`sum()`, `len()`, `max()`, `min()`)

## 🚀 How to Run

1. Make sure you have Python 3 installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   cd expense-tracker
   ```
3. Run the script:
   ```bash
   python expense_tracker.py
   ```

## 🖥️ Example Run

```
enter expense: 200
Do you want to add another expense?, Enter y else enter n
y
enter expense: 150
Do you want to add another expense?, Enter y else enter n
n
1 .  200
2 .  150
TOTAL EXPENSE : 350
AVERAGE EXPENSE : 175.0
MAXIMUM EXPENSE AMOUNT : 200
MINIMUM EXPENSE AMOUNT : 150
```

## 📂 Project Structure

```
expense-tracker/
├── expense_tracker.py    # main script (run this)
├── expense_tracker.ipynb # step-by-step walkthrough notebook
└── README.md             # project documentation
```

## 🔧 Possible Improvements

- Accept decimal expenses using `float()` instead of `int()`
- Add expense categories (e.g., food, travel, bills)
- Save expenses to a file (CSV/JSON) for persistence
- Add a menu-driven interface (add / view / delete / exit)

## 📜 License

This project is open-source and free to use for learning purposes.
