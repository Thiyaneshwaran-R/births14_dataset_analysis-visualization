# Births14 Dataset Analysis  

## 📌 Project Overview  
This project performs **Exploratory Data Analysis (EDA - Exploratory Data Analysis)** and **data cleaning** on the Births14 dataset. The dataset contains demographic and medical factors related to births, such as parental ages, maturity, weeks, visits, infant outcomes, and habits.  

The goal of this project is to:  
- Explore and understand the dataset  
- Handle missing values  
- Detect and treat outliers  
- Generate visualizations to uncover patterns and relationships  

---

## 📊 Steps Performed  
1. **Data Loading**  
   - Imported dataset into a Jupyter Notebook  

2. **Basic Exploration**  
   - `.info()`, `.describe()`, `.shape`, `.head()`, `.tail()`  
   - Accessed specific rows and columns  

3. **Aggregate Functions**  
   - Mean, Sum, Minimum, Maximum  

4. **Handling Null Values**  
   - Detected missing values  
   - Treated nulls without dropping any columns  

5. **Distribution Check**  
   - Plotted **histograms**  
   - Verified normal distribution  
   - Applied **Z-score method** for outlier detection  

6. **Outlier Treatment**  
   - Identified outliers  
   - Applied **clipping** to handle extreme values  

7. **Visualizations**  
   - Boxplot  
   - Scatterplot  
   - Bar chart  
   - Line graph  
   - Pie chart  
   - Correlation heatmap  

---

## 📂 Files in Repository  
- `births14_analysis.ipynb` → Notebook with EDA, cleaning, and visualizations  
- `births14_cleaned_dataset.csv` → Cleaned dataset ready for further analysis or modeling  

---

## 🛠️ Tools Used  
- Python (Jupyter Notebook)  
- Pandas  
- Matplotlib  
- Seaborn  
- **scipy.stats** (Z-score method for outlier detection)  

---

## 📈 Key Outcome  
A **cleaned and well-understood dataset** that is ready for predictive modeling or visualization dashboards (e.g., Power BI, Tableau).  
