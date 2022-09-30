# School_District_Analysis

## Overview
  Maria was given a new file of student records in the district, by the school board. The board had requested an analysis be done on the file. 
  Maria has requested a grade-level analysis on the schools. Also, a summary statistics to be generated and a closer look at several subsets of data. 
  After that she would like to discover if the test scores differ among grades or among schools. 

## Resources
  - Data source: new_full_student_data.csv
  - Anaconda 4.14.0, Python 3.7.13, Jupyter Notebook

## Deliverable 1: Collect the Data
  To collect the data that you’ll need, complete the following steps:
  
  1. Using the Pandas read_csv function and the os module, import the data from the new_full_student_data.csv file, and create a DataFrame called student_df.
  2. Use the head function to confirm that Pandas properly imported the data.
  
  ![D1](https://user-images.githubusercontent.com/99384585/193192166-04b45fe3-5d73-437a-b113-2a2a87c7553e.png)


## Deliverable 2: Prepare the Data
  To prepare and clean your data for analysis, complete the following steps:
  
  1. Check for and remove all rows with NaN, or missing, values in the student DataFrame.
  2. Check for and remove all duplicate rows in the student DataFrame.
  3. Use the str.replace function to remove the "th" from the grade levels in the grade column.
  4. Check data types using the dtypes property.
  5. Remove the "th" suffix from every value in the grade column using str and replace.
  6. Change the grade colum to the int type and verify column types.
  7. Use the head (and/or the tail) function to preview the DataFrame.

![D2a](https://user-images.githubusercontent.com/99384585/193192450-537d4839-75bf-4de6-8597-7b18591603ac.png)

![D2b](https://user-images.githubusercontent.com/99384585/193192464-9da89b7d-7d98-43f6-b851-eeb1925a4aef.png)


## Deliverable 3: Summarize the Data

  Describe the data using summary statistics on the data as a whole and on individual columns.

  1. Generate the summary statistics for each DataFrame by using the describe function.
  2. Display the mean math score using the mean function.
  3. Store the minimum reading score as min_reading_score.
  
  ![D3](https://user-images.githubusercontent.com/99384585/193192698-dd5da82b-faf3-44a0-a5d7-2c1b7f612b9f.png)


## Deliverable 4: Drill Down into the Data
  
  Drill down to specific rows, columns, and subsets of the data.
  To drill down into the data, complete the following steps:

   1. Use loc to display the grade column.
   2. Use iloc to display the first 3 rows and columns 3, 4, and 5.
   3.Show the rows for grade nine using loc.
   4.Store the row with the minimum overall reading score as min_reading_row using loc and the min_reading_score found in Deliverable 3.
   5.Find the reading scores for the school and grade from the output of step three using loc with multiple conditional statements.
   6.Using conditional statements and loc or iloc, find the mean reading score for all students in grades 11 and 12 combined.  
 
  ![D4a](https://user-images.githubusercontent.com/99384585/193193314-ce34b4de-c7f2-444a-8066-e4b01f24354f.png)
  
  ![D4b](https://user-images.githubusercontent.com/99384585/193193316-fc651094-b554-47ba-97d3-5679fb8f1d26.png)


## Deliverable 5: Make Comparisons Between District and Charter Schools
  Compare district vs charter schools for budget, size, and scores.

  Make comparisons within your data by completing the following steps:

  1.Using the groupby and mean functions, look at the average reading and math scores per school type.
  2.Using the groupby and count functions, find the total number of students at each school.
  3.Using the groupby and mean functions, find the average budget per grade for each school type.
  
  ![D5a](https://user-images.githubusercontent.com/99384585/193193381-48ef677a-785f-4471-b16b-a1b1a0511897.png)
  
  ![D5b](https://user-images.githubusercontent.com/99384585/193193383-12c2f2c9-0737-4a56-bef2-a55680b91145.png)
  
  ![D5c](https://user-images.githubusercontent.com/99384585/193193385-6575cfc3-cfb8-4155-9b53-63f92932d9f8.png)

  
  
  
