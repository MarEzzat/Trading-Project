# Trading Project

## Overview

**Trade Account Manager** is a Java application that simulates the creation and management of trade accounts, including both **Cash Accounts** and **Margin Accounts**. It reads account data and transaction data from text files, processes deposits and withdrawals, and displays the final balances of selected accounts.

This project demonstrates object-oriented programming, file I/O, and service/repository design patterns in Java.

## How It Works

1. **Load Trade Accounts**: Reads account data from `accounts.txt` and initializes either `CashAccount` or `MarginAccount` objects.
2. **Apply Transactions**: Processes each transaction (deposit or withdraw) from `transactions.txt`.
3. **Final Test**: Prints the balances of selected accounts to the console for verification.

## Technologies Used

- Java 11+
- Object-Oriented Programming (OOP)
- File I/O (`java.nio.file`)
- `BigDecimal` for accurate financial calculations

## Features

- Support for both Cash and Margin accounts
- Accurate financial processing with `BigDecimal`
- Clean separation using services and repositories
- Easily extendable for future features
