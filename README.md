# 🏠 Airbnb Data Cleaning with Python & Pandas

A data cleaning project using Python and Pandas on a real-world Airbnb Open Dataset.

---

## 📌 Project Overview

Raw data is rarely analysis-ready. In this project, I took a messy, real-world Airbnb dataset and systematically cleaned it using Python's Pandas library — handling missing values, duplicates, data type corrections, and column standardization to make the data ready for analysis.

---

## 📁 Repository Structure

```
Airbnb-Data-Cleaning-by-pandas-/
│
├── Airbnb_Open_Data.csv              # Raw dataset (original, uncleaned)
├── code.ipynb                        # Jupyter Notebook with all cleaning steps
├── Cleaned_Airbnb_data.csv           # Cleaned output in CSV format
└── Cleaned_Airbnb_data_to_excel.xlsx # Cleaned output in Excel format
```

---

## 🛠️ Data Cleaning Steps Performed

- **Exploratory inspection** — used `.info()`, `.describe()`, and `.shape` to understand the dataset structure
- **Removing duplicates** — identified and dropped all duplicate rows
- **Handling missing values** — filled or dropped NaN values based on column context
- **Data type conversion** — corrected columns stored in wrong formats (e.g. price stored as string)
- **Column standardization** — renamed columns, stripped whitespace, and normalized inconsistent values
- **Filtering invalid data** — removed out-of-range or nonsensical entries
- **Exporting clean data** — saved the final cleaned dataset to both `.csv` and `.xlsx`

---

## 📊 Dataset

**Airbnb Open Data** — sourced from Kaggle  
Contains real-world Airbnb listing information including pricing, location, room type, reviews, and host details.

---

## 🧰 Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas | Data manipulation and cleaning |
| Jupyter Notebook | Interactive development environment |
| NumPy | Numerical operations |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rishabh2170/Airbnb-Data-Cleaning-by-pandas-.git
   cd Airbnb-Data-Cleaning-by-pandas-
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy openpyxl jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook code.ipynb
   ```

---

## 👤 Author

**Rishabh**  
GitHub: [@Rishabh2170](https://github.com/Rishabh2170)
