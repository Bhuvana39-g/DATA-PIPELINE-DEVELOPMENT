
# Task 1 – ETL Pipeline (Titanic Dataset)

## Description
This project performs an ETL (Extract, Transform, Load) pipeline on the Titanic dataset from Kaggle.

## Steps Performed
- **Extract:** Loaded the dataset from local Kaggle file
- **Transform:**
  - Handled missing values (Age, Cabin, Embarked)
  - Encoded categorical variables (Sex, Embarked)
  - Scaled numerical features (Age, Fare)
  - Added a derived feature (`IsMinor`)
- **Load:** Saved the processed dataset to `processed_titanic.csv`

## Tools Used
- Python
- Pandas
- Scikit-learn

## Output
The file `processed_titanic.csv` contains the final clean dataset ready for modeling.
