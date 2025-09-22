Marketing Campaign Dataset Cleaning Task

Introduction:
This project is about cleaning a messy marketing campaign dataset I downloaded from Kaggle. The original file wasn’t even in a proper table format—it had inconsistent values, missing data, and duplicate entries. My goal was to clean it up and make it ready for analysis.

Tools Used:
I used Microsoft Excel for the entire cleaning process. Since the dataset had fewer than 10,000 rows, Excel was the most efficient choice. It allowed me to manually inspect, clean, and validate the data without needing Python or Pandas.

Cleaning Process:
1. Imported the raw CSV using Excel’s “Get Data” option (Text/CSV format).
2. Transformed the messy text into a proper table using Power Query.
3. Removed duplicate rows by validating the ID column.
4. Standardized column headers to make them clean and readable.
5. Fixed inconsistent values in categorical columns like Marital_Status.
6. Checked for missing data and handled it appropriately.
7. Validated data types—ensured numbers, dates, and text were correctly formatted.

Validation Strategy:
I used the ID column to validate the dataset because it uniquely identifies each record. I avoided using columns like Marital_Status or Year_Birth because they contain repeated or ambiguous values that could lead to incorrect validation.

Why Excel?
Even though I’m learning Python and Pandas, I chose Excel for this task because:
- The dataset was small enough to handle manually.
- Excel gave me faster control over cleaning steps.
- I’ve previously cleaned larger datasets (13.5k rows) using Excel, so I trusted the process.

Outcome:
The final cleaned dataset is now structured, validated, and ready for analysis or visualization. I’ve included both the raw and cleaned files in this folder, along with the original task PDF.