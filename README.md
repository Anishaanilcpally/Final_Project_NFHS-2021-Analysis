# Final_Project_NFHS-2021-Analysis
Project Documentation
Project Title: The Impact of Education and Infrastructure on Maternal and Child Health – NFHS 2021 Analysis
1. Project Overview
This project serves as a technical demonstration of an end-to-end data analytics pipeline using the National Family Health Survey (2019-21) dataset. The primary focus is on transforming raw survey data into actionable insights through rigorous data cleaning, feature renaming, and statistical visualization.
2. Tools Used
Pandas – Data cleaning, feature renaming, and structural manipulation.
Matplotlib – Foundation for layout design and basic plotting.
Seaborn – Advanced statistical visualizations and correlation analysis.
NumPy – Numerical operations and data handling.
3. Dataset
Source: National Family Health Survey (2019-21).
Description: The dataset contains district-level survey data across India with key columns including:
State and District names
Literacy and Schooling percentages
Maternal Health (Anemia, Vaccinations)
Household Amenities (Electricity, Clean Fuel, Sanitation)
4. Steps Followed
1.
Data Ingestion: Imported the raw CSV dataset using Pandas.
2.
Data Cleaning & Refactoring:
Renamed complex, long-form column headers into short, technical identifiers for better coding efficiency.
Checked data types and confirmed the scale of the dataset (704 records).
3.
Exploratory Data Analysis (EDA):
Performed statistical summaries (.describe()) to understand the distribution of health metrics.
4.
Data Visualization:
Created visual distributions to compare state-wise health performance.
Used Seaborn for pattern analysis between education and health outcomes.
5.
Result Interpretation: Extracted technical insights based on data correlations.
5. Key Insights
Structural Impact: Access to household electricity and clean fuel correlates directly with improved sanitation scores.
The Schooling Gap: Data identifies that while literacy is high, 10+ years of schooling is the primary driver for better health indicators.
National Trends: Anemia remains a consistent challenge across various demographics, suggesting it is a universal nutritional issue rather than a regional one.
6. Visualizations
Distribution plots for maternal health indicators.
Comparative bar charts for state-wise infrastructure levels.
Correlation analysis between education and vaccination rates.
7. Files Included
National_Family_Health_Survey_2021.csv – Raw dataset.
Final_Project.ipynb – Jupyter Notebook containing Python code and analysis.
README.md – Project description for GitHub.
8. How to Use
1.
Open Final_Project.ipynb in Jupyter Notebook or Google Colab.
2.
Ensure the CSV dataset is in the same directory.
3.
Run the cells sequentially to observe the data cleaning process and generated plots.
9. Conclusion
This project demonstrates the effective use of Python for real-world social data analysis. It showcases the ability to take raw, unorganized survey data and transform it into a clean, visualized format to support data-driven conclusions.
