🏦 ATM Management System (Python OOP Project)

A console-based ATM Management System developed using Python Object-Oriented Programming (OOP) concepts.
This project simulates basic ATM operations such as PIN verification, balance inquiry, deposits, withdrawals, and transaction history.


📌 Features

🔐 Secure PIN verification (3 attempts)

💰 Check account balance

➕ Deposit money

➖ Withdraw money with a maximum limit

📜 Transaction history tracking

🧾 Transaction counter

🚫 Card blocking after multiple incorrect PIN attempts

🛠️ Technologies Used


Python 3

OOP Concepts

Abstraction

Encapsulation

Inheritance

Polymorphism

ABC Module (abc)


🧠 OOP Concepts Implemented
Concept	Description
Abstraction	Enforced using ABC and @abstractmethod
Encapsulation	Private & protected variables (__, _)
Inheritance	A_T_M inherits from Account and BankAccount
Polymorphism	Overriding abstract method
Class Method	Bank name display

📂 Project Structure
ATM-Management-System/
│
├── atm.py        # Main Python program
└── README.md     # Project documentation

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/ATM-Management-System.git

2️⃣ Navigate to Project Folder
cd ATM-Management-System

3️⃣ Run the Program
python atm.py


🧑‍💻 User Flow

Enter account holder details

Set a 4-digit ATM PIN

Verify PIN (max 3 attempts)

Choose ATM options:

Check balance

Deposit money

Withdraw money

View transaction history

Exit


🧪 Sample Output
----------
 Welcome to
 ABC Bank!
----------

Enter Account Holder Name: Syam
Enter Account Number: 123456
Enter Initial Balance: ₹5000
Set 4-digit ATM PIN: 1234

PIN Verified Successfully!

ATM MENU
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Transaction History
5. Exit
   

🔒 Withdrawal Rules

Maximum withdrawal limit: ₹10,000

Cannot withdraw more than available balance

Negative or zero amounts are not allowed

🚀 Future Enhancements

Add file/database storage

Multiple user support

GUI using Tkinter

PIN encryption

Admin panel

📚 Learning Purpose

This project is ideal for:

Python beginners

OOP practice

Mini projects

College assignments

Interview preparation

🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

📄 License

This project is free to use for learning and educational purposes.

👨‍💻 Author

Syam Sundar
📍 India
💡 Python | Java | Data Analyst Enthusiast

⭐ If you found this project helpful, don’t forget to star the repository!
