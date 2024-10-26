### Student-Data-Analysis-Using-Lookup-Functions-in-Excel



## Project Overview

In this project, I analyzed a dataset containing student information, including names, marks, and attendance records. The objective was to demonstrate the use of various Excel lookup functions to retrieve specific data points efficiently. The following lookup functions were utilized:

- VLOOKUP and MATCH
  
- INDEX and MATCH
  
- XLOOKUP
  
- HLOOKUP

## Problem Statement

The main tasks were to extract the name, mark, and attendance for specific student IDs:

- Retrieve the data for student ID 001 using the VLOOKUP and MATCH functions.
  
- Retrieve the data for student ID 007 using the INDEX and MATCH functions.
  
- Retrieve the data for student ID 015 using the XLOOKUP function.
  
- Retrieve the data for student ID 015 using the HLOOKUP function.

## Formulas Used

The following formulas were employed to achieve the tasks:

- VLOOKUP and MATCH:

Formula:
=VLOOKUP(H3,A3:D19,MATCH(I2,A2:D2,0),FALSE)
This formula retrieves the name, mark, and attendance for student ID 001.

- INDEX and MATCH:

Formula:
=INDEX(B3:D19,MATCH(H9,A3:A19,0),MATCH(I2,B2:D2,0))
This formula retrieves the name, mark, and attendance for student ID 007.

- XLOOKUP:

Formula:
=XLOOKUP(H14,A3:A19,B3:D19,0)
This formula retrieves the name, mark, and attendance for student ID 015.

- HLOOKUP:

Formula:
=HLOOKUP(N14,C23:S26,2)
This formula retrieves the data for student ID 015 from a horizontal dataset.

## Conclusion

By employing these advanced lookup functions, I successfully extracted the desired student information from the dataset. This project not only enhanced my Excel skills but also showcased my ability to solve data-related problems using various methodologies. I have attached screenshots of the work for visual representation.

![Lookup Functions](https://github.com/user-attachments/assets/cc4bd3bd-8780-426c-884b-8d0b64b9e212)

This report highlights my proficiency in using Excel for data analysis and retrieval, an essential skill in data management and analysis roles.
