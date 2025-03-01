




# **Advanced Soybean Agricultural Dataset**

## **Overview**

The **Advanced Soybean Agricultural Dataset** is a comprehensive dataset designed to assist in agricultural research and machine learning applications. Compiled in 2025 by a team of experts at the **College of Agriculture, University of Tikrit**, this dataset includes various agricultural parameters related to soybean plants, focusing on growth, productivity, and nutritional value.

### **Contributors:**
- **Assistant Lecturer Basim Fahad Abdullah**, College of Agriculture, Tikrit University.
- **Assistant Professor Dr. Dawood Salman Madad**, College of Agriculture, Tikrit University.
- **Assistant Professor Wisam Dawood Abdullah**, College of Computer Science and Mathematics, Tikrit University.

## **Dataset Description**

This dataset consists of **55,450 rows** and **13 columns**, each capturing important agricultural parameters essential for understanding soybean growth under different conditions. It provides detailed insights into the relationship between environmental factors and soybean crop characteristics.

### **Features in the Dataset:**
1. **Plant Height (PH)**
2. **Number of Pods (NP)**
3. **Biological Weight (BW)**
4. **Sugars (Su)**
5. **Relative Water Content in Leaves (RWCL)**
6. **ChlorophyllA663**
7. **Chlorophyllb649**
8. **Protein Percentage (PPE)**
9. **Weight of 300 Seeds (W3S)**
10. **Leaf Area Index (LAI)**
11. **Seed Yield per Unit Area (SYUA)**
12. **Number of Seeds per Pod (NSP)**
13. **Protein Content (PCO)**

### **Key Columns:**
- **Parameters**: The `Parameters` column encodes essential experimental conditions affecting soybean growth. The values in this column represent:
  - **G**: Genotype (six different genotypes)
  - **C**: Salicylic acid levels (250 mg, 450 mg, and control)
  - **S**: Water stress (5% and 70% of field capacity)

### **Other Key Information:**
- **Size**: 55,450 samples
- **Data Type**: Numerical and Categorical

This dataset provides detailed information on various factors influencing soybean growth and its productivity, making it a valuable resource for researchers working on **precision agriculture**, **crop health assessment**, **yield prediction**, and **agricultural optimization**.

## **Dataset Features Explanation**

1. **Plant Height (PH)**: Measures the height of the soybean plant.
2. **Number of Pods (NP)**: The total number of pods produced by each plant.
3. **Biological Weight (BW)**: The weight of the soybean plant.
4. **Sugars (Su)**: The amount of sugar content in the plant.
5. **Relative Water Content in Leaves (RWCL)**: Measures the water content in the soybean leaves.
6. **ChlorophyllA663**: Chlorophyll A content at 663 nm.
7. **Chlorophyllb649**: Chlorophyll B content at 649 nm.
8. **Protein Percentage (PPE)**: Protein percentage in the plant.
9. **Weight of 300 Seeds (W3S)**: The weight of 300 seeds from the soybean plant.
10. **Leaf Area Index (LAI)**: A measure of the leaf area per unit of land.
11. **Seed Yield per Unit Area (SYUA)**: The yield of seeds per unit area.
12. **Number of Seeds per Pod (NSP)**: The average number of seeds per pod.
13. **Protein Content (PCO)**: The overall protein content of the plant.

## **Intended Use**

The **Advanced Soybean Agricultural Dataset** is structured for use in various analytical and predictive modeling tasks, such as:
- **Yield Prediction**: Predicting the yield of soybean crops based on various input parameters.
- **Crop Health Assessment**: Analyzing the health of crops under different environmental conditions.
- **Agricultural Optimization**: Improving the efficiency of farming techniques based on data-driven insights.
- **Machine Learning Applications**: Utilizing machine learning models to make predictions or classify different aspects of soybean growth.

This dataset is an ideal resource for **agronomists**, **data scientists**, and **researchers** looking to apply machine learning techniques to agricultural problems, especially in the area of **precision farming**.

## **How to Use the Dataset**

You can download and use the dataset for machine learning tasks, statistical analysis, or data visualization. Here are some possible approaches:
- **Data Preprocessing**: Handle missing values, scale features, and encode categorical variables for machine learning models.
- **Model Training**: Train machine learning models such as linear regression, decision trees, or deep learning models to predict plant characteristics.
- **Exploratory Data Analysis (EDA)**: Use data visualization techniques like histograms, scatter plots, and boxplots to understand relationships in the data.

## **Getting Started**

To get started with the dataset, you can clone the repository and load the dataset using popular libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Scikit-learn** in Python.

```bash
git clone https://github.com/your-repository/advanced-soybean-dataset.git
cd advanced-soybean-dataset
```

In your Python code, you can load the dataset using the following command:
```python
import pandas as pd

# Load the dataset
df = pd.read_csv('path_to_dataset.csv')

# Display the first few rows
print(df.head())
```

