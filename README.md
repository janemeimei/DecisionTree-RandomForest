# DecisionTree-RandomForest
Introdution of Project

In this project I will use lending data of Lending Club(the company connect people who need money with people who have money) from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full.

Summary of Project

I built a Decision Tree model with an accuracy of 73% and a Random Forest model with an accuracy of 85%, using numerical factors and transforming the categorical 'purpose' variable into multiple binary (boolean) features. Both models aimed to predict whether a borrower would fully repay their loan. However, both models suffer from class imbalance, where they predict well for the majority class (fully paid loans, class 0) but underperform on the minority class (not fully paid loans, class 1). To improve the prediction for class 1, techniques like SMOTE (Synthetic Minority Over-sampling Technique) or adjusting the class weights during model training could be applied to balance the dataset and enhance model performance for the minority class.
