# Data Cleaning Process (Power BI - Power Query)

## 📌 Overview
All data cleaning and transformation were performed inside Power BI using Power Query.  
The goal was to ensure the dataset is clean, consistent, and ready for analysis.

---

## ⚠️ Issues Identified

### 1. Missing Values
- Null values were found in certain columns  

### 2. Duplicate Records
- Duplicate entries identified in Employee ID (EmpID)  

### 3. Inconsistent Values
- Example: "TravelRarely" was inconsistent  
- Standardized to "Travel_Rarely"  

### 4. Unnecessary Columns
- Column: YearsWithCurrManager had null values and was not required  
- Removed from dataset  

### 5. Data Type Issues
- Some columns had incorrect data types  

---

## 🧹 Cleaning Steps Performed

### Handling Missing Values
- Reviewed columns for null values  
- Removed or ignored columns where data was not useful  

### Removing Duplicates
- Selected all columns and removed duplicate rows  

### Standardization
- Fixed inconsistent text values  
- Applied consistent naming format  

### Data Type Correction
- Used "Detect Data Type" in Power Query  
- Ensured numeric and categorical fields are correctly formatted  

---

## ✅ Outcome
- Clean dataset ready for analysis  
- Improved data consistency and accuracy  
- Enabled reliable insights in Power BI dashboard  

---

## 🛠 Tool Used
- Power BI (Power Query)
