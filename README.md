# A PWA Budget Tracker
An Online/Offline Budget Tracker giving users a fast and easy way to track their money, allowing them to access the information anytime.

---------------

[Links](#Links)
<br>
[UserStory](#UserStory)
<br>
[Description](#Description)
<br>
[Installation](#Installation)
<br>
[Usage](#Usage)
<br>
[FutureDevelopment](#FutureDevelopment)

<br>
---------------

## Links

[GitHub Repository:](https://github.com/RAMulc/BudgetTracker)

[Heroku:](https://ram-budget-tracker.herokuapp.com/)

## **UserStory**

- As an avid traveller;
- I want to be able to track my withdrawals and deposits with or without a data/internet connection;
- So that my account balance is accurate when I am traveling.

## Description

A simple Budget Tracker application to allow for both online and offline access using MongoDB, Node, IndexedDB and Express. The app is deployed to Heroku and makes use of MongoDB Atlas for the backend online database, with IndexedDB utilised for temporary offline storage.



Upon opening the app, the user is presented with their current balance, fields to name a transaction along with its associated value, a list of previous transactions, and a graphical representation of previous transactions/balances.

![The Application](https://github.com/RAMulc/BudgetTracker/blob/main/assets/img/ScrnSht.png)

When the user has online access to the MongoDB Atlas database, transactions are uploaded upon selecting the appropriate button (to add or remove funds). If the user should be afflicted with a lack of access to the internet, the transactions will be temporarily stored in IndexedDB database. These transactions will be uploaded to the MongoDB Atlas database upon restoration of the online connection.

## Installation

Run npm install to install the required packages.

## Usage

Run 'node server.js' or 'npm start' at the command line to start the program or [run from Heroku.](https://ram-budget-tracker.herokuapp.com/).


## FutureDevelopment

Allow for:

- Multiple users with logins;
- Selection of desired currency;
- Deletion of existing records;
- Update of existing records; and
- Allow user to select desired graphical representation of balance over time.



---------------

[About Me...](https://ramulc.github.io/Portfolio/)
