# School District Analysis

## Overview

### Purpose
Making an analysis on student data from a csv using jupyter notebook.

### Background
The csv student data has had some changes recently(ie. the new "school budget" column). Maria is asking for a reworked analysis of the newly changed dataset. 

## Expectations
1. Load the data into a detaframe
2. Clean up the dataframe
3. Summarize key data
4. Dive deeper into the data and analyze subsets
5. Compare the data by using grouping and other functions
6. Make a written analysis(this readme)

## Results
Complete results are available in the jupiter notebook link below.

[jupyter notebook](Student_Data_Challenge_Starter_Code.ipynb)

## Conclusion
In the beginning of this notebook it can be noted that there were quite a few null values for math and reading scores. There was also a lot of duplicate data. In the process of removing these duplicates and null values the descriptors that can be viewed by .describe() can be affected, therefore not providing a realistic view of the data.

Charter schools though having lower school budgets, had an higher average score for both reading and math. While the average scores do give a good look at the data, the viewer should make sure to take the school size into account as it is another variable that has an affect on the average scores.
