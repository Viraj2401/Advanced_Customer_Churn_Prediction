# ADV-CUSTOMER_CHURN_PRED
This is our Computer Engineering final year Major Project.

Also made a POWER-BI dashboard for the same just to communnicate better with the stakeholders and make them visualize what we are actually talking about.

![Screenshot 2023-12-13 142247](https://github.com/Viraj2401/My-Projects/assets/151989127/cd48d41f-1178-4a78-9f98-5404cfaeb581)

We have used a Data Science & Machine Learning concepts to predict the likeliness of a customer to churn from the existing subscription.


![Architectural Design for Customer Churn Predictiom](https://github.com/Viraj2401/My-Projects/assets/151989127/2e768b50-890e-446e-b359-b792cf1a6f91)


This is a project where we initially use the data to perform EDA on the data that we got and run some analysis to find out the insights about how the customer behaviour works in terms of all the features that we got in the data like monthly cgarges, gender, dependables, internetservice, tenure etc..




This gave us a good amount of clarity on the set of customer features that were importatnt to us and ignore the rest ones.
Using the affecting features we split the data into train and test and trained models using various approaches like Decision Trees, Random Forest ect. We also used SMOTE-ENN for upsampling of the data as the data was highly imbalanced which made our score metrics more efficient and help us achieve acuuraciees like 94-95 %.


![95% accuracy model output](https://github.com/Viraj2401/My-Projects/assets/151989127/d7078e7f-d4e6-4473-8a35-0e1a08c6b2e2)



![Telco6](https://github.com/Viraj2401/My-Projects/assets/151989127/aec7d8c2-a42c-49d4-b760-3994e8bcb127)



We also tries using PCA for feature reduction and balancing the data but didn't give very exciting results.
Also explored SVM and Logistic Regression for the same data but saw a trend of commonness of using those earlier while reading research papers so tried ensemble with RF to explore new things and be unique.

