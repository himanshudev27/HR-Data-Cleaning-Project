# HR Data Collection, Cleaning and Validation

## Project Overview
This project demonstrates the process of collecting, cleaning, validating, and preparing HR employee data for further analysis.

A simulated HR dataset containing 600 employee records was created with realistic data-quality issues, including missing values, duplicate records, inconsistent formats, incorrect data types, and invalid entries.

## Objectives
- Import and inspect HR datasets.
- Identify and handle missing values.
- Remove duplicate records.
- Correct data types.
- Standardize categorical variables.
- Validate employee records.
- Export a cleaned dataset.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Microsoft Excel

## Dataset Features
- Employee ID
- Employee Name
- Age and Gender
- Department and Job Role
- Location
- Date of Joining
- Annual Salary
- Years of Experience
- Performance Rating
- Attendance Percentage
- Leave Days
- Employment Status

## Data Cleaning Process
1. Dataset import and inspection.
2. Missing value identification.
3. Duplicate removal.
4. Data type conversion.
5. Invalid value detection and correction.
6. Standardization of categorical values.
7. Missing value imputation.
8. Data validation.
9. Export of cleaned dataset.

## Project Files
| File | Description |
|---|---|
| HR_Raw_Dataset.csv | Original simulated dataset |
| HR_Cleaned_Dataset.csv | Cleaned dataset |
| HR_Data_Cleaning.ipynb | Python cleaning notebook |
| HR_Data_Cleaning_Report.pdf | Project methodology and findings |
| HR_Validation_Summary.csv | Statistical summary |

## Key Learning Outcomes
- Practical data preprocessing using Pandas.
- Handling real-world data-quality challenges.
- Data validation and consistency checks.
- Reproducible data cleaning workflows.

## Dataset Disclaimer
This project uses simulated employee data for educational purposes. It does not contain actual employee records.

## Author
Himanshu Raj


## Week 1 – Python for Machine Learning & Data Preprocessing

An additional notebook extends this project with machine-learning preprocessing using the existing simulated HR dataset.

### Additional workflow
- Data inspection using Pandas and NumPy
- Duplicate removal, type conversion and missing-value imputation
- Feature selection and target separation
- One-Hot Encoding of categorical features
- StandardScaler normalization of numerical features
- Exploratory Data Analysis with Matplotlib and Seaborn
- Train/test splitting and preprocessing pipelines to avoid data leakage
- Export of cleaned, training and testing datasets

### New files
| File | Description |
|---|---|
| `Week1_HR_Data_Preprocessing.ipynb` | Week 1 preprocessing notebook |
| `requirements.txt` | Python dependencies |
| `outputs/` | Generated cleaned and preprocessed CSV files (created when notebook runs) |

Run `pip install -r requirements.txt`, then open the Week 1 notebook in Jupyter. Keep `HR_Raw_Dataset.csv` in the repository root.

**Responsible-use note:** The dataset is simulated. Employment status is used only as an educational example target and must not be used for real employment decisions.
