# Savings Account Smart Contract

## Technology
___
* Solidity version 0.5.0
* Remix IDE for compilation and deployment
* Ganache Local Blockchain
* Metamask for web injection

## Description
An application that allows a user to DEPOSIT and WITHDRAW from a Smart Contract Savings account
___

* User may transact with the account from any ethereum address via the DEPOSIT function

* User can only take from the account with two authorized accounts upon deployment of the smart contract via the WITHDRAW function

* Contract also has viewability functions for the balance, lastWithrawalAmount, and lastToWithdraw

## Application in Action
___
### Transaction Withdrawal to One of the approved accounts
![Transaction](./images/transaction.png)

### Viewer Functions following withdrawal to authorized account
![Viewer](./images/viewerfunctions.png)

### Ganache
![Ganache](./images/ganache.png)

### Transactions completed on smart contract 
![First Batch](./images/transactions1-5.png)
![Second Batch](./images/transactions6-8.png)

### Calling lastToWithdraw
![Last to Withdraw](./images/last_to_withdraw.png)

### Calling lastWithdrawalAmount
![Last to Withdraw](./images/last_withdraw_amount.png)

### Making a Deposit with Primary Account of 18eth
![Deposit Remix](./images/deposit.png)
![Deposit Terminal](./images/deposit_terminal.png)



