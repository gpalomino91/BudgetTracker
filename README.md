# **Budget Tracker**

### **Description**
Console application to manage income, expenses, and calculate financial balances easily.

---

### **Features**
- Add income with date, description, amount, and category.
- Add expenses with date, description, amount, and category.
- View a list of all incomes and expenses.
- Calculate total income, total expenses, and overall balance.
- User-friendly console interface.

---

### **Requirements**
- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0)

---

### **How to Run the Project**

1. **Clone the repository:**
    ```sh
    git clone https://github.com/gpalomino91/BudgetTracker.git
    cd BudgetTracker
    ```

2. **Build the project:**
    ```sh
    dotnet build
    ```

3. **Run the application:**
    ```sh
    dotnet run
    ```

---

### **Usage**
1. Select an option from the menu:
    ```
    ====== Budget Tracker ======
    1. Add Income
    2. Add Expense
    3. View Incomes
    4. View Expenses
    5. Calculate Total Balance
    6. Exit
    ============================
    Select an option:
    ```

2. Follow the on-screen prompts to add or view financial records.
3. The balance is calculated as:
    ```
    Balance = Total Income - Total Expenses
    ```

---

### **Project Structure**
```
BudgetTracker
├── BudgetTracker.csproj
├── Program.cs
├── Models
│   ├── Income.cs
│   └── Expense.cs
└── Services
    └── FinancialRecord.cs
```

- **Program.cs**: Entry point of the application.
- **Models**: Contains data models for `Income` and `Expense`.
- **Services**: Manages financial records and calculations.

---

### **License**
This project is licensed under the MIT License.

---

### **Author**
- **Gonzalo Palomino** - GitHub Profile: https://github.com/gpalomino91 | LinkedIn: https://www.linkedin.com/in/gpalominotorres/

---

### **Notes**
- This is a simple console-based budget tracker for learning purposes.
- Contributions are welcome! Feel free to open issues or submit pull requests.

---

### **TODOs**
- Add data persistence (save records to a file or database).
- Implement editing and deleting of records.
- Improve user input validation and error handling.

---

### **Enjoy managing your budget!** 🚀

