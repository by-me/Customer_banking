
# Customer Banking Application

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Usage](#usage)
  - [Example Interaction](#example-interaction)
- [File Structure](#file-structure)


## Overview
The Customer Banking Application is a simple banking system that allows users to manage savings and CD (Certificate of Deposit) accounts. Users can create accounts, input their balance and interest rates, and calculate interest earned over a specified period.

## Features
- Create Savings Accounts
- Create CD Accounts
- Calculate interest earned on balances
- Update account balances with interest


## Getting Started

### Prerequisites
- Python 3.x
- Basic understanding of Python programming

### Usage 
1. Run the application 
```python customer_panking.py ```
2. Follow the prompts to enter your savings and CD account information.
### Example Interaction

``` Enter the savings balance: 1000
Enter the interest rate (APR) for the savings account: 5
Enter the number of months for the savings account: 11

Updated Savings Account Balance: $1,048.50
Interest Earned on Savings: $48.50

Enter the CD balance: 5000
Enter the interest rate (APR) for the CD account: 3
Enter the number of months for the CD account: 6

Updated CD Account Balance: $5,075.00
Interest Earned on CD: $75.00
```

## File Structure
```
/Customer-Banking-Application
│
├── Account.py              # Contains the Account class definition
├── savings_account.py       # Contains the create_savings_account function
├── cd_account.py            # Contains the create_cd_account function
├── customer_banking.py      # Main file to run the application
└── README.md                # Documentation file

```
