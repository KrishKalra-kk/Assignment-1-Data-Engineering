# Data Cleaning Assignment

## About This Project

This is my assignment for the data engineering internship. I worked with a shopping dataset from Myntra and cleaned it using Python and Pandas.

## What I Did

### 1. Loaded and Explored the Data
Started by loading the CSV file and checking what was in it. The dataset had 1001 rows and 24 columns. I used `head()`, `tail()`, and `info()` to see the structure.

### 2. Fixed Missing Values
Found out that some columns had a lot of empty cells. I removed those columns that were mostly empty and filled in the remaining gaps with 'Unknown' so the data wouldn't break.

### 3. Cleaned Up Duplicates
Checked for duplicate rows and removed them. This made the dataset smaller but cleaner.

### 4. Kept Only Useful Columns
The dataset had too many columns. I selected only the ones I needed: product title, prices, ratings, number of ratings, and category.

### 5. Created a New Column
Since the dataset didn't have quantity, I created a 'savings' column that shows how much money you save on each product (original price - final price).

### 6. Saved the Clean Data
Exported the cleaned dataset as a new CSV file that can be used for further analysis.

## Files Here

- `assignment_1.ipynb` - The notebook with all my code and results
- `Combined_dataset_cleaned.csv` - The cleaned data
- `README.md` - This file

## Results

The notebook shows:
- How many rows and columns before and after cleaning
- What missing values looked like
- How many duplicates I removed
- Basic stats about prices and ratings

## Tools Used

- Python
- Pandas library
- Jupyter Notebook

## How to Use

Open the notebook and run the cells one by one to see how the cleaning process works.
