# Personal Expense Tracker 💰

A simple and user-friendly **Personal Expense Tracker** application written in Java. This console-based program helps you manage your expenses effectively by allowing you to add, view, and organize your financial records. 

---

## Features ✨

- **Add Expenses**: Record details of your expenses, including date, category, description, and amount.
- **Display Expenses**: View all recorded expenses with a summary of details.
- **Interactive Menu**: A simple interface to navigate through the application.

---

## How to Use 🕹️

### Menu Options:
1. **Add a New Expense**:
   - Input details such as date, category, description, and amount.
   - The program validates numeric inputs to ensure accuracy.
2. **Display All Expenses**:
   - Lists all recorded expenses with details.
   - Shows the total number of expenses recorded.
3. **Exit**:
   - Ends the application with a friendly goodbye message.

---

## Setup and Running the Program 🚀

1. **Prerequisites**:
   - Java Development Kit (JDK) installed (Java 8+ recommended).

2. **Steps to Run**:
   - Save the program in a file named `ExpenseTracker.java`.
   - Compile the program using:
     ```bash
     javac ExpenseTracker.java
     ```
   - Run the program with:
     ```bash
     java ExpenseTracker.ExpenseTracker
     ```

---

## Example Usage 💡

**Add Expense**:
```plaintext
==== Personal Expense Tracker ====
1. Add a new expense
2. Display all expenses
3. Exit
Choose an option: 1
Enter date (dd/mm/yyyy): 24/11/2024
Enter category: Food
Enter description: Lunch with friends
Enter amount: 500

Expense added successfully!
```

**Display Expenses**:
```plaintext
==== Personal Expense Tracker ====
1. Add a new expense
2. Display all expenses
3. Exit
Choose an option: 2

Listing all expenses:
---------------------------------
Category   : Food
Amount     : ₹500.00
Description: Lunch with friends
Date       : 24/11/2024
---------------------------------
Total expenses: 1
```

---

## Key Highlights 🛠️

- **Data Structure**: Utilizes an `ArrayList` to store expense records.
- **Validation**: Ensures correct numeric inputs for amounts.
- **Reusable Methods**: Encapsulates expense-related operations in a dedicated `Expense` class.

---

## Future Enhancements 🌟

- **Search and Filter**: Add options to filter expenses by category or date.
- **Expense Summary**: Provide a breakdown of total expenses by category.
- **Data Persistence**: Save and load expenses from a file to retain data between sessions.

---

Start tracking your expenses efficiently with this handy program! 🚀
