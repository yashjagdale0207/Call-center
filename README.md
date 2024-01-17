# Data Cleaning Report: Customer Call List

1. **Duplicate Removal:**
   - Identified and removed duplicate records in the customer call list for enhanced data accuracy.

2. **Column Elimination:**
   - Discarded unnecessary columns, such as "Not_Useful_Column," streamlining the dataset for better clarity.

3. **Name Standardization:**
   - Standardized last names by removing leading and trailing characters, ensuring consistency in data presentation.

4. **Phone Number Formatting:**
   - Cleaned and formatted phone numbers, removing non-alphanumeric characters and applying a consistent structure (###-###-####).

5. **Categorical Data Transformation:**
   - Transformed categorical columns ('Paying Customer' and 'Do_Not_Contact') for uniformity by replacing 'Yes' with 'Y' and 'No' with 'N.'

6. **Address Details Extraction:**
   - Extracted street address, state, and zip code from the 'Address' column for better segmentation.

7. **Null Value Handling:**
   - Filled null values in the 'Do_Not_Contact' column with an empty string to maintain data completeness.

8. **Data Integrity Assurance:**
   - Ensured data integrity by dropping rows with missing phone numbers and resetting the index for a cleaner dataset.

The cleaned and standardized dataset is now prepared for further analysis and utilization in customer engagement activities.
