# Understanding Impact of Ozempic on obese hypertensive patients

## Data Description

The dataset provided for analysis comprises medical claims data for obese and hypertensive patients aged 40-75, along with a subset of prescription data detailing medications dispensed to a fraction of these patients.

- **Medical Claims Data:** This dataset contained comprehensive information on medical services rendered to the specified patient group. It included patient demographics, details of medical services received, Ozempic treatment information, health conditions, and potential missing values. External sources such as Wikipedia's List of ZIP Code prefixes and Data USA  provided additional demographic insights related to specific zip code prefixes.

- **Prescription Data:** A concentrated subset of the medical claims dataset, provided details of prescriptions dispensed to a subset of patients. It included information on prescribed medications, dosage, frequency, and other relevant details.


## Objective of the project

Explore the effects of Ozempic on obese and hypertensive patients aged 40-75, employing advanced statistical techniques to estimate treatment effects accurately.

## Analysis Performed in the Dataset

1. Conducted Exploratory Data Analysis (EDA) to understand the dataset's structure, identified missing values, and summarized key statistics.
2. Preprocessed and merged the datasets, handled missing data and encoding categorical variables.
3. Addressed potential endogeneity issues in estimating the treatment effect of Ozempic.
4. Developed a model for estimating the treatment effect using Double-Lasso or Treatment Effect Lasso techniques.
5. Evaluated and interpreted the developed model's performance to assess the accuracy of estimating the treatment effect.
