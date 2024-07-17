# Bike-purchase-Analysis
![](motor-bike-picture.jpg)![](motor-bike-picture.jpg)![](motor-bike-picture.jpg)
## Introduction/Overview
The "Analysis on Bike Purchase" project aims to explore and understand the various demographic and socioeconomic factors that influence individuals' decisions to purchase bikes. By analyzing a diverse set of attributes, including income, marital status, gender, education, occupation, home ownership, car ownership, commute distance, region, and age, we seek to uncover patterns and trends that differentiate bike buyers from non-buyers.
The insights gained from this analysis will be invaluable for businesses, marketers, and policymakers, enabling them to tailor their strategies to effectively target potential bike buyers. Additionally, this project will provide a comprehensive understanding of the key drivers behind bike purchases, facilitating more informed decision-making and strategy development in the bike retail industry.
# Data Source
The data used for the analysis of bike sales was collected through a survey using a google form, the survey gathered responses from diverse group of participate, providing detailed information of various demographic and socioeconomic factors.
# Tools:
By combining Excel for robust data cleaning and transformation with Power BI for sophisticated analysis and visualization, your project will benefit from a comprehensive approach to understanding bike purchase patterns. This workflow ensures that you can extract meaningful insights and communicate them clearly through engaging visualizations to stakeholders
1.	Excel for Data Cleaning and Transformation:
o	Data Cleaning: Excel will be used to clean the raw data by removing duplicates, correcting errors, and ensuring consistency across the dataset. Tools. like filters, sorting, and conditional formatting will aid in identifying and rectifying issues.
o	Data Transformation: Excel's capabilities, such as pivot tables, functions like IF statements, and data validation, will facilitate transforming the data into a structured format suitable for analysis. This step involves aggregating, summarizing, and organizing the data to prepare it for further analysis in Power BI.
2.	Power BI for Analysis and Visualization:
o	Data Analysis: Power BI will handle the deeper analysis tasks. This includes creating different data tables, performing calculations using DAX (Data Analysis Expressions), and deriving insightful metrics such as average purchase age, regional buying trends, and correlation between income and purchase likelihood.
o	Visualization: Power BI's strength lies in its ability to create interactive and visually compelling dashboards and reports. You'll use it to generate various charts (like bar charts, line graphs), maps, and slicers that allow stakeholders to explore the data dynamically. This facilitates presenting key findings and trends effectively.
# Data Cleaning and Transformation 
Steps Taken:
1.	Data Cleaning:
o	Marital Status and Gender: Standardized capitalization for consistency (e.g., changed "S" to "Single", ”M” to” Married”, “M” to “Male”, “F” to “Female”).
o	Age: Ensured all age values were correctly formatted and within reasonable ranges.
o	Checked for Errors and Duplicates: Identified and removed duplicate entries to maintain data integrity.
2.	Data Transformation:
o	Age Range Calculation: Calculated age ranges (“children” less that 31 yrs, "youth" for ages between 31-50, "adult" for ages 50 and above) to categorize individuals based on age demographics by using IF function as below =IF(L2>50,"adult",IF(L2>=31,"youth",IF(L2<31,"childre"))).
o	Derived Columns: Created new columns such as "age range" to facilitate easier analysis and categorization of age groups.
3.	Verification and Quality Check:
o	Validation: Ensured all transformations and calculations were accurately applied to the entire dataset.
o	Review: Cross-checked transformed data against original sources to validate accuracy and consistency.
![](

