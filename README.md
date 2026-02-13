# NHANES-Body-Measurement-Analysis

### **Project Overview**

This project presents an exploratory and statistical analysis of anthropometric data from the National Health and Nutrition Examination Survey (NHANES). The objective is to compare body measurements between adult male and female participants and evaluate health-related indicators derived from the dataset.

The analysis focuses on understanding weight distribution, body composition patterns, and relationships between key physical measurements.

### **Dataset**

The dataset consists of two CSV files:

* nhanes_adult_male_bmx_2020.csv

* nhanes_adult_female_bmx_2020.csv

Each file contains seven body measurement variables:

* Weight (kg)

* Standing height (cm)

* Upper arm length (cm)

* Upper leg length (cm)

* Arm circumference (cm)

* Hip circumference (cm)

* Waist circumference (cm)

Derived variables such as Body Mass Index (BMI), Waist-to-Height Ratio, and Waist-to-Hip Ratio were computed during the analysis.

### **Objectives**

* Compare weight distributions between male and female participants.

* Compute statistical measures of central tendency and dispersion.

* Calculate and analyze BMI and waist-based health indicators.

* Standardize measurements using z-scores.

* Examine relationships using Pearson and Spearman correlation analysis.

* Interpret differences in fat distribution patterns.

### **Methods**

* The analysis was conducted using:

* NumPy for matrix operations and statistical computation

* Matplotlib and Seaborn for data visualization

* Pandas for structured data handling

Missing values were handled appropriately before computation and visualization. Standardization was performed using the z-score transformation.

### **Key Findings**

* Male participants generally exhibit higher average body weight and greater variability compared to females.

* BMI shows strong positive correlation with waist and hip circumferences.

* Waist-based ratios provide additional insight into central fat distribution beyond BMI alone.

* Standardization allows meaningful comparison across variables measured on different scales.

### **Repository Structure**

* Capstone_Project_Data_Science_01.ipynb – Complete analysis notebook

* LICENSE – MIT License

* README.md – Project documentation

### **Conclusion**

This project demonstrates the application of numerical computation, statistical analysis, and visualization techniques to real-world health data. The findings highlight measurable differences in body composition patterns and emphasize the importance of combining multiple indicators when evaluating health risk.
