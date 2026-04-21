# mental-wellbeing-env-analysis
Data science &amp; biostatistics project on UK wellbeing and green space

# Modeling Environmental Determinants of Mental Wellbeing  
### Integrating Data Science and Biostatistics on UK Local Authority Data

## Overview
This project investigates the relationship between environmental factors—specifically access to green space—and mental wellbeing across UK local authorities.

Using a combination of data science and biostatistical techniques, the analysis explores whether proximity to parks and availability of green space are associated with variations in anxiety, happiness, and life satisfaction.

---

## Objectives
- Analyze the relationship between green space access and mental wellbeing
- Apply regression, clustering, and hypothesis testing techniques
- Demonstrate a full data science workflow (data cleaning → modeling → interpretation)
- Highlight limitations of aggregated regional data

---

## Datasets

### 1. UK Wellbeing Data (ONS)
- Source: UK Office for National Statistics
- Description: Measures of life satisfaction, happiness, anxiety, and sense of worth
- Link: https://www.ons.gov.uk/peoplepopulationandcommunity/wellbeing

### 2. UK Green Space Data
- Source: Ordnance Survey + Google Mobility
- Description: Access to parks, distances, and environmental exposure metrics

---

## Methods Used

### Data Processing
- Cleaning and standardizing datasets
- Filtering to a common time period (2020–2021)
- Pivoting data from long to wide format
- Merging datasets on geographic identifiers

### Statistical & ML Techniques
- **Linear Regression** → relationship between green space and anxiety  
- **K-Means Clustering** → grouping regions by wellbeing profiles  
- **Hypothesis Testing (t-test)** → comparing anxiety across groups  
- **Exploratory Data Analysis** → distributions, correlations, scatter plots  

---

## Key Findings

- Wellbeing indicators (happiness, life satisfaction) are strongly correlated  
- Anxiety shows a negative relationship with other wellbeing measures  
- Environmental variables show **weak relationships** with anxiety  
- No statistically significant difference in anxiety based on green space access  
- Clustering reveals distinct wellbeing profiles across regions  

---

## Limitations

- Small sample size (limited statistical power)  
- Aggregated regional data (loss of local variability)  
- Missing potential confounders (income, health, demographics)  

---

## Future Work

- Use more granular (individual or neighborhood-level) data  
- Include socioeconomic and demographic variables  
- Apply advanced models (Random Forest, Lasso, etc.)  
- Conduct longitudinal and spatial analysis  

---

## Technologies Used

- Python (Pandas, NumPy)
- Scikit-learn
- Seaborn & Matplotlib
- SciPy

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/mental-wellbeing-env-analysis.git
