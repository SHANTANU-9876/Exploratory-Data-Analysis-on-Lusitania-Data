# Exploratory-Data-Analysis-on-Lusitania-Data
Objective:
The goal of this project is to extract meaningful insights from the Lusitania passenger and crew data using statistical and visual exploration techniques. The focus is on identifying patterns related to age, gender, city, passenger role (crew/passenger), and survival status.

Tools & Libraries Used:
Python:

- Pandas for data manipulation
- Matplotlib and Seaborn for visualizations
- Jupyter Notebook for development and presentation

Data Cleaning & Preprocessing:
- Unnecessary columns were dropped to simplify the dataset.
- Categorical columns like Sex, Fate, and Passenger/Crew were standardized for consistency.
- Null or missing values in the Age column were handled using .dropna() during visualizations.
- An Age Group feature was engineered to classify passengers into Child, Teen, Adult, and Senior.
- The City column was retained to analyze survival distribution across geographical regions.

Exploratory Data Analysis (EDA):
1. Age Distribution (Histogram & KDE)
Revealed most passengers were between 20-40 years.

A smooth kernel density estimation showed age density variations.

2. Age vs Fate (Boxplot)
Survivors generally had a wider age range.

Mean and median ages of survivors were slightly lower than non-survivors.

3. Survival by Sex (Countplot)
Males outnumbered females in the manifest.

Survival rate among females appeared relatively higher proportionally.

4. Survival by Role (Passenger/Crew)
Crew members had a higher fatality rate.

Passengers were more likely to survive than crew, suggesting priority during evacuation.

5. Survival by Age Group
Adults made up the majority.

Children and seniors had a lower representation and survival varied significantly across groups.

6. Survival by City (Top 10 Cities)
Visualized geographic representation and survival trends by the most frequent cities.

Some cities had relatively higher survivor counts, indicating possible regional or socio-economic influence.

7. Correlation Heatmap
As Age was the only numeric column, correlation was minimal but provided a foundation for further statistical modeling.

Key Insights & Observations:
- Age and role (Passenger/Crew) had significant influence on survival.

- Females had a higher proportional survival rate.

- Geography (City) hinted at patterns that could be further explored.

- Data visualization helped uncover subtle trends and enhanced understanding beyond raw statistics.
