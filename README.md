# Topic-19-Model-Deployment

This is a simple Random Forest Classifier model deployment on local host http://127.0.0.1:5000

### Concept 
1. Dataset named `heart.csv` used to train the model 
2. The model needs 19 datas input from user 
3. User enters datas then model predicts either he/she probably suffers a heart failure or not

### Features explanation 
1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: oldpeak = ST [Numeric value measured in depression]
11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]


### OUTPUT 
![home](https://user-images.githubusercontent.com/101930615/204236922-14b2ab10-b8f6-40d4-9d7f-453ff28b1c05.png)
![predict](https://user-images.githubusercontent.com/101930615/204237402-b9270b78-ce1d-418e-ac1f-c08a2044e851.png)
