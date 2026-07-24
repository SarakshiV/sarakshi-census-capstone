# sarakshi-census-capstone

CONCLUSION

1. Project Title: Education, Income, and Opportunity in the 1994 U.S. Workforce
This title explains that our project focuses on how education may be connected to income and financial opportunities. It also makes clear that the data represents the workforce in 1994.

2. One-Sentence Summary: 
I used 1994 U.S. Census data to build models that predict whether an adult earns more than $50,000 per year and tested whether the results were equally accurate for males and females.

3. The Problem:
People do not always have equal access to education, job training, or higher-paying careers. This matters because adults with fewer opportunities may have lower incomes and less financial stability, which can cause economic inequality to continue.

4. The Data:
I used the UCI Adult Census Income dataset, which originally had 32,561 rows and 15 columns. During my analysis, I found hidden missing values marked with question marks, duplicate rows, and a large difference between the number of people earning above and below $50,000.

5. What We Did: 
We cleaned the dataset by fixing missing values, removing duplicates, and preparing the categories for machine learning. We trained several models to predict whether someone earned more than $50,000 and compared them using accuracy, precision, recall, and F1 score.

6. What We Found:
Gradient Boosting was our best overall model, with an accuracy of 83.66% and an F1 score of 60.21%. However, its recall was only 48.33%, meaning it correctly identified fewer than half of the people who actually earned more than $50,000.

7. Fairness Check:
The model had 79.3% accuracy for males and 89.6% accuracy for females, which is a difference of 10.3 percentage points. Recall was much closer at 46.4% for males and 45.9% for females, but the accuracy gap shows that the model did not perform equally well for both groups.

8. Limits and What’s Next:
The dataset comes from 1994, so it does not represent today’s wages, cost of living, technology, remote work, or gig economy. With more time, we would use newer data, test more demographic groups, and adjust the model to improve recall without creating too many incorrect predictions.

9. How to Run It:
Open the Google Colab notebook and upload the Adult Census Income dataset if it is not already there. Then click “Runtime” and select “Run all” to run every part of the project from beginning to end.

10. Team and Roles:
The members of this project were Sarakshi, Misheeta, Nisha, and Simran. We worked together on cleaning the data, creating visualizations, building and comparing machine learning models, checking fairness, and writing the final conclusions.
