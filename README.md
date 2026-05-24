# ApexPlanet-Task1-Data-Immersion-and-Wrangling


## Project Summary
This project was carried out as part of the **ApexPlanet Data Analytics Internship Program**.

The main purpose of this task was to clean and organize a housing dataset by converting raw and unstructured data into a well-structured format suitable for analysis.



## Goals

- Explore and understand the dataset
- Detect missing information
- Eliminate duplicate entries
- Resolve data inconsistencies
- Identify and manage outliers
- Normalize column naming conventions
- Apply feature creation techniques
- Generate a cleaned dataset


## Technologies Used

- Python
- Pandas
- NumPy
- CSV Files



## Project Files

| File Name | Purpose |
|------------|----------|
| `housing_data_creator.py` | Creates a sample housing dataset |
| `data_cleaning_project.py` | Performs preprocessing and cleaning operations |
| `housing_data.csv` | Raw dataset |
| `cleaned_housing_data.csv` | Processed and cleaned dataset |
| `README.md` | Documentation of the project |



## Data Preprocessing Workflow

### 1. Importing Dataset
Imported the housing dataset into a Pandas DataFrame for further processing.

### 2. Handling Missing Data
- Numerical fields were filled using **median values**
- Categorical fields were filled using **mode values**

### 3. Removing Duplicate Data
Detected and deleted duplicate records to improve data reliability.

### 4. Managing Outliers
Used the **Interquartile Range (IQR)** approach to identify and limit outlier values.

### 5. Feature Creation
Generated a new attribute:

```python
house_age = Current Year - Year Built
```

### 6. Saving Processed Data
Exported the final cleaned dataset for future analytical use.

---

## Skills and Learning Outcomes

- Practical experience in data preprocessing
- Understanding data quality assessment methods
- Data transformation techniques
- Feature engineering concepts
- Python-based data handling workflow

---

## Final Result

✔ Analysis-ready cleaned dataset

✔ Internship project completion

✔ Portfolio-ready GitHub project

---

## Organization

**ApexPlanet Software Pvt. Ltd.**
