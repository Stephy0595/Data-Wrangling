# Data-Wrangling

This repository contains various Excel data wrangling techniques to help clean and prepare your datasets for analysis. 

The focus is on ensuring that the data is consistent, accurate, and in the correct format, which is crucial for any data-driven decision-making process.

1. Data Type Conversion
   
When working with numerical data in Excel, it's essential to ensure that the data types are correctly recognized by the system.

Incorrect data types can lead to errors in calculations, charts, and analysis.

Task:

Check the data types of the 'Price' and 'Quantity' columns to ensure they are formatted as numbers. 

If needed, convert them to the appropriate data type.

2. Transforming Text Data
   
Text data can often be messy. Columns like 'Product Name' and 'Brand Name' might have inconsistencies such as leading or trailing spaces, mixed case, or misspellings. 

It’s important to standardize text entries to avoid errors during filtering or aggregating data.

Task:

Examine the 'Product Name' and 'Brand Name' columns for any inconsistencies or irregularities, such as extra spaces, mixed capitalization, or spelling mistakes.

Clean the text data to ensure consistency and accuracy.

How to Fix:

Use the TRIM() function to remove leading or trailing spaces.

Use UPPER(), LOWER(), or PROPER() to standardize the case of text.


