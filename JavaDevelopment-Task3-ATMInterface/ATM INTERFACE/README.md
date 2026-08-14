# 🏦Console-Based ATM Interface

A robust, object-oriented console-based ATM (Automated Teller Machine) simulation built in **Java**. This project simulates core banking operations including secure user authentication, cash withdrawals, deposits, peer-to-peer account transfers, and real-time transaction history tracking.

---

## ✨ Features

* **Secure Authentication**: User ID and PIN-based login with a maximum 3-attempt security lockout.
* **Account Operations**:
  * **Balance Inquiry & Deposit**: Securely add funds with real-time balance updates.
  * **Cash Withdrawal**: Validates withdrawal amounts against available account balances.
  * **Peer-to-Peer Transfers**: Transfer funds securely to other registered accounts with automatic sender and recipient logging.
* **Transaction History Logs**: Automatically records date, time, transaction type, amount, and resulting balance for every session action.
* **Robust Input Validation**: Error-handling mechanisms to prevent crashes caused by invalid inputs or text formatting errors.

---

## 🛠️ Tech Stack

* **Language:** Java
* **Libraries Used:** `java.util.*`, `java.time.*`

---

## 📂 Project Structure

```text
ATM/
│
├── src/
│   └── atm/
│       ├── Main.java         # Entry point & mock account seeding
│       ├── ATM.java          # User interface and menu navigation logic
│       ├── Bank.java         # Account registry and authentication manager
│       ├── Account.java      # Core banking logic (deposit, withdraw, transfer)
│       └── Transaction.java  # Transaction details and timestamp formatter
│
└── README.md
