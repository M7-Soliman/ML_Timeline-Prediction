# Machine-Learning-Project
 
## Team
Mohamed Soliman Elhussiny, Armando Mendez, Will Xue, Danish Bokhari, Maddie Clubb 

## Problem Statement
The dataset we are going to use is from Imperial Marble and Granite, a countertop-installation business. The features we have available to us include: 'CONTRACTOR', 'CUSTOMER NAME', 'PO#', 'STONE COLOR', 'DATE INSTALLED', 'PLACE INSTALLED', 'SQFT', 'PROJECT COST', 'DEPOSIT', 'CHECK #', 'DATE CASH PAYMENT', 'FINAL PAYMENT CHECK#', 'DATE PENDING', 'PAYMENT DAYS OUTSTANDING', 'TOTAL PAID', and 'AFTER EXPENSES'. For this final project, we decided to build a model that predicts whether or not payment for a given job will be late – made more than 12 days after installation. In terms of the models we explored, we tested several classification algorithms and compared results to determine the best model for this problem. The algorithms we experimented with included SVM, Decision Tree, Random Forest, and Logistic Regression. The source of this data is the business itself since one of our groupmates is a relative of the business owner. The problem we are trying to solve is significant because family businesses need to be conscious of how much money they have available at a given time to put back into the business – thus, knowing when payments are likely to be late or on time is important in terms of the business’ financial decisions. There has been no previous attempt to solve this problem

## Results
Logistic regression performed the best across all metrics, with an accuracy, precision, recall, and F1 scores of 0.65. This shows that our model isn’t a good predictor of timeliness of payment for Imperial Marble and Granite. We think the low metrics are likely due to the lack of data. We only had around 1800 data points, while we had 10 features, likely causing our model to suffer from the curse of dimensionality. However, using less features also reduced our metrics, which suggests that in addition to not having sufficient data, there might not be any relationship between our features to begin with. Our feature selection analysis supports this, as accuracy did not increase or decrease significantly from removing features.


## 
As can be seen from our results above, the dataset that we had was not sufficient to classify payments as being late or not with more than about 65% accuracy. Although this is certainly better than random guessing, it is not exactly as high as we had initially hoped. Thus, if we were to revisit this problem in the future, we would hopefully have access to more data. Having additional features such as customer credit scores would have also been helpful as they are better predictors of timeliness of payments.
