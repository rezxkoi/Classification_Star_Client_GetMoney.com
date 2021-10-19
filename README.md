# covid19_sypmtoms_checker
Checking COVID-19 Symptoms using classification modeling  

The data will help to identify whether any person is having a coronavirus disease or not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO)who.int and the Ministry of Health and Family Welfare, India.

Disclaimer: The results or analysis of these data should be taken as medical advice.

The dataset contains seven major variables that will be having an impact on whether someone has coronavirus disease or not, the description of each variable are as follows,

Country: List of countries person visited.
Age: Classification of the age group for each person, based on WHO Age Group Standard
Symptoms: According to WHO, 5 are major symptoms of COVID-19, Fever, Tiredness, Difficulty in breathing, Dry cough, and sore throat.
Experience any other symptoms: Pains, Nasal Congestion, Runny Nose, Diarrhea and Other.
Severity: The level of severity, Mild, Moderate, Severe
Contact: Has the person contacted some other COVID-19 Patient

With all these categorical variables, a combination for each label in the variable will be generated and therefore, in total 316800 combinations are created.

Data: There are two CSV files uploaded,

Raw-Data: This file contains all the possible labels of variables, this file is used to generate the cleaned data.
Cleaned-Data: This file contains all possible combinations of data from Raw-Data.csv, can be used for analysis. Contains dummy variables after combination, can refer the notebook, for how this data is generated.
Application of the combined data:

Supervised Learning (Classification)

Future Work:

Getting more guidelines from WHO to elaborate more data
Applying Reinforcement Learning in the data
