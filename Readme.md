# Data Visualization, Preprocessing, and Statistical Analysis
**Author:** Gaurab Karki  
**Course:** Advanced Big Data and Data Mining (MSCS-634-B01)

---

## Purpose
The purpose of this lab was to explore and understand the fundamental processes of **data preprocessing, visualization, and statistical analysis** using Python. It consists of cleaning and preparing real-world data, identifying patterns through visualization, and interpreting statistical measures to uncover meaningful insights.  
The overall objective was to practice transforming raw data into structured, insightful information suitable for analysis and decision-making.

---

## Key Insights and Observations
1. **Data Cleaning and Preprocessing**
   - Missing numerical values were replaced with the column mean, while categorical ones were filled using the mode.
   - Outliers were identified and removed using the **Interquartile Range (IQR)** method.
   - After scaling using **Min-Max normalization**, the dataset showed balanced numerical feature distributions suitable for visualization and modeling.

2. **Visualizations**
   - **Histograms** revealed the spread and skewness of numeric variables.
   - **Boxplots** identified outliers and illustrated data variability.
   - **Correlation heatmaps** helped determine strong linear relationships among features.

3. **Statistical Measures**
   - The **mean, median, and standard deviation** values indicated moderate variation in key attributes.
   - Correlation analysis showed some highly correlated pairs, suggesting possible feature selection opportunities.

---

## Challenges and Decisions
- **Handling Missing Values:** Determining the right imputation technique was crucial to avoid bias. A decision was made to use mean/mode imputation for simplicity.
- **Outlier Detection:** Several extreme values were observed; IQR-based filtering was applied to retain only valid data points.
- **Scaling Strategy:** Chose **MinMaxScaler** for normalization to preserve relative distances between features.
- **Dataset Compatibility:** Ensuring consistent column names and data types required rechecking after preprocessing steps.

---