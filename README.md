# Car-Sales-Predictive-Analysis


This project was developed as part of the final exam for the course "Object-Oriented Programming" at Universidad del CEMA (UCEMA). The aim of the assessment was to apply key programming concepts in Python, along with data analysis tools, to address a realistic problem and develop a comprehensive solution that included data cleaning, exploratory analysis, and predictive modeling. The assignment also aimed to evaluate the students' ability to structure code in a clear, modular, and reusable way.

Context:

The used car market presents high price variability due to multiple factors such as brand, model, year of manufacture, fuel type, and mileage. This project aims to analyze a real dataset of cars for sale to understand how the main variables behave, detect possible anomalies, and build a predictive model that estimates a vehicle's price based on its characteristics.

Procedure:

Data Loading and Cleaning:

- A dataset with over 11,000 records and 17 variables was used.
- Null values, inconsistent records (e.g., vehicles from the year 1000 or prices below 1000), and duplicates were identified and removed.

Exploratory Data Analysis (EDA):

- Categorical variables such as brand, fuel type, and transmission were analyzed, observing their distribution and relationship with price.
- Numerical variables like mileage, year of manufacture, and price were explored, identifying outliers and non-linear behaviors.
- Correlation plots and visualizations were used to detect relationships between variables.

Preprocessing:

- Categorical variables were encoded using LabelEncoder.
- The dataset was split into independent variables (X) and the dependent variable (y).

Model Training:

- Multiple algorithms were trained and compared: linear regression, decision tree, random forest, and ridge regression.
- R² score was used as a performance metric.
- Cross-validation was applied to evaluate the models’ generalization.

Prediction:

- The best model was selected based on the balance between accuracy and generalization.
- Price predictions were made on a previously separated test dataset.

Conclusions:

- A solid-performing model was successfully built to estimate prices based on vehicle characteristics.
- Key variables explaining price variability were identified: brand, year of manufacture, transmission type, and fuel type.
- The exploratory analysis helped detect patterns and relationships not immediately obvious, adding value to the modeling process.
- This project demonstrates the usefulness of data analysis to generate actionable insights in a business context, such as pricing strategy or detecting overvalued or undervalued vehicles.
