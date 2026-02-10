# CUSTOMER_CONVERSION-ADVERTISING-IMPACT-ANALYSIS



Q1. Load the dataset bank-additional-full.csv into a pandas DataFrame.
Create a new column named "conversion" based on the y column, where:
•	"yes" → 1
•	"no" → 0

Q2. Calculate the overall conversion rate for different customer segments based on the Education column.

Q3. Plot a pie chart for each education category to visualize conversion distribution.

Q4. Break down the customer base into multiple segments according to the Job category.

Q5. Using a suitable visualization (bar chart or pie chart), display conversion distribution for each job segment.

Q6. Based on the analysis, answer the following:
•	Which education groups show the highest conversion?
•	Which job roles have stronger conversion tendencies?
•	Are there any noticeable patterns relevant for marketing decision-making?

Q7. Load the dataset Advertising.csv into a pandas DataFrame and Display the first 5 rows to understand its structure.

Q8. Using descriptive statistics and visualizations, explore how the advertising channels (TV, Radio, Newspaper) relate to Sales.

Q9. Create scatter plots for:
•	TV vs Sales
•	Radio vs Sales
•	Newspaper vs Sales



Customer Conversion Analysis Using Bank Marketing Dataset

Q1. Load and Inspect the Dataset
Load the dataset bank-additional-full.csv using pandas.
Perform the following:
•	Display the shape of the dataset
•	Show the first 5 rows
•	Identify the target column

Q2. Create a Conversion Column
Create a new column "conversion" from the existing y column such that:
•	"yes" → 1
•	"no" → 0

Q3. Calculate Overall Conversion Rate
Compute the overall conversion percentage for the entire dataset.(Hint: Use mean or aggregate functions.)

Q4. Conversion Rates by Marital Status
Group the dataset by marital status and calculate:
•	Total conversions
•	Total customers
•	Conversion rate (%)
Present the results in a DataFrame.
Then, create a bar chart showing conversion rate by marital category.

Q5. Conversion Rates by Number of Contacts
Group customers based on campaign (number of contacts during campaign).
Calculate the conversion percentage for each contact level. Plot the top 10 contact counts using a bar chart.

Q6. Conversion Rates by Age
Using the age column:
•	Calculate total customers per age
•	Calculate total conversions per age
•	Derive conversion rate (%) for each age
Represent the conversion rate using a bar chart or line chart.

Q7. Interpretation of Findings
Write a brief summary covering:
•	Which marital groups convert better?
•	How does number of contacts affect conversion?
•	What patterns are observed across age groups?
•	Any insights useful for campaign optimization?
