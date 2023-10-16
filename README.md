# Decision tree classifier and Overfitting
The goal of this notebook is to learn how overfitting works using the decision tree classifier model. I like decision trees because they are easier to understand than most other machine learning or statistical learning methods.

# Below we have a brief description of what each of the features we are going to use mean. The numbers next to the features are the ones that were used in the original dataset.

[1] #3 Age: age in years
[2] #4 Sex: sex (1 = male; 0 = female)
[3] #9 Chest_pain_type
Value 1: typical angina
Value 2: atypical angina
Value 3: non-anginal pain
Value 4: asymptomatic
[4] #10 At_rest_bp: resting blood pressure (in mm Hg on admission to the hospital)
[5] #12 Cholesterol: serum cholestoral in mg/dl
[6] #16 Fast_blood_sug: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
[7] #19 Rest_ecg: resting electrocardiographic results
Value 0: normal
Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
[8] #32 Maxhr: thalach: maximum heart rate achieved
[9] #38 Exer_angina: exang: exercise induced angina (1 = yes; 0 = no)
[10] #40 Oldpeak: ST depression induced by exercise relative to rest
[11] #41 Slope: the slope of the peak exercise ST segment
Value 1: upsloping
Value 2: flat
Value 3: downsloping
[12] #44 Ca: number of major vessels (0-3) colored by flourosopy
[13] #51 Thal: Thallium or stress test 3 = normal; 6 = fixed defect; 7 = reversable defect. See this website for more info on the thallium or stress test.
[14] #58 Diag: num: diagnosis of heart disease (angiographic disease status)
Value 0: no vessel with 50% diameter narrowing
Value 1: one vessel with 50% diameter narrowing
Value 2,3,4: 2,3,4 vessels with 50% diameter narrowing
