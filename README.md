# 📊 Task 2: Exploratory Data Analysis (EDA)

## 🧠 Objective
Perform Exploratory Data Analysis on a dataset (e.g., Titanic Dataset) to:

- Understand the structure and relationships within the data.
- Identify trends, patterns, and anomalies.
- Prepare the dataset for further modeling or decision-making.

---

## 🛠 Tools Used
- **Pandas** – for data manipulation and statistics  
- **Matplotlib** – for basic visualizations  
- **Seaborn** – for advanced statistical plots  
- **Plotly** – for interactive visualizations  

---

## ✅ What I Did / Learned

### 1. Generated Summary Statistics
- Used `.describe()` to find **mean**, **median**, **standard deviation**, **min**, **max**, and **quartiles**.
- Understood the distribution and range of numeric variables.

### 2. Visualized Distributions
- **Histograms**: Visualized frequency distribution of numerical features.
- **Boxplots**: Detected **outliers**, **spread**, and **skewness** in features like `Age`, `Fare`.

### 3. Analyzed Relationships
- Created **correlation matrix** and **heatmaps** to understand linear relationships between features.
- Used **pairplots** to observe interaction between multiple numerical variables.

### 4. Detected Patterns & Anomalies
- Identified **outliers** and **missing data**.
- Observed **survival rate** patterns in Titanic dataset based on **gender**, **class**, and **age**.

### 5. Inferred Key Insights
- Found that **females had a higher survival rate**.
- **Younger passengers** and those in **higher classes** were more likely to survive.
- Noticed **Fare** had **positive skewness** and was impacted by outliers.

---

## ❓ Interview Questions & Answers

**1. What is the purpose of EDA?**  
To explore and understand the dataset, identify patterns, anomalies, and prepare it for machine learning or business decisions.

**2. How do boxplots help in understanding a dataset?**  
They visualize the spread of data, detect outliers, and highlight central tendencies like median and interquartile range.

**3. What is correlation and why is it useful?**  
Correlation measures the linear relationship between two variables. It's useful for feature selection and detecting multicollinearity.

**4. How do you detect skewness in data?**  
Through histograms, boxplots, and statistical metrics like skewness values. Positive/negative skew indicates asymmetry in distribution.

**5. What is multicollinearity?**  
When two or more features are highly correlated, which can cause issues in regression models by inflating variance.

**6. What tools do you use for EDA?**  
Pandas, Matplotlib, Seaborn, Plotly, and sometimes NumPy and Scikit-learn for preprocessing.

**7. Can you explain a time when EDA helped you find a problem?**  
Yes, while working with the Titanic dataset, EDA helped me uncover that some features had many missing values and others had outliers that skewed the model’s performance.

**8. What is the role of visualization in ML?**  
Visualizations make it easier to understand data trends, spot anomalies, explain models, and communicate insights effectively to stakeholders.

---

## 📂 Dataset Used
**Titanic Dataset** – [Click here to download](https://www.kaggle.com/competitions/titanic/data)  
Contains features like `Survived`, `Age`, `Sex`, `Pclass`, `Fare`, etc.

---

## 📌 Conclusion
EDA is a foundational step in any data science or machine learning project. It improves our understanding of the data and guides better feature engineering and model selection.
