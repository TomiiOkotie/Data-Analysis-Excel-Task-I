# Data-Analysis-Excel-Task-I

## Worksheet 1
For this task, I created an imaginary data set which was a table containing 20 rows of information with fields which included Employee ID, Employee Full Name, Department, Salary and Job type. I went ahead to clean the data and worked on the data type for each of the ranges. Then I went ahead to duplicate the dataset into 3 different sheets.

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/EmployeeDataset.png)

## Worksheet 2

In this worksheet, I show only employees who are freelancers and highlighted employees whose salaries are above $ 10,000. To achieve this, I used the sort and filter icon to filter out employees who are not freelancers, then I went ahead to use conditional formatting on the salary column and highlighted salaries greater than $ 10,000.

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/SortandFilter.png)

In this sheet, I had a list of employee names in one column and wanted to split these names into first names and last names. To do this, I added a new column right next to the one with employee names. Next, I selected the column containing the employee names. Then, I went to the "Data" tab in Excel. I used the "Text to Columns" feature from there. I specified that I wanted to split the text into spaces. I clicked "Finish" and agreed to let Excel replace the original data. As a result, the employee names got separated into the new columns, with first names in one and last names in the other. I didn't have any duplicate Data. 


![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/DelimtedDataset.png) 

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/spilltedf.png)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/Noduplicate.png)

## Worksheet 3

Fot this sheet, I first selected the employee name column and used conditional formatting to highlight names that started with "E" in yellow. Then, I sorted the salary column from highest to lowest and applied a green and red color scale to highlight the salary range.

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/ConditionalFormatting.png)


#   Excel Task 2

In this sheet, I had clean data with minimal issues. I adjusted column widths to fit content properly. I styled and centered the header row for clarity. I assigned appropriate data types like currency for money, date for dates, and text for text columns, leaving the rest as general data. This enhanced data organization and presentation. The first task was to determine the total revenue and to get that i used the sum function to sum up the entire sales coulunm with the formula =SUM(A2:A701)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/RevenueData.png)

I also went ahead to calculate the total profit by summing up the profit column using the sum funtion =SUM(L2:L701) 

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/Profit%20Data.png)

For the next task i had to determine the average revenue, i used the average function for the sales column, the fornalar used =AVERAGE(A2:A701)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/AverageRevenue.png)

The next task was to calculate the average of unit sold and i used average function on the unit sold column, the formula used was =AVERAGE(O2:O701)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/AverageUnitSold.png) 

For the next task, i had to find the total discount and to achieve this i used the sum function on the discount column and the formula deployed was =SUM(F2:F701)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/Average%20Unit%20Sold.png)

The next insight shows total number of sales, which simply means using the count functon to determine the number of sales , and i used =COUNT(A2:A701)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/CountData.png)

And for the sheet below, i had to determine the highest profit in the profit column and i simply used the max function, formula was =MAX(L2:L701)

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/HighestData.png) 

For the fianl insight, i created a column namee sales range and return 'high sales', if the sale value is above average, otherwise return 'Low Sales'.  To do this i used the if function and also use absolute referencing. Formula =IF(A2>$V$17,"High Sales", "Low Sales")

![](https://github.com/TomiiOkotie/Data-Analysis-Excel-Task-I/blob/main/lowsales.png)

