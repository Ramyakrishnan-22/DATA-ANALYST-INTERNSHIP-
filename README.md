# DATA-ANALYST-INTERNSHIP-Task1
# Excel Data Cleaning – Internship Task

## Objective
To clean and prepare a messy dataset using Excel by applying data cleaning techniques used by data analysts.

## Dataset Description
The dataset contains movie and TV show information with:
  Missing values
  Duplicate records
  Inconsistent text formats
  Incorrect date formats

## Data Cleaning Process

### 1. Dataset Loading
 Downloaded the dataset in CSV format
 Opened in Excel ensuring column headers are correct

### 2. Freeze Panes & Filters
 Applied Freeze Top Row
 Enabled filters on all columns for easy analysis

### 3. Missing Value Handling
 Identified blank cells using filters
 Filled or left blanks based on column importance

### 4. Duplicate Removal
 Created a backup of raw data
 Removed duplicate rows using ID and Title columns

### 5. Text Standardization
- Used TRIM to remove extra spaces
- Used PROPER for consistent text case
- Used UPPER for rating values

### 6. Format Correction
- Converted date column to YYYY-MM-DD format
- Ensured numeric columns contain only numbers

### 7. Data Quality Notes
- Added a column named Data_Quality_Notes
- Used Excel formulas to detect:
  - Missing values
  - Rating inconsistencies
  - Invalid date formats
  - Country naming issues

### 8. Final Export
- Saved cleaned dataset as Excel and CSV files

---

## Files in Repository
- Raw_Data.xlsx
- Cleaned_dataset.xlsx
- cleaned_dataset.csv

---

## Tools Used
- Microsoft Excel



