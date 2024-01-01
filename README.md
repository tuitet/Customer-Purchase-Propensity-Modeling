# Customer Purchase Propensity Modeling

## Summary
**Goal**: The goal of this project is to predict the likelihood that a customer will purchase a certain product based on underlying factors. This would improve the customer acquisition strategy of a certain Fortune 500 company.

**Background**: This is a consulting project for a Fortune 500 company via Georgia Tech's Masters in Analytics practicum. For privacy reasons, the data is not included and the results are masked. 

**Dataset**: This Fortune 500 company provided a dataset of past customer purchases, along with the customer's attributes and past purchase behaviors. 

**Approach**: We created a data pipeline to cleanse, feature engineer, model, and score 10 classification models and choose the best model based on test ROC AUC and F2 scores.

**Results**: 
- Based on much experimentation, a random forest model perfomed the best with a Test ROC AUC of 85%. This model was used to predict customer prediction probabilities on an unseen dataset, which was provided to the client as a final deliverable.


## Key skills being practiced in this project
This project tested several key skills for a data practitioner, including:  
- **Data Cleaning and Modeling Pipeline Usage**: Because this work was being shared with the client for their future use, it was important to write clean, easily readable code which could be reused or modified if desired. Creating a clean data pipeline to do all data wrangling, feature engineering, modeling, and scoring steps was beneficial to the client. 
- **Customer Relationship Management**: Throughout this project, we worked with the client to ensure requirements were understood and deliverables were aligned with expectations. A clean, organized code package along with a written summary and recommendation was provided to the customer to provide business value and improve their customer acquisition strategy.  
