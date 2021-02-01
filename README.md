# Heart-Failure-Prediction
Create a model to assess the likelihood of a death by heart failure event. This can be used to help hospitals in assessing the severity of patients with cardiovascular diseases.


Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide. Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

# Dataset Link
  [download](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data)


## Dataset Description
 
 Feature | Explanation | Measurement	| Range
------------- | ------------- |------------- | -------------
Age	|Age of the patient	|Years |	[40,..., 95]
Anaemia	|Decrease of red <br> blood cells or hemoglobin |	Boolean|	0, 1
High blood pressure |	If a patient has hypertension |	Boolean	 |0, 1
Creatinine phosphokinase<br>(CPK) |	Level of the CPK enzyme <br>in the blood |	mcg/L|	[23,..., 7861]
Diabetes|	If the patient has diabetes |	Boolean	| 0, 1
Ejection fraction|	Percentage of blood leaving<br>the heart at each contraction|Percentage	|	[14,..., 80]
Sex	| Woman or man |	Binary|	0, 1
Platelets|	Platelets in the blood|	kiloplatelets/mL|	[25.01,..., 850.00]
Serum creatinine|	Level of creatinine in the blood|	mg/dL|	[0.50,..., 9.40]
Serum sodium|	Level of sodium in the blood|	mEq/L|	[114,..., 148]
Smoking|	If the patient smokes|	Boolean	|0, 1
Time|	Follow-up period|	Days|	[4,...,285]
DEATH EVENT<br>(TARGET)|	If the patient died during the follow-up period|	Boolean|	0, 1


## Model Performance :
![1](https://user-images.githubusercontent.com/29980448/106421132-30ab7080-6482-11eb-8051-964552628274.png)

## Conclusion:
- **43% of the population under study have aneamic symptoms while ~57% are non-aneamic.**
- **42% of the population have diabetes while ~58% don't have non-diabetes.**
- **35% of the population have hypertension or high bloob pressure while ~65% have normal blood pressure.**
- **65% of the population are male while ~35% are female.**
- **68% of the population have smoking habits while ~32% are non-smokers.**
- **In the population being studied for the condition of heart failure out of the 299 cases, 96 have succumbed to the condition while 203 cases survived.**

- **In percentages, 32.11% of the cases succumbed (positive examples) while 67.89% cases survived (negative examples) the condition.**

 
- **After training our dataset with seven different model, we conclude that __RandomForest__  is best model for our dataset. (via the highest accuracy score = 0.90)**



