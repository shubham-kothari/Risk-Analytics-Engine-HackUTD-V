# HackUTD2019

Problem Statement given by Fannie Mae for Risk Analytics.

We provide our approach to find if the mortgage comes with Moderate, High or No Risk associated with it.

The solution predicts the possible 3 categories a loan may be associated with and the best results are:

### High-Risk Loans
**93% Precision and 96% Recall**

### Moderate Risk Loans
**93% Precision and 93% Recall**

### No Risk Loans
**91% Precision and 83% Recall**

We wanted to use Area Under ROC and Area Under PRC as metrics but they are not suitable for multiclass classification problems and due to the limited time we used F1-Score which is a weighted score of PRECISION and RECALL.

For more details and **Exploratory Data Analysis**: https://utdallas.box.com/s/afh0zw1uyloffp1x2gre2ejbtb2tky7p 
