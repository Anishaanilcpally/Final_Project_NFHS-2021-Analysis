# Final_Project_NFHS-2021-Analysis
# Project Documentation

## Project Title: NFHS 2021 Data Analysis using Pandas, Matplotlib, and Seaborn

### 1. Project Overview
This project focuses on performing an end-to-end data analytics workflow on the National Family Health Survey (NFHS-5) dataset. The goal is to demonstrate technical proficiency in data cleaning, structural transformation, and statistical visualization.

### 2. Tools & Technical Skills
* **Pandas**: Data cleaning, feature renaming, and structural manipulation.
* **Matplotlib**: Foundation for layout design and basic plotting.
* **Seaborn**: Advanced statistical visualizations and correlation analysis.
* **NumPy**: Numerical operations and data handling.

### 3. Dataset
* **Source**: National Family Health Survey (2019-21)
* **Description**: The dataset contains district-level survey data across India. Key features include:
    * Literacy and Schooling percentages
    * Maternal Health (Anemia, Vaccinations)
    * Household Amenities (Electricity, Clean Fuel, Sanitation)

### 4. Steps Followed (Technical Workflow)
1. **Data Ingestion**: Imported the raw CSV dataset using Pandas.
2. **Data Cleaning & Refactoring**:
    * Renamed complex, long-form column headers into short, technical identifiers for better coding efficiency.
    * Verified data types and confirmed the scale of the dataset (704 records).
3. **Exploratory Data Analysis (EDA)**:
    * Performed statistical summaries (`.describe()`) to understand the distribution of health metrics.
4. **Data Visualization**:
    * Created visual distributions to compare state-wise health performance.
    * Used Seaborn for pattern analysis between education and health outcomes.

### 5. Key Insights
* **Infrastructure Sensitivity**: Access to household electricity and clean fuel correlates directly with improved sanitation scores.
* **The Schooling Gap**: Data identifies that while literacy is high, 10+ years of schooling is the primary driver for better health indicators.
* **National Trends**: Anemia remains a consistent challenge across various demographics.

### 6. Files Included
* `National_Family_Health_Survey_2021.csv` – Raw dataset.
* `Final_Project.ipynb` – Jupyter Notebook containing Python code.
* `README.md` – Project description.

### 7. How to Use
1. Open `Final_Project.ipynb` using Jupyter Notebook or Google Colab.
2. Ensure the CSV dataset is in the same directory.
3. Run the cells sequentially to observe the analysis.

### 8. Conclusion
This project demonstrates the ability to take raw survey data and transform it into a clean, visualized format to support data-driven conclusions using industry-standard Python libraries.
