# Console-Finances


## Background

We are tasked with creating code for analyzing the financial records of a company that are provided.

## User Story

```
As a Finance Manager I need my finances analysed
so that I can see the trends of our profit and loss over a period. 
```


## Acceptance Criteria

Follow the instructions:

### Instructions

You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

Your task is to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in Profit/Losses are from month to month and then find the average.
  * (`Total/(Number of months - 1)`)

* The greatest increase in Profit/Losses (date and amount) over the entire period.

* The greatest decrease in Profit/Losses (date and amount) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis 
  ----------------
  Total Months: 86
  Total: $38382578
  Average Change: -2315.12
  Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
  Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
  ```

Your final code should print the analysis to the console.


## Deliverable:

Follow the link to view the boostrap-portfolio landing page:

[https://pine-box.github.io/Bootstrap-Portfolio/](https://pine-box.github.io/Console-Finances/)

Output generated:

```text
Financial Analysis
------------------
Total Months: 86
Total: $38382578
Average Change: -2315.12
Greatest Increase in Profit/Losses: Feb-2012 ($1170593)
Greatest Decrease in Profit/Losses: Sep-2013 ($-1196225)
```text