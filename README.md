# ReneWind_Classification_with_ImbalancedData_OverSampling_UnderSampling

Objective:
● ReneWind is a company working on improving the machinery/processes involved in the production of
wind energy using machine learning and has collected data of generator failure of wind turbines using
sensors.
● The objective is to build various classification models, tune them, and find the best one that will help
identify failures so that the generators could be repaired before failing/breaking to reduce the overall
maintenance cost.

● The nature of predictions made by the classification model will translate as follows:
○ True positives (TP) are failures correctly predicted by the model. These will result in repairing costs.
○ False negatives (FN) are real failures where there is no detection by the model. These will result in replacement
costs.
○ False positives (FP) are detections where there is no failure. These will result in inspection costs.
● It is given that the cost of repairing a generator is much less than the cost of replacing it, and the cost
of inspection is less than the cost of repair

Data Overview
● The data shared is a ciphered version containing 20000 observations in the train set and 5000 in the 
test set
● The number of features provided is 40 but the data is ciphered hence, the column names are 
anonymous 
● 2 columns have missing values.
● 94.5% of the observations are negative and only 5.5% observations are a positive representing
failure. The dataset is highly imbalanced so we tried undersampling and oversampling techniques to
balance the data.
