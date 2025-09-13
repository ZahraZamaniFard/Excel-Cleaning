# Excel Data Cleaning Project
This project demonstrates various data cleaning and transformation techniques in Excel.
The dataset is stored in the Data sheet, and I created 10 additional sheets, each dedicated to a specific task.
Tasks and Methods
* Sheet 1: Combined first and last names into a single column using the TEXTJOIN function.
* Sheet 2: Extracted the area code (first three digits) from phone numbers using the MID function.
* Sheet 3: Extracted the 7-digit phone number without the area code using a combination of MID and SUBSTITUTE.
* Sheet 4: Cleaned phone numbers by removing parentheses and spaces with the SUBSTITUTE function.
* Sheet 5: Extracted only the street name (excluding the house number) using RIGHT, LEN, and FIND.
* Sheet 6: Combined the street name with the Zipcode in the format *Street Name – Zipcode* using RIGHT, TEXTJOIN, LEN, and FIND.
* Sheet 7: Created a unique identifier by combining initials and area codes with RIGHT and MID.
* Sheet 8: Standardized addresses by replacing “St” with “Street” using the SUBSTITUTE function.
* Sheet 9: Extracted the house number from street addresses using Power Query.
* Sheet 10: Extracted Day, Month, and Year from dates using the DAY, MONTH, and YEAR functions.
Key Learnings
Through this project, I practiced:
* Excel text functions (TEXTJOIN, MID, RIGHT, LEN, FIND, SUBSTITUTE)
* Date functions (DAY, MONTH, YEAR)
* Power Query for advanced data transformation
* Building a step-by-step workflow for cleaning and structuring data
