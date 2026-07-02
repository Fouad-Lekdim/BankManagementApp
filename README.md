# 🏦 BankManagementApp

A C++ console-based Bank Management System that provides a secure, menu-driven interface for managing banking operations. Built with an OOP architecture and a clear separation between core business logic, reusable libraries, and UI screens.

---

## 📋 Features

- 🔐 **Authentication** — Login screen with session tracking and login history register
- 👤 **Client Management** — Add, update, delete, find, and list bank clients
- 💰 **Transactions** — Deposit, withdraw, transfer between accounts, and view transfer logs
- 💱 **Currency Exchange** — List, find, update exchange rates, and calculate currency conversions
- 👥 **User Management** — Add, update, delete, and manage system users with access control

---

## 🗂️ Project Structure

```
BankManagementApp/
├── UserInterface.cpp           # Entry point
├── Global.h                    # Global definitions
├── Users.txt                   # Persistent user data storage
│
├── core/                       # Business logic
│   ├── clsBankClient.h
│   ├── clsCurrency.h
│   ├── clsUser.h
│   └── clsPerson.h
│
├── Libs/                       # Reusable utility classes
│   ├── clsDate.h
│   ├── clsString.h
│   ├── clsInputValidate.h
│   └── clsUtil.h
│
└── Screens/                    # UI layer
    ├── clsMainScreen.h
    ├── clsScreen.h
    ├── Client/
    │   ├── clsAddNewCllientScreen.h
    │   ├── clsDeleteClientScreen.h
    │   ├── clsDepositScreen.h
    │   ├── clsFindClientScreen.h
    │   ├── clsShowAllClientsScreen.h
    │   ├── clsTotalBalancesScreen.h
    │   ├── clsTransactionsScreen.h
    │   ├── clsTransferLogRegisterScreen.h
    │   ├── clsTransferScreen.h
    │   ├── clsUpdateClientScreen.h
    │   └── clsWithdrawScreen.h
    ├── User/
    │   ├── clsAddNewUserScreen.h
    │   ├── clsDeleteUserScreen.h
    │   ├── clsFindUserScreen.h
    │   ├── clsLoginScreen.h
    │   ├── clsLoginRegisterScreen.h
    │   ├── clsManageUsersScreen.h
    │   ├── clsUpdateUserScreen.h
    │   └── clsUsersListScreen.h
    └── Currency/
        ├── clsCurrenciesListScreen.h
        ├── clsCurrencyCalculatorScreen.h
        ├── clsCurrencyExchangeScreen.h
        ├── clsFindCurrencyScreen.h
        └── clsUpdateRateScreen.h
```

---

## 🚀 Getting Started

### Requirements
- Windows OS
- No installation required

### How to run
1. Go to the [Releases](../../releases) section
2. Download the latest `BankManagementApp.zip`
3. Extract the zip file
4. Double-click `UserInterface.exe` to launch the app

> ⚠️ Make sure `Users.txt` stays in the **same folder** as the `.exe` file, otherwise login will not work.

---

## 🔑 Demo Credentials

| Username | Password |
|----------|----------|
| admin    | admin    |

---

## 🛠️ Built With

- **Language:** C++
- **IDE:** Visual Studio
- **Paradigm:** Object-Oriented Programming (OOP)

---

## 👨‍💻 Author

**Fouad LEKDIM**  
[GitHub Profile](https://github.com/Fouad-Lekdim)
