# Personal Expense Tracker 💰

A lightweight **Personal Expense Tracker** built with Java, designed to help you manage your expenses easily. This console-based application allows you to add, view, and organize your financial records with an intuitive menu-driven interface.

---

## Features ✨

- **Add Expenses**: Record your expenses with details like date, category, description, and amount.
- **View Expenses**: Display all recorded expenses with a summary.
- **User-Friendly**: Simple and interactive console interface for easy navigation.
- **Input Validation**: Ensures proper numeric input for expense amounts.

---

## Installation and Setup 🚀

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AbdulRehman-18/Personal-Expense-Tracker.git
   cd Personal-Expense-Tracker
   ```

2. **Compile the Program**:
   - Ensure you have Java installed (Java 8+).
   - Run the following command:
     ```bash
     javac src/ExpenseTracker/ExpenseTracker.java
     ```

3. **Run the Program**:
   ```bash
   java src.ExpenseTracker.ExpenseTracker
   ```

---

## Usage 🕹️

### Menu Options:
1. **Add a New Expense**:
   - Record an expense by entering the date, category, description, and amount.
2. **Display All Expenses**:
   - View all recorded expenses with details and the total number of entries.
3. **Exit**:
   - Safely exit the application.

---

## Example Session 💡

**Add Expense**:
```plaintext
==== Personal Expense Tracker ====
1. Add a new expense
2. Display all expenses
3. Exit
Choose an option: 1
Enter date (dd/mm/yyyy): 24/11/2024
Enter category: Transportation
Enter description: Train ticket
Enter amount: 150

Expense added successfully!
```

**View Expenses**:
```plaintext
==== Personal Expense Tracker ====
1. Add a new expense
2. Display all expenses
3. Exit
Choose an option: 2

Listing all expenses:
---------------------------------
Category   : Transportation
Amount     : ₹150.00
Description: Train ticket
Date       : 24/11/2024
---------------------------------
Total expenses: 1
```

---

## Contributing 🤝

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## Future Enhancements 🌟

- **Filter Options**: Allow filtering expenses by category or date.
- **Summary Report**: Provide a breakdown of expenses by category.
- **Persistence**: Add file-based storage for saving and loading expenses.

---

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### Start managing your expenses today! 💼
