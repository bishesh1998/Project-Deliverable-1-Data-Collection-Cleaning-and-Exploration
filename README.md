# MSCS_634_ProjectDeliverable_1  
**Advanced Data Mining for Data-Driven Insights and Predictive Modeling**

## Dataset Summary
The **Stroke Prediction Dataset** from Kaggle contains **5,110 records** and **11 attributes** describing patient demographics, health history, and lifestyle factors used to predict stroke occurrence (`stroke`: 0 = No, 1 = Yes).

## Data Cleaning
- Dropped non-informative `id` column.  
- Imputed 201 missing `bmi` values using the median.  
- Fixed category typo: `"Govt_jov"` to `"Govt_job"`.  
- No duplicate records found.  
- Verified data types and categorical consistency.

## Exploratory Data Analysis (EDA)
- **Class imbalance:** approximately 95% non-stroke vs about 5% stroke cases.  
- **Age:** Stroke likelihood increases with age.  
- **Glucose:** Right-skewed distribution; higher values linked to stroke.  
- **BMI:** Near-normal distribution, peak around 25–30 (overweight range).  
- **Correlations:** `age`, `avg_glucose_level`, and `hypertension` show strongest associations with stroke.  

## Key Insights
1. Stroke events are rare — imbalance must be handled in modeling.  
2. Older age, high glucose, and hypertension are major risk indicators.  
3. Dataset is clean and suitable for regression and classification models.  
