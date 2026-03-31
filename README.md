# Basic-Data-Preprocessing
Beginner-friendly data preprocessing project covering missing values, duplicates, data cleaning, and text preprocessing. Includes step-by-step outputs for better understanding and use of inplace=True to reflect changes in the dataset.
## 📊 Data Preprocessing Practice (Beginner Friendly)

This repository demonstrates basic and commonly used **data preprocessing techniques** to help beginners understand how raw data is transformed into a clean and structured format.

The dataset used here contains unstructured and messy data. Step by step, the data is cleaned, processed, and converted into a format suitable for analysis.

### 🔧 What has been done:

* Loaded raw dataset and explored its structure
* Handled missing values (removed and filled where necessary)
* Removed duplicate records
* Converted data types (e.g., rating and price to numeric)
* Cleaned unstructured text data (lowercase, removed special characters, stopwords, etc.)
* Standardized column names
* Created a structured dataset ready for analysis

### 🧠 Important Notes for Beginners:

* Most of the preprocessing techniques used here are **common and applicable to many datasets**
* For better understanding, multiple `print()` statements are included to show intermediate outputs at each step
* When modifying the dataset, using `inplace=True` is important so that changes are directly reflected in the main DataFrame (and later in the exported Excel/CSV file)

### 📌 Example:

```python
df.dropna(inplace=True)
```

This ensures the changes are applied to the original dataset.

### 🚀 What's Next:

More advanced preprocessing techniques and projects will be added in the upcoming days.

---

This repository is created for learning and practicing real-world data cleaning workflows.
