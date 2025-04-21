# ElevateLabs-Data-Analyst-Internship-Task-1
This task focuses on cleaning and preprocessing the Netflix Titles dataset using Excel Power Query . The goal is to transform the raw dataset into a clean, analysis-ready format by handling null values, removing duplicates, standardizing formats, and correcting data types.

# Tools used
Microsoft Excel (Power Query Editor)

# Objectives
Identify and handle missing values

Remove duplicate entries

Standardize text formats (e.g., country names, type)

Convert and format dates consistently (dd-mm-yyyy)

Rename and clean column headers

Validate and correct data types

# Dataset
Source: Netflix Titles Dataset - Kaggle

Dataset:[netflix_titles.csv](https://github.com/user-attachments/files/19832693/netflix_titles.csv)


# 📌 Tasks Performed
✅ Excel Power Query

# 1.Import the CSV dataset into Power Query
   
# 2.Renamed and Cleaned Column Headers
   Rename all columns to:
            All lowercase
            Underscores instead of spaces
Example: Show ID → show_id, Date Added → date_added

# 3.Handled Missing Values
    Remove rows where critical fields like title, date_added, or type are null.
    For non-critical fields (like director, cast)
    Replace nulls using Transform → Replace Values with "Not Provided".

# 4.Removed Duplicate Rows 

# 5.Standardized Text Columns
    Format Columns like type, rating, country, listed_in, etc.
    Trim: Removed extra spaces
    Clean: Removed hidden characters
    Capitalize Each Word: Captalized each word 

# 6.Converted Date Formats
     date_added column coverts the date format into dd-mm-yyyy format.

# 7.Fix Data Types
   Columns like:
    release_year → Whole Number
    date_added → Date
    title, country, director → Text

# Summary changes in dataset
- Removed 35 duplicate rows.
- Replaced null values in `country`,'Director','cast','listed_in' with "Not Provided".
- Standardized `country` values and trimmed whitespace.
- Converted `date_added` to date format DD-MM-YYYY.
- Renamed columns: "Show ID" → "show_id", etc.
- Set data types: `release_year` as Whole Number, `date_added` as date.

# Cleaned and Preprocessed Dataset

[Netflix Data Cleaned and Preprocessed Dataset.xlsx](https://github.com/user-attachments/files/19832690/Netflix.Data.Cleaned.and.Preprocessed.Dataset.xlsx)
