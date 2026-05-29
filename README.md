# Task 1: Data Cleaning and Preprocessing

## Dataset
Netflix Movies and TV Shows Dataset

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Data Cleaning Steps
1. Loaded dataset using Pandas
2. Checked dataset structure using df.info()
3. Identified missing values using df.isnull().sum()
4. Filled missing values:
   - director → Unknown
   - cast → Not Available
   - country → Unknown
   - rating → Not Rated
   - duration → Unknown
   - date_added → Most frequent date
5. Checked duplicate records
6. Standardized column names
7. Converted date_added to datetime format
8. Verified data types
9. Saved cleaned dataset

## Results
- Missing Values: 0
- Duplicate Records: 0

## Output
cleaned_netflix.csv