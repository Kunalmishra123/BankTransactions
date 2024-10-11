# Bank Transactions

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Database Connection](#database-connection)


## Introduction
The Bank Transactions project is a web application designed to manage and analyze bank transactions. Users can view, add, edit, and delete transactions, providing a clear overview of their banking activities.

## Features
- User authentication
- View transaction history
- Add new transactions
- Edit existing transactions
- Delete transactions
- Filter transactions by date, type, or amount

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** C#
- **Database:** Microsoft SQL Server 

## Prerequisites
Before you begin, ensure you have the following installed:
- Microsoft SQL Server Management Studio 
- Visual Studio 2022
- Git

## Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/Kunalmishra123/BankTransactions.git

## Database Connection
1. **Create a appsettings.json file in the root directory (if it doesn't already exist).
     Add your database connection string:**
   ```bash
   "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=BankTransactions;Trusted_Connection=True;"
   },

To update your local databse use below command:
- Update-Database 

  
   
