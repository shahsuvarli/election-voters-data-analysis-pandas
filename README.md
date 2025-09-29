# Azerbaijan Voter Demographics Analysis

This project explores voter demographics in Azerbaijan using precinct-level data.  
The primary goal is not only to uncover insights from the dataset but also to **practice and demonstrate the use of Python's pandas library** for data analysis and cleaning.

## 📌 Project Importance
Understanding demographic patterns—such as age distributions across voting precincts—can be valuable for:  
- Identifying age group trends in the electorate  
- Assessing representation of younger vs. older populations  
- Building a foundation for more advanced statistical and political analysis  

Although this dataset is real, the **main focus of the project is educational**: strengthening skills in pandas, data cleaning, grouping, and visualization.

## 🛠️ Methods
- **Data Cleaning:** Handling missing values, inconsistent formatting, and duplicates  
- **Feature Engineering:** Creating age groups from birth years, validating age calculations  
- **Aggregation:** Counting voters per age group and precinct  
- **Visualization:** Pie charts and tables to highlight age distribution patterns  

## 📊 Results (Summary)
- The largest share of voters are in the **18–38** age range (~43%), showing a young population base  
- The **38–58** group (~38%) is also strongly represented  
- Older age groups **58+** are much smaller, with <1% above 79 years  

This suggests the voter base is dominated by **young and middle-aged individuals**.

## 🚀 Learning Focus
This repository is primarily an **exercise in pandas functions**:  
- `groupby`, `cut`, `crosstab`  
- `merge`, `concat`, `reset_index`  
- Data cleaning with `dropna`, `fillna`, `replace`  
- Visualization with `matplotlib`  

## 📂 Repository Structure
- `aze_voters.ipynb` → Main Jupyter Notebook with the analysis  
- `README.md` → Project documentation (this file)  

## 📊 Data Source
The dataset is available on Kaggle: [Azerbaijan Voter List](https://www.kaggle.com/datasets/msbrown/azerbaijanvoterlist/data)

## ✅ Next Steps
- Extend analysis with gender or regional comparisons (if data available)  
- Apply statistical tests to compare age distributions  
- Automate pipeline for repeated analysis  

---

> ⚡ **Note:** This project is mainly for practicing `pandas` and exploring data manipulation techniques. The insights are secondary to the educational value.
