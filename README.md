# PyBank 🏦

A command-line banking application built in Python that simulates core banking operations with secure authentication and input validation.

## About the Project

PyBank was built as a personal project to apply core Python fundamentals in a real-world context. It simulates basic banking operations a user would expect — opening an account, logging in, making transactions, and checking balance — all with security checks in place.

## Features

- **Account Creation** — collects and validates user details including phone number, Aadhar, and PAN
- **Secure Login** — account number based username with PIN authentication
- **Transactions** — credit and debit with live balance updates
- **Balance Check** — secured behind account number and PIN verification
- **Input Validation** — empty inputs, wrong lengths, and invalid data are all caught and re-prompted
- **Random Account Number** — unique 6-digit account number generated at account creation

## Concepts Used

- Functions
- While loops and conditionals
- Input validation
- List-based data storage
- Python "random" module

## How to Run

1. Make sure Python is installed on your system
2. Clone this repository
3. Run the file:

Code File Name:

python Banking.py


4. Follow the on-screen menu to interact with the app

## Menu Options

| Option | Action |
|--------|--------|
| 1 | Open a new account |
| 2 | Log in to existing account |
| 3 | Check available balance |
| 4 | Exit |

## What I Learned

- How to structure a multi-function Python program
- Importance of input validation and secure data handling
- Debugging logic errors and fixing security loopholes
- Writing clean, readable code

## Future Improvements

- Save accounts to a file using JSON so data persists after the program closes
- Transaction history showing last 5 transactions
- Wrong PIN lockout after 3 attempts
- Multiple account support

## Author

**Subhashree Mudada**  
B.Sc. Computer Science | Thakur Shyamnarayan Degree College  
[LinkedIn](http://linkedin.com/in/subhashree-mudada-388776387)
