# Banking Application 🏦
Welcome to the Banking Application, a Java-based solution designed to simplify banking operations for users. This application allows for seamless management of accounts, whether you're a new user registering for the first time or an existing user managing your finances.

## Features 🌟
### User Registration:
  - New users can easily register and create a banking profile.
  - Existing users can log in directly to access their accounts.
### Account Management:

- **Create Account:** New users can set up a bank account after registration.
- **Login:** Existing users can log in using their credentials to access their accounts.
### Banking Operations:

- **Debit Money:** Withdraw funds from your account.
- **Credit Money:** Deposit funds into your account.
- **Transfer Money:** Transfer funds to other accounts securely.
- **Check Balance:** View your current account balance.
- **Check Account Details:** Review your account details, including transaction history.
- **Log Out:** Securely log out of the application.

# Getting Started 🚀

### Prerequisites
- Java Development Kit (JDK)
- MySQL Database
- MySQL Connector/J (Java)


### Setup


1. **Clone the Repository:**
```bash
Copy code
git clone https://github.com/yourusername/Banking-Application.git
```
2. **Configure Database Settings:**
Open the `BankingApp.java file` and update the database settings:

```java
Copy code
private static final String DB_URL = "jdbc:mysql://localhost:3306/your_database_name";
private static final String DB_USER = "your_username";
private static final String DB_PASSWORD = "your_password";
```
3. **Compile and Run:**
4. 
Compile and run the application using your preferred IDE or command line tools.

```bash
Copy code
javac Main.java
java Main
```

# Usage 📋

Upon running the application, you’ll be presented with the following options:

- **Register:** Create a new user profile and set up a bank account.
- **Login:** Access your account if you're an existing user.

#### Perform Operations:
- **Debit Money:** Withdraw funds from your account.
- **Credit Money:** Add funds to your account.
- **Transfer Money:** Transfer money to other accounts.
- **Check Balance:** View your account balance.
- **Check Account Details:** Review your account details.
- **Log Out:** Securely exit the application.

Follow the on-screen prompts to perform your desired operations.

# Contributing 🤝
We welcome contributions! If you have suggestions for improvements, new features, or bug fixes, feel free to open issues or submit pull requests.

# Acknowledgments 🙏
Special thanks to all contributors and users of the Banking Application. Your feedback and support are invaluable!

Happy banking! 🏦

