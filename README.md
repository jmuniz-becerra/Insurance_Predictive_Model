# Insurance_Predictive_Model
Creation of a multi-variate regression model to predict medical charges incurred by the insuree.

It's critical for an insurance company to be able to assess risk when onboarding a new insuree. Granted life is unpredictable, here I sought to create a regression model to try and predict the cost of bringing on a new insuree.

To do so, I utlized the following features: age, gender, bmi, # of children, smoker, and region of the U.S. where insuree is from. I converted categorical information (gender, smoker y/n, region of residence) via 'LabelEncoder' from sklearn into numerical values for incorporation in analysis, and I utilized the LinearRegression module from sklearn to input features to predict price of medical charges. 

In addition, data exploration was done to get a better understanding of the demographics of the insurees. The median age, median amount in medical charges, frequency of region of residence within the U.S., insight on average bmi, age and # of children were used for data exploration. The constructred report for data visualization can be found in the list of files for this repository, and the purpose of this report is to serve as a 

**** NOTE **** 

Granted this dataset is modest in size (1300+ rows) and supplied by Kaggle, here I intend to improve my skill and work towards competency in data exploration, organization, and preparation for machine learning analysis.

Future direction can be found in future direction section at the end of this README file.

**** END OF NOTE ****



**** FUTURE DIRECTION ****

An obvious point of future direction is to continue the retreival of data for continous analysis.



**** END OF FUTURE DIRECTION ****
