# Data Preprocessing & Feature Engineering 

##  Overview
This repository contains a Jupyter Notebook (`Assignment9.ipynb`) focused entirely on the most crucial phase of the machine learning pipeline: **Data Preparation**. Before a model can make accurate predictions, the data must be cleaned, scaled, and transformed. This project demonstrates best practices in handling messy, real-world data to optimize it for algorithmic processing.

##  Key Techniques & Workflows Demonstrated

### 1. Data Exploration & Cleaning
* Conducted initial data profiling (summary statistics, data type checks).
* Handled missing values using strategic imputation and removal techniques to maintain dataset integrity.

### 2. Feature Scaling
* Applied both **Standard Scaling** (Z-score normalization) and **Min-Max Scaling** to numerical features.
* Includes a written analysis discussing the specific scenarios and mathematical reasons for preferring one scaling technique over the other depending on the algorithm used (e.g., distance-based vs. tree-based models).

### 3. Categorical Encoding
* Implemented **One-Hot Encoding** for nominal variables with low cardinality (fewer than 5 categories) to prevent unintended ordinal relationships.
* Implemented **Label Encoding** for categorical variables with high cardinality (more than 5 categories) to maintain dimensionality.
* Includes a comparative discussion on the pros and cons of both encoding methods.

### 4. Feature Engineering & Transformation
* **Feature Creation:** Engineered two entirely new, mathematically derived features designed to capture deeper relationships in the data, complete with the business rationale behind their creation.
* **Skewness Correction:** Applied a logarithmic transformation to highly skewed numerical features to approximate a normal distribution, improving the performance of linear models.

##  Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Libraries:** `pandas`, `numpy`, `scikit-learn` (for scalers and encoders), `matplotlib`, `seaborn` (for distribution visualization)
