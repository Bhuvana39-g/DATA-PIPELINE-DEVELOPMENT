# DATA-PIPELINE-DEVELOPMENT

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**:   BHUVANANJALI NADAPANA

**Intern ID**:  CT04DG3255

**DOMAIN**:  DATA SCIENCE

**BATCH DURATION**: JUNE 22nd,2025 to JULY 23rd,2025

**MENTOR NAME**: NEELA SANTHOSH

**Data Pipeline Project Description**
This project involves the development of a complete ETL (Extract, Transform, Load) pipeline using Python, Pandas, and Scikit-learn to automate data preprocessing, transformation, and loading tasks.

Tools Used
Python: Core programming language for scripting the pipeline.

Pandas: Used for data extraction, manipulation, and cleaning. Pandas provides flexible DataFrame structures for handling tabular data efficiently.

Scikit-learn: Used for preprocessing techniques, including handling missing values, encoding categorical variables, and scaling numerical features.

Pipeline Steps
Extraction:
The pipeline reads raw data from CSV files using Pandas’ read_csv() function. This step loads the data into a DataFrame for easy manipulation and inspection.

Transformation:

Missing Value Imputation: Missing numeric values are replaced using the SimpleImputer from Scikit-learn, typically applying the mean strategy.

Encoding: Categorical columns are converted into numeric format using LabelEncoder for label encoding or pd.get_dummies() for one-hot encoding.

Feature Scaling: Numerical features are standardized to have zero mean and unit variance using StandardScaler, improving model performance and training stability.

Column Selection: Original raw columns can be dropped or retained as needed after transformations.

Loading:
The cleaned and transformed data is saved back to a CSV file using Pandas’ to_csv() method. This makes it ready for further analysis or machine learning modeling.

Purpose
The pipeline automates repetitive data preparation tasks, ensuring consistency, reproducibility, and improved data quality for downstream machine learning workflows.

Keywords: Pandas, Scikit-learn, ETL, Data Preprocessing, Data Transformation, Feature Engineering.
