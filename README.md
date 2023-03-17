## Background Knowledge
**Heart Disease, aka Cardiovascular Disease are a group of conditions that affects the Heart and Blood vessels. The conditions can be Coronary artery Disease, heart failure etc.**

**The Coronary artery Disease is the most common type of Heart disease and its caused by the build up of plaques in the arteries that supply blood to the heart. This kind of discomfort is known as Angina and can result to Heart Attack if the flow of Blood to the Heart is blocked completely.**

**Generally, heart failure happens when the heart is unable to pump blood effectively throughout the body, which can lead to symptoms like Shortness of Breath, Fatigue, swelling in the leg or ankles.**

**The risk factors of Heart Disease include High Blood Pressure, High Cholesterol, Smoking, Diabetes, Obesity, sedentary lifestyle and Family history of Heart Disease.**

**Preventive and management measures of heart Disease are Healthy Diet, Regular Exercise, weight and stress management as well as medications and medical procedures.**

**In conclusion, I developed a Machine Learning Model to Predict whether or not a person has Hypertension or not using Medical Conditions like Chest pain Type, Resting Blood Pressure, Fasting Blood Sugar, Resting Electrocardiographic results etc. and other features of a person like Age and Sex.**

**I first explored the preprocessed data by removing missing values, transforming categorical features to numerical and lastly.**

**Then, I visualized and the following are the trends I discovered**
1. **The Males are more prone to Heart diseases than the females**
2. **Patients with asympt (asymptomatic) chestpain are more prone to Heart diseases and patients with abnang (atypical angina) are less likely to have this attack.**
3. **The abn (abnormal) Resting Electrocardiographic results is rare to find in most Patients...**
4. **Patients with Normal thal are mostly safe from Heart attacks**
5. **Average individuals from age 25-40 have higher chances of being affected by heart problems.**
6. **Old patients from 55 downwards have higher chances of getting heart attacks...**

**I scaled the non-categorical features to make all values be in the same range**

**Then, I trained and evaluated several models like Logistic Regression, Supported Vector Classifier, Decision Tree Classifier, Random Forest Classifier using Cross Validation to obtain Average Accuracies of the different Models.** 

**Based on the Average Accuracy scores, I selected Random Forest Classifier as the best performing Model with an average Cross Val Score of 82.77 an accuracy of 100%.**
**Finally, I plotted an Heatmap using the Seaborn Module to show the Confusion Matrix of the prredictions.**
**The Confusion Matrix shows the following**
1. **Of all 160 People that are Healthy;**
    - **140 People we're classified as Healthy - True Positive**
    - **0 were misclassified as Non-healthy - False Negative**
2. **Of all 136 that are non Healthy;**
    - **110 were misclassified as Healthy - False Positive**
    - **0 were Classified as Non-healthy - True Negative**
    
This project can be used in Hospitals and People to  make them aware of their health status.
