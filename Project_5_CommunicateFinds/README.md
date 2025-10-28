# (Prosper Loan Data Exploration and Analysis)
## by (Thiresh Lodaya)

In this case-study of Loan Data from the exploration to presentation phase have tried to extract useful features in deciding the credit worthiness of a loan borrower. I have tried to use all the Data Analysis tools learned during the course into this use-case.

## Dataset

The Dataset contains 113937 loans with 81 characteristics of those loan. The dataset contains many numerical and categorical features to explore on visual assesing on the .csv file.The dataset contains 84853 loan listing cleaned from 113937 from data of Proster Company.The dataset contains most numeric data, but also categorial data and datetime object as well.In this investigation, we explore a dataset containing information about various loans offered by Prosper. The dataset includes a wide range of features related to loan terms, borrower information, loan status, and Prosper ratings.


## Summary of Findings
 Our primary focus is to analyze the factors that might contribute to loan defaults and gain insights into the relationships between different features and loan outcomes.

- The distribution of Prosper ratings appears to be relatively normal, with a majority of borrowers falling within the mid-range ratings. On the other hand, the distribution of monthly stated income is highly varied
- There is a noticeable trend where defaulted credits are more frequently associated with individuals who have lower Prosper ratings. Specifically, borrowers with ratings of D are the most common among those with defaulted credits.
- Long-term loans (60 months) are generally riskier than short-term loans (12 months).
- When examining employment status, individuals with lower Prosper ratings are more likely to be associated with statuses such as "Not employed," "Self-employed," "Retired," or "Part-time." This indicates that borrowers with lower ratings may have less stable or secure employment.

Overall, the analysis suggests that Prosper ratings, borrower rates, and loan amounts are significant factors in predicting loan defaults. Borrowers with lower credit ratings, higher borrower rates, and larger loan amounts may be more prone to defaulting on their loans. Additionally, certain loan purposes and employment statuses are associated with higher default risks, highlighting the importance of these variables in credit risk assessment.

## Key Insights for Presentation

Data Wrangling, Exploratory and Explantory Analysis are showcased in the presentation.
How salary of loan borrowers in wide range and using z-score method the outliers are removed. Furthermore only taking into consideration the completed, defaulted and chargedoff Loan status into the analysis and replacing the chargedoff to defaulted using function from python.

ProsperRating, loan borrower's listing categories and employement status helps in predicting the reason and features behind a loan turing to a default.The Employement status of the loan borrowers, not judging but shows bit uncertain financial situation which could be driving reason for the loan default.

ProsperRating 'AA', 'A' and 'B' have got huge credits for loan based on the borrowerRate relation and so are the default credit. As mentioned in previous point, based on employement status the loan was defaulted but loan borrowers belonging to that category do not get huge amount of credit which concludes that the total credit defaulted in big in higher ProsperRatings.