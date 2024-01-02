# Console-Finances

## Project Description
Console-Finances is a JavaScript-based solution designed to analyze 
financial records. The program processes an array of financial data, 
each entry containing a date and the corresponding profit or loss for that month.
It calculates various financial metrics, 
providing insights into the total number of months recorded, 
net total amount of profit/loss over the entire period, 
average monthly change in profit/loss, 
and identifying the greatest increase and decrease in profits over the entire period.

## Technologies Used
- JavaScript

## Installation and Usage
To use Console-Finances, follow these steps:
1. Clone the repository to your local machine.
2. Ensure that you have a browser to execute the script.
3. Open index.html in browser and open console there to see the results

## Features
Console-Finances includes the following features:
- Calculation of the total number of months included in the dataset.
- Computation of the net total amount of Profit/Losses over the entire period.
- Determination of the average change in Profit/Losses over the entire period.
- Identification of the greatest increase in profits (including the date and amount) over the entire period.
- Identification of the greatest decrease in losses (including the date and amount) over the entire period.

### total number of months
That is simple, just use the length property of the array

### total amount of Profit/Losses
Loop to the array where we acummulate all values in a single variable

### average change
The complexity is in understand how to calculate that, the solution is also simple
Starting in the second element, create a difference with the previous, accumulate the value then dvide by the number of elements

### greates increase or decrease
That is asking to find the max and min of changes, we can re-use the previous loop to ask the max and the min at same time

