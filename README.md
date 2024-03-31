# MACHINE_LEARNING
**diabetes prediction**
As Per the facts given by WHO(World Health Organization), there are about 422 million people worldwide who suffer from Diabetes, according to various studies done by WHO approximately 1.5 million deaths every year are directly related to diabetes. Indirectly Diabetes patients can have blindness, Kidney failures, heart attacks, stroke, etc. due to high sugar levels or imbalanced insulin levels. There are 2 types of diabetes: Type 1 Diabetes and Type 2 Diabetes. A common misconception might appear that Type 1 diabetes leads to Type 2 diabetes but both these types are different in nature. In reality, pre-diabetes can lead to either Type 1 Diabetes or Type 2 Diabetes.

The dataset mentioned contains data that divides patients into 3 categories (0 = no Diabetes; 1 = Pre-Diabetic; 2 = Diabetic)

The algorithms applied to the dataset do not differentiate the type of diabetes the patient might or might not have, it only predicts whether the person is diabetic or not (it may be of Type 1 or Type 2).

The Dataset contains 21 features along with 253679 entries which are analyzed to make predictions. The following features are taken into consideration.  
1.	HighBP
0 = no diabetes
1 = pre-diabetes
2 = diabetes

2.	HighChol	
0 = no high BP
1 = high BP

3.	CholCheck
0 = No high cholesterol
1 = High cholesterol	

4.	BMI	
Contains numeric values

5.	Smoker
If  a person has had at least 100 cigarettes in their life
0 = (<=) 100
1 = (>) 100 	

6.	Stroke
0 = no stroke
1 = has had a stroke	

7.	HeartDiseaseorAttack
0 = no heart disease
1 = has heart disease 	

8.	PhysActivity
Physical activity in the past 30 days
0 = no physical activity
1 = physical exercising was done

9.	Fruits
0 = consume no fruits in a day
1 = consume (>=) 1

10.	Veggies
0 = consume no vegetables in a day
1 = consume (>=) 1

11.	HvyAlcoholConsump
Heavy Alcohol consumption = (>=)14 drinks for men or (>=)7 drinks for women/ per week 
0 = if the above condition is False
1 = if the above condition is True	

12.	AnyHealthcare
0 = no insurance
1= has insurance	

13.	NoDocbcCost	
Could not see a doctor because of financial issues in the past year
0 = no 
1 = yes

14.	GenHlth
1 = excellent 
2 = very good 
3 = good 
4 = fair 
5 = poor	

15.	MentHlth
This includes stress, depression, and problems with emotions, for how many days during the past 30 days was the patient’s mental health not good?
-	This contains numerical values between 0-31	

16.	PhysHlth	
for how many days during the past 30 days was your physical health not good?
-	This contains numeric data between 0-31

17.	DiffWalk
0 = no difficulty in climbing stairs
1 = difficulty in climbing stairs	

18.	Sex	
0 = female 
1 = male

19.	Age
13-level age category 
1 = 18-24 
9 = 60-64 
13 = 80 or older

20.	Education	
Education level on a scale of 1-6 
1 = Never attended school or only kindergarten 
2 = Grades 1 through 8
3 = Grades 9 through 12
4 = college
5 = masters
6 = highly educated with multiple degrees

21.	Income
Income on a scale of 1-8 
1 = less than $10,000 
5 = less than $35,000 
8 = $75,000 or more

**The predicted column is Diabetes_012**
