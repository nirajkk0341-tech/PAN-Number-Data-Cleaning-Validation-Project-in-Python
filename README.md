# PAN-Number-Data-Cleaning-Validation-Project-in-Python
In this project focuses on cleaning and validating Indian PAN (Permanent Account Number) data using Python. It leverages regular expressions and custom logic to identify valid PAN numbers based on format, repetition patterns, and sequential character rules. The script can be applied to real-world datasets (e.g., CSV files) containing PAN numbers to automate the validation process efficiently.

🛠 Key Features:

✅ Regex-based validation for standard PAN format: ABCDE1234F

❌ Rejects PANs with:

Incorrect length or format

Repeated adjacent characters

Sequential patterns (e.g., ABC, 123)

📄 Supports bulk validation using pandas DataFrames

📊 Marks each PAN as "Valid" or "Invalid" in a new column

📂 Files Included:
pan_validator.py – Core validation script

pan_data.csv – (Sample CSV containing PAN numbers)

requirements.txt – Python libraries used

README.md – Project overview and instructions
