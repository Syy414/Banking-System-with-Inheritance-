# Banking System with Inheritance

A Java-based banking system that demonstrates Object-Oriented Programming principles, specifically **inheritance** and **polymorphism**. This interactive console application allows users to create and manage different types of bank accounts with unique features.

## Features

### Account Types

1. **Savings Account**
   - Interest calculation based on balance
   - Minimum balance requirement ($10.00)
   - Interest automatically added to balance

2. **Current Account**
   - Overdraft facility
   - Transaction fees ($1.50 per withdrawal)
   - No interest earnings

### Core Functionality

- ✅ Create accounts with custom details
- ✅ Deposit funds
- ✅ Withdraw funds with validation
- ✅ Calculate interest (Savings Account only)
- ✅ View account information
- ✅ Interactive menu-driven interface

## Object-Oriented Concepts Demonstrated

- **Inheritance**: `SavingsAccount` and `CurrentAccount` extend the base `Account` class
- **Polymorphism**: Runtime polymorphism through method overriding
- **Encapsulation**: Protected fields with public methods
- **Method Overriding**: Different implementations of `withdraw()` and `calculateInterest()`

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Command line terminal or Java IDE

### Compilation

```bash
javac BankingSystem.java
```

### Running the Program

```bash
java BankingSystem
```

## Usage

1. **Account Creation**
   - Enter account holder name
   - Enter account number
   - Enter initial balance
   - Select account type (Savings or Current)
   - Provide additional details based on account type

2. **Menu Options**
   - **Display Info**: View current account details
   - **Deposit**: Add funds to the account
   - **Withdraw**: Remove funds (subject to account-specific rules)
   - **Calculate Interest**: Calculate and add interest (Savings Account only)
   - **Exit**: Close the application

## Example

```
=== CREATE YOUR ACCOUNT ===
Enter Account Holder Name: John Doe
Enter Account Number: SA001
Enter Initial Balance: 1000

Select Account Type:
1. Savings Account
2. Current Account
Choice: 1
Enter Interest Rate (%): 5

Account Created Successfully!

=== MENU ===
1. Display Info
2. Deposit
3. Withdraw
4. Calculate Interest
5. Exit
Choose an action: 4

Calculated Interest: $50.0
Success! New Balance: $1050.0
```

## Class Structure

```
Account (Base Class)
├── SavingsAccount
│   ├── Interest rate
│   ├── Minimum balance constraint
│   └── Interest calculation
└── CurrentAccount
    ├── Overdraft limit
    ├── Transaction fees
    └── No interest
```

## Project Structure

```
Banking-System-with-Inheritance/
├── BankingSystem.java       # Main source file
├── README.md                # Project documentation
└── .gitignore               # Git ignore rules
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Author

**Syy414**
- GitHub: [@Syy414](https://github.com/Syy414)
- Youtube: [@Syy414](https://youtu.be/ctURZMSaKFY)
---

⭐ If you found this project helpful, please consider giving it a star!
