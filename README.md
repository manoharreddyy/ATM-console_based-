# ATM_Project_Console_Based

## Overview
ATM_Project_Console_Based is a simple console-based banking system implemented in Python. This project allows users to perform basic ATM operations such as withdrawing money, depositing money, generating or resetting a PIN, and viewing account details.

## Features
- **Withdraw Money** (Requires a valid PIN)
- **Deposit Money**
- **Generate/Reset PIN**
- **View Mini Statement** (Check balance and account details)
- **Exit the System**

## Functionalities
- Users can withdraw money if they have sufficient balance and enter the correct PIN.
- Deposits can be made without a PIN.
- PIN generation is required for new users, and existing users can reset their PIN.
- The mini statement displays the current balance, email, and username.
- The program runs in a loop until the user selects the exit option.

## How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ATM_Project_Console_Based.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd ATM_Project_Console_Based
    ```

3. **Run the Python script:**
    ```bash
    python atm.py
    ```

4. Follow the on-screen instructions to perform transactions.

## Data Structure
This project uses a dictionary (`accounts`) to store account details:

```python
accounts = {
    2001: [9200, 9347, "user1@gmail.com", "user1"],
    2002: [2040, 8096, "user2@gmail.com", "user2"],
    2003: [19000, None, "user3@gmail.com", "user3"]
}



