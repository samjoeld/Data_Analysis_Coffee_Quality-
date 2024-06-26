# Final Report: Exploratory Data Analysis of Coffee Quality Dataset

## Introduction
The purpose of this report is to present the findings from the exploratory data analysis (EDA) conducted on the Coffee Quality Dataset. The dataset contains information about various aspects of coffee production and quality evaluation, including quality measures, bean metadata, and farm metadata.

## Aim
The aim of this project is to identify key factors that influence coffee quality, understand the relationships between different variables, and provide recommendations to improve coffee production practices and overall quality.

## Business Problem / Problem Statement
The coffee industry continuously seeks ways to enhance the quality of coffee beans to meet consumer preferences and increase market value. Understanding the factors that affect coffee quality is crucial for producers, traders, and retailers. This project aims to address the following key questions:
- What are the primary factors influencing coffee quality?
- How do different variables such as processing methods, altitudes, and regions impact coffee quality?
- What recommendations can be made to improve coffee production practices?

## Project Workflow
The workflow for this project involves the following steps:
1. **Data Collection**: Gathering the coffee quality dataset.
2. **Data Understanding**: Exploring the dataset to understand its structure and contents.
3. **Data Cleaning**: Handling missing values, outliers, and inconsistencies.
4. **Data Transformation**: Creating derived metrics and filtering data for analysis.
5. **Exploratory Data Analysis (EDA)**: Conducting univariate, bivariate, and multivariate analyses.
6. **Insights and Recommendations**: Summarizing key findings and providing actionable recommendations.

## Data Understanding
The dataset contains information about various coffee samples, including quality scores and metadata. The primary columns include:
- **Quality Measures**: Aroma, Flavor, Aftertaste, Acidity, Body, Balance, Uniformity, Clean Cup, Sweetness, Cupper Points, Total Cup Points.
- **Bean Metadata**: Species, Variety, Processing Method, Altitude.
- **Farm Metadata**: Owner, Country of Origin, Region, Farm Name, Harvest Year.

Initial exploration of the dataset revealed the following:
- **Dimensions**: The dataset consists of multiple rows and columns.
- **Data Types**: The dataset includes numerical and categorical variables.
- **Summary Statistics**: Provides basic statistical details like mean, median, and standard deviation for numerical columns.

### Dataset Details

- **Species**: Type of coffee species, such as Arabica or Robusta.
- **Owner**: The owner of the coffee farm or plantation.
- **Country of Origin**: The country where the coffee was grown.
- **Farm Name**: Name of the farm where the coffee was produced.
- **Lot Number**: Identifier for the specific lot of coffee.
- **Mill**: The facility where the coffee cherries were processed.
- **ICO Number**: International Coffee Organization number for tracking.
- **Company**: The company responsible for the coffee production.
- **Altitude**: The altitude range where the coffee was grown.
- **Region**: The specific region within the country where the coffee was grown.
- **Producer**: The individual or entity responsible for growing the coffee.
- **Number of Bags**: Quantity of coffee bags produced.
- **Bag Weight**: Weight of each coffee bag.
- **In-Country Partner**: Local partner involved in the coffee production process.
- **Harvest Year**: The year the coffee was harvested.
- **Grading Date**: The date the coffee was graded for quality.
- **Variety**: The specific variety of coffee, such as Bourbon or Typica.
- **Processing Method**: The method used to process the coffee cherries, such as washed or natural.
- **Aroma, Flavor, Aftertaste, Acidity, Body, Balance, Uniformity, Clean Cup, Sweetness, Cupper Points**: Various quality attributes evaluated during cupping.
- **Total Cup Points**: The overall quality score assigned to the coffee.
- **Moisture**: The moisture content of the coffee beans.
- **Category One Defects, Quakers, Category Two Defects**: Indicators of defects in the coffee beans.
- **Color**: The color of the coffee beans.
- **Expiration, Certification Body, Certification Address, Certification Contact**: Certification details.

### Coffee-Producing Countries

The dataset includes coffee samples from various countries known for their coffee production. Here are some of the key coffee-producing countries represented in the dataset:

- **Ethiopia**: Often considered the birthplace of coffee, Ethiopia is known for its diverse coffee varieties and distinct flavor profiles. Ethiopian coffee is often grown at high altitudes, contributing to its unique taste.
- **Brazil**: The largest coffee producer in the world, Brazil is known for its high-volume production and a wide range of coffee flavors. Brazilian coffee is typically grown at lower altitudes compared to other coffee-producing countries.
- **Guatemala**: Known for its high-quality Arabica coffee, Guatemala's coffee is often grown in volcanic soil and at high altitudes, resulting in rich and complex flavors.
- **Peru**: Peru produces a variety of coffee with a focus on organic and fair-trade practices. Peruvian coffee is known for its bright acidity and floral notes.
- **United States (Hawaii)**: Hawaii is the only state in the U.S. that grows coffee, with Kona coffee being particularly famous for its smooth and rich flavor profile.

## Data Cleaning - Missing Values Imputation, Outliers, Handling Inconsistent Values

Data cleaning involved several steps:
- **Handling Missing Values**: Columns with high percentages of missing values were removed, and missing values in numerical columns were imputed with the median.
- **Outlier Detection and Removal**: The Interquartile Range (IQR) method was used to detect and remove outliers.
- **Handling Inconsistent Values**: Categorical values were standardized to ensure consistency.

## Overall Insights Obtained from Analysis

# The EDA revealed several key insights:

Quality Distribution: Quality attributes such as Aroma, Flavor, and Aftertaste show normal distribution with slight skewness towards higher scores.
Correlation: Significant positive correlations were found between Aroma, Flavor, and Total Cup Points.
Altitude Impact: Higher altitudes were associated with better coffee quality scores.
Processing Method: Washed/Wet processing methods generally yielded higher quality scores. 

# Key Findings:

•	Identification of Key Factors Affecting Coffee Quality:

o	Through univariate analysis, we identified aroma, flavor, aftertaste, acidity, and body as the key factors affecting coffee quality.
o	Bivariate analysis revealed strong correlations between aroma and flavor, as well as between processing method and flavor.

•	Understanding the Relationship Between Different Variables:

o	The correlation matrix highlighted significant relationships between variables such as acidity and flavor, altitude and cupping score, and processing method and aftertaste.
o	Segmented univariate analysis showed variations in quality measures across different coffee varieties and processing methods.

•	Recommendations for Improving Coffee Quality and Production Practices:

o	Optimizing processing methods to enhance flavor profiles and aftertaste.
o	Selecting suitable coffee varieties based on desired quality attributes.
o	Implementing farming practices tailored to specific altitudes and regions to improve overall coffee quality.
o	Monitoring and controlling factors such as moisture levels and defects to ensure consistent quality.

•	Important Variables:
o	Aroma, flavor, aftertaste, acidity, body
o	Processing method, coffee variety, altitude, region





•	Dependencies:
o	Aroma and flavor are strongly correlated, indicating that improvements in aroma may lead to enhancements in flavor.
o	Processing method has a significant impact on aftertaste, with certain methods yielding better results.
o	Altitude and region influence coffee quality, with specific regions known for producing beans with distinct flavor profiles.

### Conclusion
      The analysis provided valuable insights into factors affecting coffee quality. Recommendations include optimizing processing methods, selecting suitable coffee varieties, and tailoring farming practices to specific altitudes and regions.

