# HeartDiseasePrediction-MiniProject.

In this notebook , the goal is to build a model that can predict the probability of heart disease occurrence, based on a combination of features that describes the disease. Database used in this project is collected from Kaggle (https://www.kaggle.com/ronitf/heart-disease-uci). In order to achieve the goal, I have performed following :- 

•	Data   – Finding Missing values, Duplicate Values or any Outliers<br>
•	Exploratory data analysis – Finding correlation between features and label, graphical representation of the data. <br>
•	Machine learning Algorithm-  Logistic Regression , Decision Tree Classifier, Random Forest Classifier.<br>
•	Evaluation of the model – Confusion Matrix<br>

  Features Information: <br>

The dataset consists of 303 individuals data. There are 14 columns in the dataset, which are described below.<br>
1.	age - age in years
2.	sex - (1 = male; 0 = female)
3.	cp - chest pain type
a.	0: Typical angina: chest pain related decrease blood supply to the heart
b.	: Atypical angina: chest pain not related to heart
c.	2: Non-anginal pain: typically esophageal spasms (non heart related)
d.	3: Asymptomatic: chest pain not showing signs of disease
4.	trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5.	chol - serum cholestoral in mg/dl serum = LDL + HDL + .2 * triglycerides above 200 is cause for concern
6.	fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) '>126' mg/dL signals diabetes
7.	restecg - resting electrocardiographic results
a.	0: Nothing to note
b.	1: ST-T Wave abnormality can range from mild symptoms to severe problem signals non-normal heart beat
c.	2: Possible or definite left ventricular hypertrophy enlarged heart's main pumping chamber
8.	thalach - maximum heart rate achieved
9.	exang - exercise induced angina (1 = yes; 0 = no)
10.	oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
11.	slope - the slope of the peak exercise ST segment
a.	0: Upsloping: better heart rate with excercise (uncommon)
b.	1: Flatsloping: minimal change (typical healthy heart)
c.	2: Downslopins: signs of unhealthy heart
12.	ca - number of major vessels (0-3) colored by flourosopy
13.	colored vessel means the doctor can see the blood passing through the more blood movement the better (no clots)
14.	thal - thalium stress result
a.	1,3: normal
b.	6: fixed defect: used to be defect but ok now
c.	7: reversable defect: no proper blood movement when excercising
15.	target - have disease or not (1=yes, 0=no) (= the predicted attribute)
