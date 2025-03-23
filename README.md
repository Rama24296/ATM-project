# ATM-project

# ATM Simulation

## Overview

This is a simple ATM simulation program written in Python. It allows users to perform basic banking operations such as withdrawal, deposit, pin generation, mini statement, and pin reset. The program simulates the functionality of an ATM system and provides basic features for managing user accounts.

##Requirements  :
Python 3.x

##How to Run :
Clone or download the repository to your local machine.

Navigate to the project directory.

Run the Python script:

python atm_simulation.py


## Features

The ATM system supports the following operations:

1. **Withdrawal**:
   - Allows the user to withdraw money from the account after verifying the pin.
   - Checks for sufficient funds before allowing the withdrawal.

2. **Deposit**:
   - Allows the user to deposit money into the account.

3. **Pin Generation**:
   - Allows the user to generate a pin if not already set for the account.
   - Requires pin confirmation before setting.

4. **Mini Statement**:
   - Displays basic account details including account holder's name, date of birth, and current account balance.

5. **Reset Pin**:
   - Allows the user to reset the pin after verifying the old pin and confirming the new pin.

6. **Exit**:
   - Terminates the program.

## Data

The data is stored in a dictionary with the following structure:

```python
accounts = {
    1001 : ["Rama", "15-08-2000", 10000, 2408],
    1002 : ["Srujana", "05-06-2001", 20000, 1234],
    1003 : ["Anusha", "09-07-2000", 5000, None]
}
