# Console-Finances Repository

## Overview
This repository contains the code for a JavaScript application that analyzes the financial records of a company. The application calculates various financial metrics, including the total number of months, net total amount of Profit/Losses, average changes in Profit/Losses, greatest increase in profits (date and amount), and greatest decrease in losses (date and amount).

## Instructions
To run the application, follow these steps:
1. Clone this repository to your local computer.
2. Install the dependencies.
3. Open the `index.html` file in a web browser.

## Code Overview
The main application code is located in the `index.js` file. Here's an overview of the code structure:

### Financial Dataset
The code begins by parsing the financial dataset into an array of objects. Each object represents a month and includes the following properties:
- **Date:** The date of the month.
- **Profit/Losses:** The amount of profit or loss for the month.

### Metrics Calculations
The code calculates the following financial metrics:
- **Total number of months:** The number of elements in the finances array.
- **Net total amount of Profit/Losses:** The sum of the Profit/Losses values in the finances array.
- **Average of the changes in Profit/Losses:** The sum of the Profit/Losses changes divided by the number of changes.
- **Greatest increase in profits:** The highest Profit/Losses value in the finances array.
- **Greatest decrease in losses:** The lowest Profit/Losses value in the finances array.

### Results Logging
Finally, the code logs the results to the console.

## Deployed URL
Console-Finances Deployment: https://irebm2.github.io/Module-4/

## Screenshot

<img width="919" alt="image" src="https://github.com/irebm2/Module-4/assets/146390674/6ee2bde4-9ef6-44c3-9c5d-512d411dd04e">


## Code Source
This code is original and written by Irene Bazaga.


## Example Output
```plaintext
Financial Analysis
Total Months: 86
Total: $38,382,578
Average Change: -$2,315.12
Greatest Increase in Profits/Losses: Feb-2012 (1,926,159)
Greatest Decrease in Profits/Losses: Sep-2013 (-2,196,167)








