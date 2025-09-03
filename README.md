flix Data Cleaning (Excel)

📌 Task Overview

This project is part of my Data Analytics Internship. The goal was to clean and preprocess the Netflix Movies and TV Shows Dataset to make it ready for analysis.


---

🛠 Tools Used

Microsoft Excel



---

🔹 Steps Performed

1. Handled Missing Values
Replaced blank values in Country with "Unknown".
Kept blanks in Director and Cast since they occur frequently.
2. Removed Duplicates
Used Excel’s Remove Duplicates feature on Title + Type + Release Year.
3. Standardized Text
Fixed Type column values to ensure only Movie and TV Show exist.
Applied consistent capitalization where needed.
4. Date Cleaning
Attempted to convert Date Added into a consistent format.
Noted that Excel stored dates as text in some cases, so I kept the original format (Month Day, Year) for accuracy.
5. Renamed Columns
Cleaned headers for consistency (lowercase, underscores instead of spaces).
6. Checked Data Types
Ensured release_year is numeric.
Confirmed date_added is a valid date column.

---

📂 Deliverables

Netflix_Cleaned.xlsx → Cleaned dataset in Excel.
Netflix_Cleaned.csv → Exported cleaned dataset in CSV format.
README.md (this file) → Summary of steps performed.


---

✅ Outcome

The dataset is now:
Free of duplicates.
Missing values are handled.
Text values are standardized.
Columns are renamed and consistent.
Ready for further analysis or visualization.# netflix_data_cleaning
Task 1:Data Cleaning Using Excel
