# 5.5PF_finalPerfAssmnt

# Final Exam Python Project

## Student ID

corger5719

## Project Description

This project was created for the final performance assessment in Python. The program uses functions, loops, file handling, Excel automation, and data visualization. The program reads from an existing CSV file, appends new income data, creates an Excel pie chart, and displays a vertical bar graph using matplotlib.

## Program Requirements

This program completes the following tasks:

1. Creates a function called `askUser()`.
2. Uses a loop to ask the user for five numbers.
3. Accumulates the total of the five numbers.
4. Displays the total to the user.
5. Creates a function called `askIncome()`.
6. Uses a loop to ask for the names and annual incomes of five people.
7. Appends the new entries to an existing file called `final.csv`.
8. Creates a function called `excelPie()`.
9. Uses Excel automation to create a pie chart from the income data.
10. Saves the Excel file as `final.xlsx`.
11. Creates a function called `verticalBar()`.
12. Uses matplotlib to create a vertical bar graph from the same income data.


## Python Libraries Used

The program uses the following Python libraries:

```python
import os
import csv
import pandas as pd
import matplotlib.pyplot as plt
import openpyxl
from datetime import datetime
from openpyxl import Workbook
from openpyxl.chart import PieChart, Reference
```

## Functions Included

### askUser()

The `askUser()` function asks the user to enter five numbers. A loop is used to collect each number, add it to a running total, and display the final total.

### askIncome()

The `askIncome()` function asks the user to enter the names and annual incomes of five people. The data is appended to the existing `final.csv` file. A new line character is added before each entry so the new data is written on separate lines.

### excelPie()

The `excelPie()` function reads the data from `final.csv`, writes the data into an Excel workbook, and creates a pie chart. The numerical income values are converted to integers so the chart will display correctly. The Excel file is saved as:

```text
C:\FinalExam\final.xlsx
```

The pie chart title includes the student ID and the current date.

### verticalBar()

The `verticalBar()` function reads the data from `final.csv` and creates a vertical bar graph using matplotlib. The graph title includes the student ID and the current date.

## Output Produced

When the program runs successfully, it produces the following output:

* IDLE output showing the program prompts and total
* Updated `final.csv` file with five new entries added
* Excel file named `final.xlsx` with a pie chart
* Vertical bar graph created with matplotlib


