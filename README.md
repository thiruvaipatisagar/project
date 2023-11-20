# Expense Tracker

This is a basic expense tracker script written in Python. It allows users to add and remove expenses, as well as list all recorded expenses.

## How to Use

1. Run the script using a Python interpreter.
2. Follow the on-screen menu to add, remove, or list expenses.

## Code Structure

- `expenses`: A list to store expense records.
- `addExpense(amount, category)`: Function to add a new expense to the list.
- `removeExpense()`: Function to remove an expense from the list.
- `printMenu()`: Function to print the menu options.
- `listExpenses()`: Function to display a list of all recorded expenses.

## Usage Instructions

1. **Adding an Expense (Option 1):**
   - Enter the amount for the expense.
   - Enter the category for the expense.

2. **Removing an Expense (Option 2):**
   - Choose the expense number to remove.

3. **Listing All Expenses (Option 3):**
   - View a list of all recorded expenses.

## Important Note

- Expenses are stored in the `expenses` list as dictionaries with 'amount' and 'category' keys.

## Example

```bash
Please choose from one of the following options...
1. Add A New Expense
2. Remove An Expense
3. List All Expenses
> 1
How much was this expense?
> 25.50
What category was this expense?
> Food
