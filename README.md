# 📘 Ransomware Attack Analysis

## **Project Summary**

This project performs an in-depth Exploratory Data Analysis (EDA) of a ransomware attack dataset to uncover key trends, patterns, and insights. The analysis focuses on understanding the dynamics of ransomware, including its frequency over time, geographical distribution, and economic impact on different industries.

### **Key Objectives**

* **Time-Series Analysis**: Examine how the frequency of ransomware attacks has changed over time.
* **Geospatial Visualization**: Identify the most targeted countries and global attack hotspots.
* **Demographic & Economic Stratification**: Analyze the relationship between attacks and factors like sector, organization size, and financial impact.
* **Outlier Detection**: Pinpoint unusual or high-impact attacks that deviate from the norm.
* **Data Segmentation**: Use machine learning techniques (PCA & Clustering) to find hidden groups of attacks with similar characteristics.

***

## **Project Structure & Steps**

The analysis is structured into a logical, step-by-step workflow to ensure a thorough investigation of the data.

1.  **Import Libraries**: All necessary Python libraries for data manipulation, visualization, and machine learning are imported.
2.  **Data Cleaning**: The raw dataset is loaded and cleaned by handling missing values, standardizing column names, and converting data types for analysis.
3.  **Time-Series Analysis**: A line plot is generated to visualize the frequency of attacks over time.
4.  **Histograms, Boxplots, KDE**: Plots are created to understand the distribution of numerical features and identify potential outliers.
5.  **Correlation Heatmap**: A heatmap visualizes the correlation between numerical variables.
6.  **Geospatial Visualization**: A choropleth map is created to show the geographical distribution of attacks.
7.  **Data Transformations**: Key data points, such as the top 10 most attacked locations, are identified.
8.  **Outlier Detection**: The Z-score method is used to systematically find and analyze outliers.
9.  **PCA & Clustering**: Unsupervised machine learning is used to cluster similar attacks and discover underlying segments.
10. **Demographic & Economic Stratification**: Bar charts are used to compare the average revenue and ransom costs by sector.

***

## **Key Insights & Conclusion**

Based on the analysis, here are the main findings:

* **Attack Frequency**: The analysis reveals a significant upward trend in ransomware attacks over the years, with a notable increase in recent times.
* **Geographical Hotspots**: The United States and the United Kingdom were found to be the most frequently targeted locations.
* **Vulnerable Industries**: The healthcare, government, and technology sectors were among the most affected industries.
* **Economic Impact**: The analysis of average revenue and ransom costs shows that high-revenue sectors and government institutions faced substantial financial threats.
* **Ransomware Families**: The most common strains of ransomware were identified, providing insight into the most popular tools used by cybercriminals.

This project provides a comprehensive overview of the ransomware landscape, offering valuable insights for cybersecurity professionals and researchers.
