# PROJECT: EXPENSE TRACKER
# DESCRIPTION:
Expense Tracker is a command-line interface (CLI) application that helps users track their 
expenses. It allows users to manage their financial transactions, view expense details, and calculate 
total expenses within a specified date range. The application utilizes data structures like lists and 
dictionaries to store and manipulate expense data.
# FEATURES:
1. Add an Expense: Users can add a new expense by entering details such as date, category, 
description, and amount. The input must be validated, for example, negative amount can not be 
added, and the category must be defined previously, if no category is found then the new category need 
to be added to the category list.
2. View Expense List: Users can view their expense list, which displays all expenses with their 
corresponding details, including date, category, description, and amount.
3. Filter Expenses: Users can filter expenses based on specific criteria such as date range, category, 
or a combination of both. The filtered list will display expenses that match the selected criteria.
4. Calculate Total Expenses: Users can calculate the total expenses within a specified date range 
or for the entire expense list.
5. Delete an Expense: Users can delete a specific expense by providing its unique identifier.
6. Export Expense Data: Users can export the expense data to a CSV file for further analysis or 
record-keeping.
7. Add category: New category can be added from here.

# USER INTERFACE (CLI):
The following is an example of how the CLI of the Expense Tracker application could look:
```
Expense Tracker
---------------
1. Add an Expense
2. View the Expense List
3. Filter Expenses
4. Calculate Total Expenses
5. Delete an Expense
6. Export Expense Data
7. Add categories
8. Exit
```

```
Enter your choice (1-8): 1
Enter Expense Details:
--------------------------------
Date (YYYY-MM-DD): 2023-06-15 
Category: Groceries 
Description: Grocery shopping 
Amount: 50.00
Expense added successfully!
```

```
Enter your choice (1-8): 2
Expense List:
-------------
ID   Date        Category   Description       Amount
-------------------------------------------------------
1.   2023-06-15  Groceries  Grocery shopping  50.00
```
```
Enter your choice (1-8): 3
Filter Expenses:
1. Filter by Date Range
2. Filter by Category
3. Filter by Date Range and Category
Enter your choice (1-3): 1
Enter start date (YYYY-MM-DD): 2023-06-01
Enter end date (YYYY-MM-DD): 2023-06-30
Filtered Expense List:
----------------------
ID   Date   Category   Description   Amount
-------------------------------------------------------
1 2023-06-15   Groceries   Grocery   shopping   50.00
```

```
Enter your choice (1-8): 4
Calculate Total Expenses:
1. Calculate the total for all expenses
2. Calculate the total within a date range
```

```
Enter your choice (1-2): 1
Total Expenses: 50.00
```

```
Enter your choice (1-7): 5
Enter the expense ID to delete: 1
Expense deleted successfully!
```

```
Enter your choice (1-8): 6
Enter the file name to export (e.g., expenses.csv): expenses.csv
Expense data was exported to expenses.csv successfully!
```

```
Enter your choice (1-8): 8
Exiting.
```
