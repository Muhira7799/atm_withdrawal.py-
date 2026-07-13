# atm_withdrawal.py-
# ATM Withdrawal Testing Tool 

## Overview

The **ATM Withdrawal Testing Tool** is a simple Python console application that simulates an ATM withdrawal system.

The program checks the entered withdrawal amount and returns either a successful transaction message or a rejection message based on the withdrawal rules.

This project was created to practice Python programming, conditional logic, input validation, and basic software testing concepts.

## Withdrawal Rules

The ATM system follows these rules:

| Withdrawal Amount | Result                                |
| ----------------- | ------------------------------------- |
| Less than $20     | Rejected: Minimum withdrawal is $20   |
| $20 - $500        | Successful withdrawal                 |
| More than $500    | Rejected: Maximum daily limit is $500 |

## Features

* Accepts user input for withdrawal testing.
* Validates withdrawal amounts.
* Displays clear success and rejection messages.
* Handles invalid inputs using exception handling.
* Allows users to test multiple amounts until typing `exit`.

## Technologies Used

* Python 3
* VS Code
* GitHub

## How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/ATM-Withdrawal-Testing.git
```

Run the program:

```bash
python atm_withdrawal.py
```

## Testing Examples

### Valid Withdrawal

Example:

```
Input: 409

Output:
SUCCESS: Please take your cash.
```

### Invalid Withdrawal

Example:

```
Input: 19

Output:
REJECT: Minimum withdrawal is $20.
```

## Screenshot

The following screenshot shows the ATM testing results for different withdrawal values:

![ATM Testing Results](images/screenshot.png)

## Boundary Value Testing

This project demonstrates **Boundary Value Analysis (BVA)** by checking values around the system limits:

* 19 → Rejected
* 20 → Accepted
* 500 → Accepted
* 501 → Rejected

## Learning Outcomes

Through this project, I practiced:

* Writing Python functions
* Using conditional statements
* Handling user input errors
* Applying basic software testing techniques
* Understanding boundary conditions
t
