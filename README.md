# Titanic-EDA
Exploratory Data Analysis on Titanic Dataset
Objective of the Project
To uncover key factors influencing passenger survival, this project aims to perform comprehensive and in-depth exploratory data analysis (EDA) on the Titanic dataset, leaving no stone unturned. Using various data visualization techniques, this analysis aims to:

1. Understand Passenger Demographics – Analyze the distribution of age, gender, and class among the passengers.
2. Identify Survival Trends– Determine how class, gender, and fare prices influenced survival chances.
3. Explore Socioeconomic Disparities – Examine how social status was critical in access to lifeboats and safety.
4. Visualize Patterns and Correlations – Use statistical and graphical methods to showcase relationships between variables.
5. Enhance Data Storytelling– Present the findings in a compelling narrative format that transforms raw data into meaningful insights.

This project aims to provide a statistical understanding of the Titanic disaster. More importantly, it highlights broader societal themes of privilege, vulnerability, and survival dynamics, thereby contributing to a deeper understanding of the historical event.

General Overview of the Titanic Dataset
The dataset contained information about 891 passengers, with 12 key features, including:
Demographics (Age, Sex, Embarked)
Travel Information (Pclass, Ticket, Fare, Cabin)
Family Relations (SibSp, Parch)
Survival Status (0 = Not Survived, 1 = Survived)
Missing values were found in Age, Embarked, and Cabin, and we handled them by imputing median and mode values. Unnecessary columns like Ticket, Name, and Cabin were dropped.
________________________________________
 Key Insights from Visualizations
(a) Survival Rate
🔹 38.4% of passengers survived, while 61.6% perished (from the pie chart).
🔹 This shows that more than half of the people did not survive the Titanic disaster.
________________________________________
(b) Gender and Survival
🔹 Females had a significantly higher survival rate than males.
🔹 About 74% of women survived, compared to only 18% of men.
🔹 This confirms the historical "Women and Children First" policy during the evacuation.
 Insight: If you were a female passenger, your chances of survival were much higher.
________________________________________
(c) Passenger Class and Survival
🔹 1st-class passengers had the highest survival rate (~63%),
🔹 2nd-class passengers had a moderate survival rate (~48%),
🔹 3rd-class passengers had the lowest survival rate (~25%).
 Insight: Wealthier passengers (1st-class) had better survival chances.
This suggests that social status played a role in evacuation priorities.
________________________________________
(d) Age and Survival
🔹 Children (aged <10) had higher survival rates, likely due to the "Women and Children First" rule.
🔹 Older passengers (>50) had lower survival rates, possibly because of slower mobility.
🔹 Most passengers were aged 20-40 years.
 Insight: Younger passengers were prioritized for survival.
________________________________________
(e) Family Size and Survival
🔹 Passengers traveling alone had a lower survival rate.
🔹 Those with 1-3 family members had better survival chances.
🔹 Large families (≥4 members) had lower survival rates, possibly due to difficulty evacuating together.
 Insight: Being with family improved survival chances, but too large a family could be a disadvantage.
________________________________________
(f) Ticket Fare and Survival
🔹 Higher ticket fares were strongly associated with survival.
🔹 People who paid more (first-class passengers) were more likely to survive.
 Insight: Paying for a higher-class ticket increased survival chances.
________________________________________
(g) Embarkation Port and Survival
🔹 Passengers who boarded from Cherbourg (C) had the highest survival rate (~55%).
🔹 Passengers from Southampton (S) had the lowest survival rate (~34%).
 Insight: The embarkation port played a minor role, but wealthier passengers (who had higher survival rates) often boarded from Cherbourg.
________________________________________
(h) Correlation Between Features
🔹 Strongest correlation:
Fare and Pclass (-0.55) → First-class passengers paid higher fares.
Survival and Sex (0.54) → Being female increased survival chances.
Survival and Pclass (-0.34) → Higher class increased survival.
 Insight: Gender, class, and fare were the most important survival factors.
________________________________________
Final Conclusion
Who Had the Best Chance of Survival?
Female passengers, especially those in 1st class.
Children (<10 years old).
Passengers who paid higher fares (wealthier individuals).
People who traveled in small family groups (1-3 members).
Who Had the Lowest Chance of Survival?
Male passengers, especially in 3rd class.
Passengers traveling alone.
Older passengers (aged >50).
Passengers who boarded from Southampton.
Final Takeaway 
This code uses the Titanic dataset to tell a compelling story about the factors influencing passenger survival. Through a series of visualizations, it uncovers patterns and insights within the data, transforming raw numbers into a narrative that resonates with the audience, highlighting social dynamics, privilege, and vulnerability aboard the ill-fated ship.

