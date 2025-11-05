# 💳 Bank System (C# Console Project)

A simple OOP-based banking system built in C#.  
Demonstrates the use of:
- Object-Oriented Programming (Inheritance, Interfaces, Encapsulation)
- Custom Exceptions
- Layered architecture (Models, Services, Data)
- Basic in-memory data management

## 🧩 Structure

BankSystem/
 ├── Program.cs
 ├── Models/
 │    ├── Account.cs
 │    ├── User.cs
 │    ├── Transaction.cs
 ├── Interfaces/
 │    ├── IAccountService.cs
 │    ├── IUserService.cs
 ├── Services/
 │    ├── AccountService.cs
 │    ├── UserService.cs
 ├── Exceptions/
 │    ├── InsufficientBalanceException.cs
 │    ├── UserNotFoundException.cs
 └── Data/
      ├── DataStorage.cs
      
## 🧠 Features
- Create users and accounts
- Deposit / Withdraw
- Transfer money between accounts
- Transaction history
- Exception handling (e.g., insufficient balance, user not found)

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/BankSystem.git

