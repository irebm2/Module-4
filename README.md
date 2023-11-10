# Module-4

#README file for Console-Finances repository

Console Finances
This repository contains the code for a JavaScript application that analyzes the financial records of a company. The application calculates the following metrics:

Total number of months included in the dataset
Net total amount of Profit/Losses over the entire period
Average of the changes in Profit/Losses over the entire period
Greatest increase in profits (date and amount) over the entire period
Greatest decrease in losses (date and amount) over the entire period
The application uses the following JavaScript features:

Arrays
Loops
Conditional statements
Console logging
Instructions
To run the application, clone this repository to your local computer and install the dependencies. Then, open the index.html file in a web browser.

Code overview
The application code is contained in the index.js file. The code begins by parsing the financial dataset into an array of objects. Each object represents a month and contains the following properties:

Date: The date of the month
Profit/Losses: The amount of profit or loss for the month
The code then calculates the following metrics:

Total number of months: The number of elements in the finances array.
Net total amount of Profit/Losses: The sum of the Profit/Losses values in the finances array.
Average of the changes in Profit/Losses: The sum of the Profit/Losses changes divided by the number of changes.
Greatest increase in profits: The highest Profit/Losses value in the finances array.
Greatest decrease in losses: The lowest Profit/Losses value in the finances array.
Finally, the code logs the results to the console.

Example output
Financial Analysis
----------------------------
Total Months: 86
Total: $38382578
Average Change: -2315.12
Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
