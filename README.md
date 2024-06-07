# BankAccount Project

## Overview

The BankAccount project simulates a basic banking system where users can manage their checking and savings accounts. It supports operations like deposits, withdrawals, and checking balances. Additionally, it tracks the total number of accounts and the total amount of money in all accounts.

## Features

- Create checking and savings accounts.
- Deposit and withdraw money from accounts.
- Check individual and total balances.
- Generate unique account numbers for each account.
- Track the number of accounts and the total money in all accounts.

## Usage

### Class: BankAccount

#### Attributes

- `private double checkingBalance`
- `private double savingsBalance`
- `private String accountNumber`
- `private static int numberOfAccounts`
- `private static double totalMoney`

#### Methods

- `public BankAccount()`: Constructor to create a new account.
- `public double getCheckingBalance()`: Returns the checking account balance.
- `public double getSavingsBalance()`: Returns the savings account balance.
- `public void deposit(double amount, String accountType)`: Deposits money into the specified account type.
- `public void withdraw(double amount, String accountType)`: Withdraws money from the specified account type if funds are sufficient.
- `public double getTotalBalance()`: Returns the total balance of checking and savings accounts.
- `public static int getNumberOfAccounts()`: Returns the total number of accounts created.
- `public static double getTotalMoney()`: Returns the total amount of money in all accounts.
- `public String getAccountNumber()`: Returns the account number.

## Expected Output

The application will create two bank accounts, deposit money into checking and savings accounts, withdraw money from the accounts, display the balances after each operation, and print the total number of accounts and total money across all accounts.

