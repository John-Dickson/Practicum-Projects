# Practicum Projects

These are the projects I completed during the course of my study at Practicum.

*   Gold Project:
    *   The project is complete, the code needs to be revised and cleaned up a little, but everything functions correctly.
    *   Add `clear_output(wait=True)` to the appropriate places in the code to make the output cleaner.
*   Final Project:
    *   ~The project is complete. The goal of the project was to achieve a AUC-ROC score of at least 0.85 on the machine learning model.~
    *   Add SHAP plots to the ML models to better understand them. 
    *   Do a sanity check where all 1 and 2 year contracts get marked non-churn and all no contract get marked as churn. > Done, ended up filling it with all 0s (non-churn) for 75% accuracy vs 85% for the best trained model. 
    *   Identify and plot histograms of churn vs non churn customers for the columns with the highest weights. 
    *   identify any high error groups, and test a ML model with just that group to understand the weights of that group. 
    *   What I expect to find is that the longer the customer is using the services, the less likely the model is to predict they will churn. This will likely leave 2 kinds of errors:
        *   New customers are likely to be predicted to churn even when they won't.
        *   Old customers will never be predicted to churn.
