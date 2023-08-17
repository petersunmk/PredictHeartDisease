# Prediction of  Heart Disease  in Classification   

1. Build machine learning classification models to predict whether someone has heart disease based on medical attributes.  

2. Leverage Models include Logistic Regression, K-Nearest Neighbors Classifier, and Random Forest Classifier to reach the highest accuracy in prediction
3. 
4. Conclusion: Highest 93f% accuracy rate is a tuned machine learning classifier by GridSearchCV AUC Score.

<img width="576" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/4ebbe0f2-f489-40cb-a1ac-12641a6e669b">


 > To predict whether someone has heart disease based on their medical attributes
    
    1. Problem Definition
    2. Data
    3. Evaluation
    4. Features
    5. Modelling
    6. Experimentation
    
## 1. Problem Definition

  >  Given clinical parameter about a patient, can we predict whether or not they have heart disease?

## 2. Data

    The original data came from the Cleavland data from UCI Machine Learning Repository.
    https://archive.ics.uci.edu/dataset/45/heart+disease
<img width="655" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/3f5ca127-9486-4636-a992-4398143a7579">


## 3. Evaluation
  
  > Try to reach 95% or highest accuracy at predicting whether or not a patient has heart disease

  
## 4. Features

> Heart Disease Dictionary:
  
1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type.  
     0: Typical angina: chest pain related decrease blood supply to the heart  
     1: Atypical angina: chest pain not related to heart  
     2: Non-anginal pain: typically esophageal spasms (non heart related)  
     3: Asymptomatic: chest pain not showing signs of disease
4. trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5. chol - serum cholestoral in mg/dl  
   above 200 is cause for concern  
   serum = LDL + HDL + .2 * triglycerides

6. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
   '>126' mg/dL signals diabetes
7. restecg - resting electrocardiographic results  
     0: Nothing to note  
     1: ST-T Wave abnormality  
     can range from mild symptoms to severe problem  
     signals non-normal heart beat  
     2: Possible or definite left ventricular hypertrophy  
     Enlarged heart's main pumping chamber
8. thalach - maximum heart rate achieved
9. exang - exercise induced angina (1 = yes; 0 = no)
10. oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
11. slope - the slope of the peak exercise ST segment  
    0: Upsloping: better heart rate with excercise (uncommon)  
    1: Flatsloping: minimal change (typical healthy heart)  
    2: Downslopins: signs of unhealthy heart  
12. ca - number of major vessels (0-3) colored by flourosopy  
    colored vessel means the doctor can see the blood passing through  
    the more blood movement the better (no clots)
13. thal - thalium stress result  
    1,3: normal  
    6: fixed defect: used to be defect but ok now  
    7: reversable defect: no proper blood movement when excercising
14. target - have disease or not (1=yes, 0=no) (= the predicted attribute)
<img width="861" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/7786cc5c-3c2f-4001-9567-7c17b6be8b38">

<img width="861" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/6e9b597e-4bfe-4db5-93b9-c94bc4add1a9">
<img width="878" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/f3dd9868-91b1-45da-9f49-8c77c4775710">
<img width="983" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/1ad2a7ea-cc51-46d3-91fc-55cc73b36088">

## 5. Modeling
Try 3 different machine learning models:
1. Logistic Regression
2. K-Nearest Neighbors Classifier
3. Random Forest Classifier
<img width="551" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/0f7b8be2-488a-4101-a3db-7d93c1aa149f">

<img width="592" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/a5e5fad2-3904-4044-b007-694447edbf2c">

<img width="585" alt="image" src="https://github.com/petersunmk/PredictHeartDisease/assets/90821383/4a606e9f-6ea5-4aac-b36b-2da82fb936c9">

## 6. Experimentation

   Furether to do : Try a better/ other model, Like XGBoost
