# Bank Management System - User Guide

## Introduction

This guide explains how to use the Bank Management System. The system uses C++ and file handling for data storage.

Use the system to manage bank accounts. The system stores data in a file named `accounts.dat`.

Download the GitHub repository. After you download the repository, compile the code using `g++`.

Click **Run** to start the account creation process.

## Features

The system provides the following features:

*   Create an account.
*   Delete an account.
*   Check the balance by entering the account number.
*   Transfer money from one account to another.

For file handling, the system uses the `fstream` library. It uses the `ifstream` and `ofstream` classes for reading and writing. It saves data in binary mode.

The C++ code uses OOP concepts. The system uses inheritance. `Account` is the base class, and `SavingsAccount` and `CurrentAccount` are the child classes.

You don't need an internet connection. You can run the system offline.

## How to use the system

Follow these steps:

1.  Open the `main.cpp` file in Visual Studio Code.
2.  Compile the program using `g++ main.cpp -o bms`.
3.  Run the `bms.exe` file.
4.  Select an option from the menu.
5.  Enter the account number.

When you enter the account number, the system displays the details. If the system doesn't find the account, it shows an error message.

The system stores data in the file. Don't delete the file. If you delete the file, you lose all data.

## Installation requirements

You need the following requirements:

*   Install Visual Studio Code.
*   Install the `g++` compiler on your laptop.
*   You need 100 MB of RAM.
*   Use Windows 10 or higher.

Download the `setup.exe` file from the internet. Double-click the file to complete the installation.

## Important notes

Keep your password safe. Use the logout feature after you finish your work.

If you find a bug, report the issue on GitHub. You can contact the developer by email.

This documentation uses Google Docs, and GitHub hosts the code.

You don't need a JavaScript file for this C++ project. You also don't need a Node.js environment.

A future version of the system will support the MySQL database.

For more information, read the full documentation.

