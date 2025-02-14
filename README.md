ATM_Project_Console_Based
Overview
ATM_Project_Console_Based is a simple console-based banking system implemented in Python. This project allows users to perform basic ATM operations such as withdrawing money, depositing money, generating or resetting a PIN, and viewing account details.

Features
Withdraw Money (Requires a valid PIN)
Deposit Money
Generate/Reset PIN
View Mini Statement (Check balance and account details)
Exit the System
Functionalities
Users can withdraw money if they have sufficient balance and enter the correct PIN.
Deposits can be made without a PIN.
PIN generation is required for new users, and existing users can reset their PIN.
The mini statement displays the current balance, email, and username.
The program runs in a loop until the user selects the exit option.
How to Use
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/ATM_Project_Console_Based.git
Navigate to the project directory:

bash
Copy
cd ATM_Project_Console_Based
Run the Python script:

bash
Copy
python atm.py
Follow the on-screen instructions to perform transactions.

Data Structure
This project uses a dictionary (accounts) to store account details:

python
Copy
accounts = {
    
}
Each account consists of:

Balance: Initial deposit amount
PIN: Security PIN for transactions (if set)
Email: User's registered email
Username: Account holder's name
Requirements
Python 3.x
Notes
This is a basic implementation and does not persist data after execution.
For security purposes, PINs are required for withdrawals and modifications.
The project can be extended by integrating a database for persistent storage.
License
This project is open-source and available for modification and distribution.
