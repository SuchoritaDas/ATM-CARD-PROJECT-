# ATM-CARD-PROJECT-

Requirements Python 3.6
a. Jupyter Notebook 7.2
b.Pycharm 2024 3.1.1

Features:
a.Check Balance: Users can check their current account balance.
b.Deposit Funds: Users can deposit funds into their account.
c.Withdraw Funds: Users can withdraw funds from their account, provided they have sufficient balance.
d.View Transactions: Users can view their transaction history.
e.Change PIN: Users can change their account PIN for security.

Code Overview:
1.Account Class--
The Account class models a bank account and includes methods for various banking operations.

2.Attributes--
card_number: The card number associated with the account.
pin: The PIN associated with the account.
balance: The current balance of the account.
transactions: A list to store transaction history.

3.Methods--
deposit(amount): Deposits a specified amount to the account and updates the transaction history.
withdraw(amount): Withdraws a specified amount from the account if sufficient funds are available and updates the transaction history.
check_balance(): Prints the current balance.
print_transactions(): Prints the transaction history.
change_pin(): Changes the account PIN after validating the current PIN.

4.Authentication Function--
The authenticate function verifies the user's credentials by checking the provided card number and PIN against the stored accounts. It returns the account if authentication is successful, otherwise it returns None.

5.Main Function--
The main function runs the ATM simulation.
It prompts the user for their card number and PIN, authenticates the user, and provides a menu for performing various banking operations.
It includes error handling for invalid inputs and performs the chosen operations.

6.Future Improvements--
Here are some potential improvements that can be made to the project:
Enhanced Security: Implement encryption for storing and transmitting sensitive information.
Optimized Authentication: Use a dictionary for faster account lookups.
Transfer Funds: Add functionality to transfer money between accounts.
Logging: Implement a logging mechanism for security auditing and tracking.
