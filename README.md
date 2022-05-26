# Thyroid-Disease-Analysis
This project is done using thyroid disease dataset taken from UCL Machine Learning Repository.

Dataset Description/Attribute Information:
age - age of the patient (int)
sex - sex patient identifies (str)
on_thyroxine - whether patient is on thyroxine (bool)
query on thyroxine - *whether patient is on thyroxine (bool)
on antithyroid meds - whether patient is on antithyroid meds (bool)
sick - whether patient is sick (bool)
pregnant - whether patient is pregnant (bool)
thyroid_surgery - whether patient has undergone thyroid surgery (bool)
I131_treatment - whether patient is undergoing I131 treatment (bool)
query_hypothyroid - whether patient believes they have hypothyroid (bool)
query_hyperthyroid - whether patient believes they have hyperthyroid (bool)
lithium - whether patient * lithium (bool)
goitre - whether patient has goitre (bool)
tumor - whether patient has tumor (bool)
hypopituitary - whether patient * hyperpituitary gland (float)
psych - whether patient * psych (bool)
TSH_measured - whether TSH was measured in the blood (bool)
TSH - TSH level in blood from lab work (float)
T3_measured - whether T3 was measured in the blood (bool)
T3 - T3 level in blood from lab work (float)
TT4_measured - whether TT4 was measured in the blood (bool)
TT4 - TT4 level in blood from lab work (float)
T4U_measured - whether T4U was measured in the blood (bool)
T4U - T4U level in blood from lab work (float)
FTI_measured - whether FTI was measured in the blood (bool)
FTI - FTI level in blood from lab work (float)
TBG_measured - whether TBG was measured in the blood (bool)
TBG - TBG level in blood from lab work (float)
referral_source - (str)
patient_id - unique id of the patient (str)
target_hyper - hyperthyroidism medical diagnosis (str)
target_hypo - hypothyroidism medical diagnosis (str)
target_bp - binding protein medical diagnosis (str)
target_rep - type of replacement therapy ongoing (str)
target_sick - whether patient is sick or not (str)

This dataset has a lot of attributes and it requires huge amount of preprocessing and cleaning.
The ultimate aim to predict whether a patient is sick of thyroid or not. So it comes down to a binary classification problem.
The ML models used for classification are LogisticRegression, RandomForestClassfier, Support Vector Classifier , Gradient Boosting Classifier, Ada Boosting Classifer and XG Boosting Classifier.
