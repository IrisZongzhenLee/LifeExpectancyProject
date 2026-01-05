# 🌍 Life Expectancy Analysis (2010 vs 2015)

This project conducts a comprehensive statistical analysis of **WHO Life Expectancy data**, comparing global health outcomes across countries in **2010 and 2015**. Using clustering, principal component analysis (PCA), and maximum likelihood estimation (MLE), the study investigates how health, demographic, and socioeconomic factors relate to life expectancy.

---

## 📌 Project Overview

- **Data Source:** WHO Life Expectancy dataset (via Kaggle)  
- **Observations:**  
  - 157 countries per year  
  - 314 total country-year observations  
- **Variables:** 20 health, demographic, and economic indicators  
- **Years Analyzed:** 2010 and 2015 (analyzed separately)

### Objectives
- Cluster countries based on health outcomes
- Identify key drivers of life expectancy
- Compare global health patterns between 2010 and 2015

---

## 📊 Methodology

### 1. Data Preparation
- Filtered dataset for years 2010 and 2015
- Removed missing values and inconsistencies
- Selected relevant variables for health analysis

### 2. Cluster Analysis (K-Means)
- Applied K-means clustering separately for each year
- Identified two dominant clusters:
  - **Cluster 1:** Lower life expectancy, higher mortality, lower immunization and water access  
  - **Cluster 2:** Higher life expectancy, lower mortality, stronger health infrastructure
- Examined regional composition of clusters

### 3. Exploratory Data Analysis
- Scatterplots explored relationships such as:
  - Life Expectancy vs. GNI per capita
  - Life Expectancy vs. Alcohol consumption
- Findings suggest life expectancy is driven more by health infrastructure than income or alcohol use

### 4. Principal Component Analysis (PCA)
- Reduced dimensionality of 16 interval variables
- Retained first 4 principal components (≈83–84% variance explained)
- Identified latent factors such as:
  - Overall health status
  - Immunization accessibility
  - Nutrition and obesity patterns

### 5. Maximum Likelihood Estimation (MLE)
- Modeled life expectancy with a Gaussian distribution
- Estimated mean and variance for 2010 and 2015
- Constructed 95% confidence intervals
- Observed an average increase of ~1 year in global life expectancy from 2010 to 2015

---

## 🔍 Key Findings

- Countries naturally cluster into developing vs. developed health profiles
- Immunization rates, mortality, BMI, and water access are major determinants of life expectancy
- Alcohol consumption shows little correlation with life expectancy
- National population size contributes minimally to health variation
- Global life expectancy improved between 2010 and 2015

---

## 📁 Repository Structure
