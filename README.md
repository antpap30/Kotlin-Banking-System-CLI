# 🏦 Kotlin Banking System CLI

An interactive Kotlin console application that lets users create debit, credit, or checking accounts and manage custom euro deposits and withdrawals through a continuous menu loop with built-in balance rules and input validation.

## ✨ Features

- 💳 Account types: Create a Debit, Credit, or Checking account.
- 💶 Custom transactions: Enter specific deposit and withdrawal amounts in euros (€).
- 🛡️ Balance protection: Prevents overdrafts on debit accounts and overpayments on credit accounts.
- ✅ Input validation: Safely handles invalid or non-numeric console inputs.

## 🚀 Getting Started

### 📋 Prerequisites

- JDK 17 or higher
- IntelliJ IDEA or the Kotlin command-line compiler (`kotlinc`)

### 💻 Run the Project

Clone the repository:

```bash
git clone [https://github.com/antpap30/Kotlin-Banking-System-CLI.git](https://github.com/antpap30/Kotlin-Banking-System-CLI.git)
cd Kotlin-Banking-System-CLI
```

Open the project folder in IntelliJ IDEA, navigate to `src/Main.kt`, and run `main()`.

Alternatively, compile and run from the terminal:

```bash
kotlinc src/Main.kt -include-runtime -d BankingSystem.jar
java -jar BankingSystem.jar
```

## 🖥️ Example

```text
Welcome to your banking system.
What type of account would you like to create?
1. Debit account
2. Credit account
3. Checking account
Choose an option (1, 2 or 3)
1
The selected option is 1.
You have created a debit account.

What would you like to do?
1. Check bank account balance
2. Withdraw money
3. Deposit money
4. Close the app
Which option do you choose? (1, 2, 3 or 4)
2
Enter the amount to withdraw (in euros):
100
You successfully withdrew 100 euros. The checking balance is 440 euros.
The amount you withdrew is 100 euros
```
