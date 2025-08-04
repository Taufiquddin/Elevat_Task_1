# Task 1: Data Cleaning and Preprocessing

## 🧾 Objective
To clean and prepare a raw sales dataset by handling null values, removing duplicates, fixing inconsistent formats, and correcting data types to make the data ready for analysis.

## 📂 Dataset Description
The dataset includes the following columns:
- `Sales Person`
- `Country`
- `Product`
- `Date`
- `Amount`
- `Boxes Shipped`

## 🛠 Tools Used
- Python
- Pandas

## 🔧 Cleaning Steps Performed
1. **Loaded the dataset** using Pandas.
2. **Dropped duplicate rows** to ensure data integrity.
3. **Handled missing values** by removing rows with null entries.
4. **Standardized text data**:
   - Trimmed white spaces
   - Converted country and product names to lowercase/title case
5. **Converted the `Date` column** to datetime format using `pd.to_datetime()`.
6. **Renamed columns** to lowercase and snake_case for consistency.
7. **Fixed data types**:
   - Converted `amount` to float
   - Converted `boxes_shipped` to integer
8. **Exported the cleaned dataset** as `cleaned_sales_data.csv`.

## ✅ Final Output
- Cleaned dataset: `cleaned_sales_data.csv`
- Jupyter Notebook: `Task_1.ipynb`  
- HTML Export: `Task_1.html`

## 📌 Notes
- All invalid data entries or incorrect formats were either corrected or removed.
- Date format issues were handled using error coercion and dropped if not convertible.
