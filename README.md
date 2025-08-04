# Indian-Employee-Data-Cleaning-with-Numpy-Pandas

This project demonstrates how to clean and preprocess a real-world employee dataset using NumPy and Pandas in Google Colab. It focuses on handling missing values, converting data types, formatting, and removing unnecessary columns for a cleaner dataset.

# This Project Covers:
- Loading dataset via Google Colab
- Handling missing values in both numerical and categorical columns
- Replacing infinite values with NaN and filling them appropriately
- Converting float values (like Age and Salary) into clean integers
- Removing irrelevant or unnecessary columns
- Final dataset ready for analysis or modeling.

# Libraries Used:
- NumPy
- Pandas
- Google Colab's `files.upload()` for importing dataset.

# Key Highlights:
- Treated missing `Department` and `Position` with mode values
- Replaced `inf` and `-inf` with `NaN`, and filled with mean/median
- Converted float columns like `Age` and `Salary` into integers
- Applied upper and lower bounds to clean salary outliers
- Final cleanup by dropping irrelevant columns

# Output:
A clean and processed DataFrame ready for analysis or machine learning tasks.

---

Feel free to check out the notebook and share your feedback!
