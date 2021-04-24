# HELOC Credit Approval
This notebook is ispired by the [AIX360](https://aix360.mybluemix.net/) [HELOC Credit Approval Tutorial](https://github.com/gianluigilopardo/AIX360/blob/master/examples/tutorials/HELOC.ipynb), which shows different explainability methods for a credit approval process.
Here [XGBoost](https://github.com/dmlc/xgboost) is used for classification, achieving better accuracy than most of the models used in that notebook. Then, two feature importance methods are shown, to be compared with the *Data Scientist explanations* methods provided in the above notebook. The first one comes directly with XGBoost and the other is based on [SHAP](https://github.com/slundberg/shap).

The dataset is from the [FICO Explainable Machine Learning Challenge](https://community.fico.com/s/explainable-machine-learning-challenge) and it is about credit approval.
