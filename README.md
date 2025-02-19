# Car Sales Analysis

### Project Overview
The project focuses on analyzing a dataset to extract insights using business intelligence techniques. It involves processing and visualizing data to uncover patterns, trends, and correlations. The goal is to apply data analysis methods to support decision-making in a specific domain.

### Data Source
The dataset used for the analysis is the "Car Sales.xlsx - car_data.csv" file which was sourced from Kaggle. It contains structured data related to car sales, including information on car models, sales prices, transaction dates, customer demographics, and dealership details. 

### Tools Used
The following tools were utilized for data processing, analysis, and visualization:
- **Tableau**: Used for creating visualizations and identifying key sales trends.
- **Weka**: Implemented the Decision Tree (J48) algorithm for data mining and pattern recognition.
- **Microsoft Excel**: Used for initial exploration, formatting, and pre-processing of data.
- **Python** (Pandas, NumPy, Matplotlib, Seaborn): Assisted in additional data manipulation and visualization.

### Data Cleaning & Preparation
To ensure accuracy and reliability, several data preprocessing steps were performed:
- **Removal of unnecessary columns**: Columns such as **Car ID, Customer Name, Dealer Name, Phone, and Dealer No** were removed as they were not relevant to the analysis.
- **Handling missing values**: The dataset **had no missing values or duplicates**, so no imputation was necessary.
- **Identifying and resolving anomalies**: Outliers in **Annual Income** and **Car Prices** were identified using box plots. These extreme values were legitimate and were not removed.
- **Feature transformations**:
  - **Numerical Scaling**: Features like **Annual Income** and **Price ($)** were standardized to ensure uniformity in analysis.
  - **Categorical Encoding**: Variables such as **Company, Engine, Transmission, Color, and Body Style** were encoded for compatibility with machine learning models.

### Key Insights & Findings
- Most car buyers fall within the **$50,000 - $75,000** annual income range, indicating this as the primary customer segment.
- Cars priced between **$20,000 - $30,000** have the highest demand.
- **Chevrolet, Dodge, and Ford** are the most sold car brands.
- **SUVs and Hatchbacks** dominate the market, aligning with current consumer preferences.
- **Automatic transmissions and Double Overhead Camshaft engines** are preferred by most buyers.
- **Austin and Janesville** regions report the highest sales, suggesting strong market demand.

### Data Mining & Predictive Modeling
- **Algorithm Used**: Decision Trees (**J48 classifier in Weka**) was chosen due to its interpretability and effectiveness in handling both categorical and numerical data.
- **Model Training**: The dataset was converted to **CSV format** and loaded into Weka, where feature scaling and encoding were performed.
- **Model Evaluation**: 
  - **10-fold cross-validation** was used to prevent overfitting.
  - **Precision, Recall, and F-Measure** showed balanced performance across different classes.
  - **ROC Curves** helped assess classification accuracy, with higher values indicating stronger reliability.

### Conclusion & Future Work
The project successfully identified **key factors influencing car sales** through business intelligence and data mining techniques. Moving forward, improvements can include:
- Expanding the dataset to analyze more regions and demographic factors.
- Applying machine learning models for **sales prediction and customer segmentation**.
- Automating data pipelines for **real-time sales analysis**.

---
This project demonstrates the role of data analytics in **understanding market trends, optimizing sales strategies, and making data-driven decisions** in the automotive industry.

