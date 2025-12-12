# eda
This project focuses on a comprehensive Exploratory Data Analysis (EDA) pipeline to clean and structure housing data, laying a robust foundation for subsequent price prediction using regression models.
## Key Analytical Objectives
Data Integrity: Systematically handling data quality issues to ensure unbiased model training.
Feature Selection: Identifying the strongest predictive features for housing prices.
Insight Generation: Translating statistical findings into clear, actionable conclusions.
## Core Methodologies
Data Preprocessing:
Skewness Correction: Diagnosed features (like Price and Crime Rate) for high skewness using KDE Plots and applied Logarithmic Transformations for normalization.
Outlier Management: Identified and handled extreme outliers to prevent model distortion.
Correlation Analysis: Investigated relationships between variables, such as the clear positive correlation between Room Number and Price and the strong negative correlation between Price and Crime Rate.
## Key Findings / Results 
![WhatsApp Image 2025-12-12 at 10 10 32 PM](https://github.com/user-attachments/assets/5509b5d9-32a6-40c1-986b-a4d17b65860d)
![WhatsApp Image 2025-12-12 at 10 10 42 PM](https://github.com/user-attachments/assets/295c8d0a-295c-462e-a282-717c3e3d45e5)
Conclusion: Location, Living Area, and Room Count were confirmed as the primary drivers of housing value.
## Technologies Used
Python | Pandas | NumPy | Matplotlib / Seaborn | Scikit-learn (Implied for modeling)
