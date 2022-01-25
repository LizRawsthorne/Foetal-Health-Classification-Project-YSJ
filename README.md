# Foetal-Health-Classification-Project-YSJ
### Background
Approximately 830 (Guardian, 2018)  women die each year during childbirth because of complications arising from the pregnancy and 3.3 million babies are still born (WHO, 2011). Globally, medical domains should be equipped with the necessary resources to support, monitor, and anticipate foetal risk to improve the care and safety of the mother and baby. Cardiotocography (CTG) is used to assess the well-being of the foetus and can therefore combat fatal implications such as premature births and breeched babies. 
### Aim
This study will focus on a machine learning approach to optimise and interpret the CTG data to help automate manual, labour-intensive health care processes and contribute to reducing maternal and foetal death rates. 
### Methods
In this study 10 different classification algorithms are trained to classify and predict the health of a foetus to be Normal, Suspect or Pathological. To determine the best performing model, I observe the F1 score and implement hyperparameter tuning, feature selection and resampling to optimise model performance.      
### Results
Before feature engineering the XGBoost classifier performed the best with a test F1 score of 0.92, closely followed by Gradient Boosting Classifier and Random Forest producing a 0.91 and 0.90 F1 score respectively. After hyperparameter tuning the F1 score of the Random Forest and XGBoost classifiers increased to 0.99. 
### Conclusion
After further exploration with classifiers, I implemented a stacking classifier. This improved the precision, recall and F1 scores marginally. However, I believe more data and features are required to industrialise this approach and ethical implications should be considered. 
