# Project Overview

This project performs a **deep-dive Exploratory Data Analysis (EDA)** on the **CardioGood Fitness dataset** to uncover demographic trends and purchasing behavior across three treadmill product lines:

- **TM195**
- **TM498**
- **TM798**

The analysis aims to generate **data-driven insights** to support **targeted marketing strategies** and **product positioning decisions**.

---

## Key Data Science Workflows

### 🧹 Data Wrangling
- Conducted extensive data cleaning and preprocessing
- Handled missing values, data types, and categorical consistency
- Produced a high-quality, analysis-ready dataset:  
  **`cleaned_cardio_good_fitness.csv`**

### 📊 Univariate & Bivariate Analysis
- Analyzed key variables such as:
  - Age
  - Income
  - Education
- Examined relationships between demographic attributes and treadmill purchasing behavior
- Identified core customer segments across product lines

### 📈 Statistical Visualization
- Leveraged **Seaborn** and **Matplotlib** to create:
  - Heatmaps
  - Boxplots
  - Pairplots
- Visualized correlations between:
  - Physical fitness ratings
  - Socioeconomic factors
  - Product preferences

### 👥 Customer Profiling
- Segmented customers based on treadmill model preference
- Identified distinct user profiles, including:
  - **High-Income Fitness Enthusiasts** (TM798)
  - **Budget-Conscious Starters** (TM195)
- Enabled targeted marketing and positioning insights

---

## Key Findings

- **Income Correlation:**  
  Higher household income strongly predicts the purchase of the premium **TM798** model.

- **Fitness Rating:**  
  Customers who self-rated their fitness level as **5 (high)** predominantly selected the **TM798**, while the **TM195** is most popular among entry-level users.

- **Demographic Trends:**  
  Specific age ranges and education levels show strong correlations with treadmill usage frequency and product selection.

---

## Technical Stack

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**  
  - Pandas (Data Manipulation)  
  - NumPy (Numerical Analysis)  
  - Matplotlib & Seaborn (Data Visualization)
