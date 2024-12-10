# **Analyzing the Impact of GDP Growth on Health Outcomes**  

## **Overview**  
This project explores the relationship between a country’s GDP growth and its public health metrics, such as infant mortality rate and life expectancy. The case study uses statistical models, including Linear Regression and the Grossman Model, to analyze data from various countries over several decades. The research aims to determine how economic growth affects healthcare outcomes and whether causality exists between the two variables.

---

## **Aim**  
The primary objective of this study is to evaluate the impact of GDP per capita on public health metrics by examining:  
- **Infant Mortality Rate (IMR)**  
- **Life Expectancy (LE)**  
- **Health Expenditure Per Capita (HEPC)**  

---

## **Methodology**  

### **Data Collection**  
Data was sourced from the World Bank’s World Development Indicators, covering 266 countries from 1960 to 2021. Key variables include:  
- **GDP per Capita** (US$)  
- **Infant Mortality Rate** (deaths per 1,000 live births)  
- **Life Expectancy** (years)  
- **Literacy Rate** (%)  
- **Health Expenditure Per Capita** (US$)  
- **Pollution Levels** (CO₂ emissions in kilotons)  

### **Statistical Models Used**  
1. **Ordinary Least Squares (OLS) Regression**:  
   - Used to assess the linear relationships between GDP and health indicators.  
   - The models included GDP as the primary independent variable, while dependent variables included IMR, LE, and HEPC.  

2. **Grossman Model Implementation**:  
   - Modeled life expectancy as a function of GDP, health expenditure, literacy rate, and pollution levels to explore health investments.

---

## **Evaluation Metrics**  

### **Model Performance Metrics**  
- **R-squared (R²)**: Measures the proportion of variance explained by the model.  
- **AIC (Akaike Information Criterion)**: Evaluates model fit.  
- **Prob (F-statistic)**: Tests the significance of the overall model.  

---

## **Results**  

1. **Infant Mortality Rate (IMR)**:  
   - Countries with higher GDP generally show reduced infant mortality rates.  
   - GDP growth correlates with a 46% decrease in IMR from 2000 to 2020 globally.  

2. **Life Expectancy (LE)**:  
   - A positive correlation exists between GDP growth and life expectancy, reflecting improved healthcare infrastructure and public services.  

3. **Health Expenditure Per Capita (HEPC)**:  
   - An increase in GDP correlates with higher health expenditure per capita, enabling better healthcare access.

---

## **File Structure**  

### **Report and Analysis Files**  
1. **`201727213 mm23rt Case Study Report.pdf`**:  
   - A comprehensive report analyzing the relationship between GDP growth and key health outcomes using statistical models and economic theories.  

2. **`Case Study Analysis.ipnyb`**:  
   - Contains the entire data processing, statistical modeling, and visualization pipeline, including:  
     - Data cleaning and preprocessing  
     - Statistical analysis using OLS regression  
     - Generating visualizations (scatter plots, histograms, and trend lines)  

---

