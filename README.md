# Data Cleaning Summary
This dataset was cleaned to ensure consistency and accuracy in café sales records. The following steps were performed:

Loaded CSV file using pandas.

Stripped extra spaces from column names for consistency.

Converted non-numeric Total Spent values (like "ERROR") to proper numbers and removed rows with invalid entries.

Handled missing or invalid entries in categorical columns like Payment Method and Location by replacing "UNKNOWN" with the most frequent valid value.

Standardized the Transaction Date column to proper datetime format.

Verified the final structure and datatypes to ensure the dataset is ready for analysis.
