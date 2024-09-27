
# Customer Banking Application

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Usage](#usage)
  - [Example Interaction](#example-interaction)
- [File Structure](#file-structure)
- [Project Resources and Acknowledgments](#project-resources-and-acknowledgments)
- [Conclusion](#conclusion)

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
## Project Resources and Acknowledgments

- **Starter Files**: The starter files were provided as part of the project, serving as a foundation for the application.
- **Class Concepts**: Throughout this project, we studied various programming concepts, including:
  - **Functions**: Understanding how to define and use functions effectively.
  - **Setters and Getters**: Implementing setter and getter methods to encapsulate object properties.
  - **Inheritance**: Exploring how to create classes that inherit from other classes, allowing for code reuse and organization.


## Conclusion
The Customer Banking Application provides a practical solution for users to manage their savings and CD accounts effectively. By allowing users to calculate interest based on their input parameters, the application simplifies financial planning and helps users make informed decisions about their savings. Throughout the development of this project, we reinforced our understanding of essential programming concepts, including classes, functions, and encapsulation.

This project serves not only as a tool for personal finance management but also as a valuable learning experience, enhancing our programming skills and knowledge in software development. We look forward to further enhancements and additional features that could make the application even more robust and user-friendly in the future.


> >Thank you to our instructors and classmates for their support and guidance during this project.
