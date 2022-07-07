# blockchain_payments


This repository includes code for a mock blockchain payment system for employees with streamlit for the UI. The code is split into two sections, the first is crypto_wallet.py which includes various functions like generate_account, get_balence and send_transaction that are called in fintech_finder.py. As we are not connecting to the ethereum network itself a mock blockchain was created using Ganache. Here accounts were made and connected to using Web3.HTTPProvider. Once connected to Ganache the user is able to pay their employees by using their hourly rate and multiplying it by an inputed number of hours. Once the transaction is sent the block is validated and the amount sent is transfered out of the original "bosses" account.

Validation:
![picture](https://github.com/alexszabodefi/blockchain_payments/blob/main/Images/Screen%20Shot%202022-07-07%20at%209.09.48%20AM.png)

Account Balence:
![picture](https://github.com/alexszabodefi/blockchain_payments/blob/main/Images/Screen%20Shot%202022-07-07%20at%209.10.56%20AM.png)

