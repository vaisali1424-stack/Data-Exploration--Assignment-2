🧹 Data Cleaning & Transformation with Excel

Turning messy data into meaningful, reliable information.

Welcome to this data-cleaning project! 🚀

This repository demonstrates a practical Excel data-cleaning workflow for transforming an inconsistent product dataset into a structured and analysis-ready dataset.

The project focuses on developing essential data-preparation skills that are useful in Data Analytics, Business Intelligence, and Data Science.

🎯 Project Objectives

The main objectives of this project are to:

🔍 Identify and handle missing values

✏️ Correct inconsistent text formats

🐛 Fix spelling mistakes and category typos

🗑️ Remove duplicate records

🔀 Split and merge columns

💰 Format prices as currency

📅 Standardize manufacturing dates

🎨 Apply conditional formatting

📊 Prepare clean data for future analysis

🛠️ Tools Used

Microsoft Excel

Find & Replace

Remove Duplicates

Text to Columns

Excel Functions

Conditional Formatting

Data Formatting

📂 Repository Structure
Data-Cleaning-Excel-Project/
│
├── 📁 data/
│   ├── raw_data.xlsx
│   └── cleaned_data.xlsx
│
├── 📁 screenshots/
│   ├── missing-values.png
│   ├── duplicate-removal.png
│   ├── data-cleaning.png
│   └── conditional-formatting.png
│
├── 📄 README.md
└── 📄 data-cleaning-report.pdf

🔧 Data Cleaning Process
1. Handling Missing Values

Missing values in the Price column were identified and reviewed.

Where reliable information was unavailable, missing prices were left blank rather than assigning an arbitrary value.

Missing categories were investigated using available product information. Products that could not be reliably classified were assigned an appropriate placeholder such as Unknown.

2. Correcting Inconsistent Data

The Product Name column was standardized by correcting:

Inconsistent capitalization

Extra spaces

Inconsistent naming formats

The Category column was checked for spelling mistakes and standardized using Excel's Find and Replace functionality.

3. Removing Duplicates

Duplicate records were identified using all columns.

Excel's:

Data → Remove Duplicates

feature was used to remove identical rows.

4. Splitting Product ID

The Product ID was separated into:

Manufacturing Date

Country Code

Unnecessary characters were removed during the transformation.

5. Creating Product Brand

The Brand Name and Product Name columns were combined into:

Product Brand

Example:

Samsung + Galaxy S24
        ↓
Samsung Galaxy S24

6. Formatting Price

The Price column was converted into a currency format to improve readability and consistency.

7. Formatting Manufacturing Date

Manufacturing dates were standardized to:

DD-MM-YYYY


Example:

20240315
    ↓
15-03-2024

8. Conditional Formatting

Conditional formatting was applied to the Price column using:

Data Bars

Color Scales

A custom conditional-formatting rule was also applied to the Category column to highlight:

Electronics

📈 Before & After
Before 🧹

The original dataset contained issues such as:

iphone 15
IPhone 15
IPHONE 15

Electornics
Electronics

Samsung   Galaxy S24

Duplicate product records
Missing prices
Missing categories

After ✨

The cleaned dataset provides:

Apple iPhone 15
Samsung Galaxy S24

Electronics
Electronics

Consistent spacing
Consistent formatting
No duplicate rows
Standardized dates
Formatted prices

💡 What I Learned

This project helped strengthen my understanding of:

Data quality

Data preprocessing

Excel data-cleaning techniques

Handling missing information

Removing duplicates

Data transformation

Data standardization

Conditional formatting

🚀 Why Data Cleaning Matters

"Before you can find insights in data, you have to make sure the data can be trusted."

Clean data is the foundation of good analysis.

A beautifully designed dashboard or sophisticated machine-learning model cannot compensate for unreliable input data.

This project is a small step toward becoming a better data analyst — one cleaned dataset at a time. 📊

🌟 Future Improvements

Possible extensions to this project include:

Build an Excel dashboard

Analyze product prices by category

Identify the most expensive products

Analyze products by country

Create price-distribution charts

Automate cleaning using Python/Pandas

Build a Power BI dashboard

👨‍💻 Author

Vaisali

Aspiring Data Analyst | Excel | SQL | Python | Power BI

⭐ If you find this project useful, consider giving the repository a star!

Keep learning. Keep building. Keep growing. 🚀
