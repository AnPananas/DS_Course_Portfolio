
# Skills and libraries:

Pandas, sklearn, matplotlib

# Project Description

Customers began to leave Beta Bank. Every month. A little, but noticeable. Bank marketers have found that it is cheaper to retain current customers than to attract new ones.
You are presented with historical data on the behavior of customers and the termination of contracts with the bank.

Источник данных: (https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

# The purpose of the study

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.

Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.

# Data description 

Signs
- RowNumber — index of the row in the data
- CustomerID — unique identifier of the customer
- Surname — surname
- CreditScore — credit rating
- Geography — country of residence
- Gender — gender
- Age — age
- Tenure — how many years has a person been a customer of the bank
- Balance — account balance
- NumOfProducts — the number of bank products used by the customer
- HasCrCard — availability of a credit card
- IsActiveMember — client activity
- EstimatedSalary — estimated salary

Target attribute
- Exited — the fact of the client's departure

# General conclusion


During the study, data were prepared and three models were tested: Logistic Regression, Random Forest and Decision Tree. The studies were conducted for unbalanced and balanced samples, then the best model was selected, on which control testing was done. Additionally, the auc_roc metric was introduced, which shows the ratio of completeness and accuracy of the model.

The best indicator after balancing classes was shown by a random forest model with the value of F1-measure = 0.6, the value of AUC-ROC =0.74

F1-the measure is greater than 0.59 - the task is completed.
