# Error-Handlers

Error Handlers - IFERROR Function. 

The IFERROR function is used for anticipating and checking errors, with a conditional value to replace the error if it exists. 

Example: I have two spreadsheet files; Tokyo Airbnb listing and Calender workbooks. I wanted to extract the maximum night from the calendar workbook into the Tokyo Airbnb listing using Vlookup. However, the calendar workbook had over a million rows and Microsoft Excel couldn't open it all, instead, it returned a #N/A error for some of the records. So I used the IFERROR function to replace the error with 0. 

