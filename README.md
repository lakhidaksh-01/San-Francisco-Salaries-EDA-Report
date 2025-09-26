# Employee Salaries Dataset Analysis

## Project Overview
This project involves a comprehensive Exploratory Data Analysis (EDA) of the San Francisco Employee Salaries dataset. The analysis is performed using Python and includes data cleaning, statistical summaries, and visualization to uncover insights about employee compensation, job titles, and pay trends over time.

## Dataset
The dataset (**Salaries.csv**) contains 148,654 records with 13 columns, including:

- Employee details (ID, Name, Job Title)
- Pay information (Base Pay, Overtime Pay, Other Pay, Benefits, Total Pay, Total Pay Benefits)
- Year and agency information

## Key Features
- **Data Cleaning**: Handling missing values, correcting data types, and removing irrelevant columns.
- **Statistical Analysis**: Summary statistics, unique job titles, highest pay, and common roles.
- **Visualizations**: Distribution of Base Pay, top-paying jobs, and pay trends over years.

## Questions Answered
- Top and last 10 rows of the dataset.
- Dataset shape and information.
- Handling missing values and dropping unnecessary columns.
- Employee name frequency and unique job titles.
- Pay statistics (min, max, average Base Pay).
- Filtering data (e.g., Fire Department employees, specific individuals like ALBERT PARDINI).
- Trend analysis by year and job title.
- **Visualizations:**
  - Base Pay distribution (histogram with KDE).
  - Top 10 job titles by average Base Pay (bar plot).
  - Total Pay trends over years (line plot).

## Tools Used
Python Libraries:
- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib` and `seaborn` for visualizations.
- `Jupyter Notebook` for interactive analysis.

## How to Use
1. Clone the repository.
2. Ensure the dataset `Salaries.csv` is in the working directory.
3. Run the Jupyter notebook (`notebookbe911e9b3b.ipynb`) to reproduce the analysis.
4. Modify code as needed to explore additional questions.

## Results
- Identified the highest-paid employees and most common job titles.
- Revealed pay trends and distributions across different roles and years.
- Provided insights into compensation structures within the San Francisco public sector.

## Future Enhancements
- Incorporate more advanced visualizations (e.g., interactive dashboards).
- Perform predictive modeling (e.g., salary prediction based on job title and year).
- Expand analysis to include benefits and overtime pay trends.

## Author
Developed as part of a data analysis project using real-world salary data.
