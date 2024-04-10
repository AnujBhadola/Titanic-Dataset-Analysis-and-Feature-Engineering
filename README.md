# Titanic Dataset Analysis and Feature Engineering

This repository contains the analysis of the Titanic dataset. The dataset was cleaned and explored using pandas in Python. Various features were engineered to extract meaningful insights from the data.

## Insights

1. Survival Rate:
   - 61.6% of people died and 38.4% survived.

2. Passenger Class Distribution:
   - There were 3 passenger classes, with 55.1% of people in 3rd class, presumably due to cheaper ticket prices.

3. Gender Distribution:
   - 64.8% of passengers were male and 35.2% were female.

4. Embarkation Port:
   - 72.4% of passengers embarked from Southampton, making it the most common embarkation port.

5. Survival Rate by Passenger Class:
   - 75% of deaths occurred in the 3rd class, while 62% of survivors were from the 1st class.

6. Survival Rate by Gender:
   - 81% of males died while 74% of females survived.

7. Survival Rate by Embarkation Port:
   - 66% of passengers who embarked from Southampton died, compared to 61% from Queenstown. This is attributed to the majority of passengers from these ports being in the 3rd class.

8. Age and Survival:
   - Passengers below 20 had a higher chance of survival, while those above 20 and below 40 had a higher chance of dying. Those above 60 also had a higher chance of dying.

9. Family Size and Survival:
   - Passengers traveling alone had a higher chance of dying, while those traveling with larger families also had a higher chance of dying.

## Feature Engineering

1. Family Size:
   - Created a new column 'Family Size' by combining 'SibSp' (number of siblings/spouses) and 'Parch' (number of parents/children) columns.

2. Fare Correction:
   - Corrected the 'Fare' column to represent individual passenger fare instead of total family fare.

3. Family Type:
   - Derived a new categorical column 'Family Type' based on 'Family Size'.

## Files
- `titanic_analysis.ipynb`: Jupyter Notebook containing the code for data cleaning, feature engineering, and analysis.
- `old_titanic.csv`: Titanic dataset used for analysis.
- `new_titanic.csv`: Titanic dataset after creating new columns through Feature Engineering.

Feel free to explore the notebook for detailed analysis and insights!
