# project-brain_stroke
## Indroduction
Damage to the brain caused by a blood supply disruption. A stroke is an urgent medical matter. Stroke symptoms include paralysis or numbness of the face, arm, or leg, as well as difficulties with walking, speaking, and comprehending. Brain damage can be minimised with early therapy with drugs like tPA (clot buster). Other therapies concentrate on reducing side effects and averting more strokes.
## Objective
To predict the brain stroke of the persons based on attributes which are listed below
## Attributes
1) gender: "Male", "Female" or "Other"
2) age: age of the patient
3) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
4) heart disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease 5) ever-married: "No" or "Yes"
6) worktype: "children", "Govtjov", "Neverworked", "Private" or "Self-employed" 7) Residencetype: "Rural" or "Urban"
8) avgglucoselevel: average glucose level in blood
9) bmi: body mass index
10) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
11) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient
## Library
Numpy, Pandas, Matplotlib, Seaborn
## Methods
1. Random Forest Classifier
2. XGBoost Classifier
## Result
1. Accuracy Score from Random Forest Classifier is 94.78 %.
2. Accuracy Score from XGBoost Classifier is 94.88 %.
