# 📊 Netflix Dataset Cleaning and Preprocessing

## 🧩 Task 1: Data Cleaning and Preprocessing

### 🎯 Objective
To clean and prepare a raw Netflix dataset by handling missing values, removing duplicates, fixing inconsistent formats, and standardizing the data for further analysis.

---

### 🛠️ Tools Used
- **Python** (Pandas)

---

### 📁 Deliverables
- ✅ Cleaned dataset (`netflix_titles_cleaned.csv`)
- ✅ Jupyter notebook with cleaning steps (`Data_Preprocessing.ipynb`)
- ✅ Summary of changes (see below)

---

### 📝 Summary of Cleaning Steps

1. **Handled Missing Values**  
   - Identified missing values using `.isnull()`
   - Dropped rows with missing `rating` and `duration` fields

2. **Removed Duplicates**  
   - Used `.drop_duplicates()` to eliminate redundant entries

3. **Standardized Text Columns**  
   - Trimmed whitespace and applied title case to fields like `type` and `country`

4. **Formatted Dates**  
   - Converted `date_added` to consistent `datetime` format using `pd.to_datetime()`

5. **Cleaned Column Headers**  
   - Renamed all columns to lowercase and replaced spaces with underscores for readability

6. **Verified and Fixed Data Types**  
   - Ensured `release_year` is stored as an integer
   - Confirmed `date_added` is in datetime format

---

### ✅ Conclusion
In conclusion, the Netflix dataset was successfully cleaned and preprocessed using Python (Pandas). Missing values in important fields were identified and handled appropriately, and duplicate entries were removed to ensure data consistency. Text data such as country names and content types were standardized for uniformity. Dates were converted to a consistent datetime format, and column names were renamed to be lowercase with underscores for clarity. Data types were also verified and corrected where necessary. These preprocessing steps have resulted in a structured and reliable dataset, ready for meaningful analysis and insights.

---

### 🔗 References
- Dataset Source: [Netflix Titles on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)


