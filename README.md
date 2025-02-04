# 🏦 ATM Management System

## 📌 Overview
The **ATM Management System** is a **Java-based console application** that simulates **ATM functionalities**. It allows users to perform banking operations such as **withdrawing money, checking balances, and transferring funds** securely.

This system provides an intuitive interface and secure access, making it suitable for **educational purposes, banking simulations, and ATM-related software development.**

---

## 🎯 Features
✅ **User authentication with PIN-based login** - Ensures security and prevents unauthorized access.  
✅ **View account balance** - Displays available funds in the user's account.  
✅ **Cash withdrawal & deposit** - Allows users to withdraw or deposit funds efficiently.  
✅ **Fund transfers between accounts** - Enables users to transfer money between different accounts.  
✅ **Secure session handling** - Prevents unauthorized transactions by enforcing logout mechanisms.  
✅ **Error handling & validation** - Manages incorrect inputs, invalid transactions, and connection issues.  
✅ **OOP Principles & Modular Codebase** - Built using encapsulation, inheritance, and polymorphism for scalability.  

---

## 📂 Project Structure
```
atm-management-system/
│── src/
│   ├── Account.java            # Account details handling
│   ├── App.java                # Main entry point
│   ├── ATM.java                # ATM functionality
│   ├── OptionMenu.java         # User interface for options
│   ├── Transaction.java        # Transaction history management
│   ├── DatabaseHandler.java    # Handles account data storage (if DB is implemented)
│── bin/                        # Compiled Java classes
│── .vscode/                    # VS Code settings
│── README.md                   # Documentation file
│── LICENSE                     # Licensing information
```

---

## 🛠️ Installation & Setup
### Prerequisites
- **Java Development Kit (JDK)** (Version 8 or later) installed  
- **Terminal or Command Prompt**  
- **Text editor or IDE** (VS Code, IntelliJ, Eclipse, etc.)

### 🚀 Running the Application
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/your-repo/ATM-Management-System.git
   ```
2. **Navigate to the Project Directory**  
   ```sh
   cd ATM-Management-System
   ```
3. **Compile the Java Files**  
   ```sh
   javac -d bin src/*.java
   ```
4. **Run the Application**  
   ```sh
   java -cp bin App
   ```

### 🔧 Configuration (Optional)
- Modify **OptionMenu.java** to customize user prompts.  
- Implement **DatabaseHandler.java** to store transaction logs in a database.  
- Adjust **ATM.java** to set transaction limits.  

---

## 📊 Example Usage
1. **Login:** Users enter their account number and PIN for authentication.  
2. **Main Menu Options:**  
   - View Balance  
   - Withdraw Money  
   - Deposit Money  
   - Transfer Funds  
   - Transaction History  
   - Exit  
3. **Perform Transactions:** Users follow prompts to execute transactions.  
4. **Exit & Logout:** Securely logs out the user to prevent unauthorized use.  

---

## 🏗️ Future Enhancements
🔹 **GUI-based interface** for better user experience using JavaFX or Swing.  
🔹 **Database integration** using MySQL or SQLite for persistent data storage.  
🔹 **Multi-user support** with administrator and user roles.  
🔹 **Logging system** for transaction history tracking and fraud detection.  
🔹 **Mobile application integration** to extend ATM functionalities online.  

----
## ✉️ Contact
For any queries, reach out to:  
- **Vennela Kothakonda** - Developer  

Happy Coding! 🚀
