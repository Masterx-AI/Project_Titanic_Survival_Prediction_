# AI/ML Project - Titanic Survival Prediction 🛳️

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/145105967-cbd60849-ae30-4a4a-8450-fc73a2f7a290.jpg" style="width: 1000px;"/></p>

### Description:

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).


### Acknowledgements:
This dataset has been referred from Kaggle: https://www.kaggle.com/c/titanic/data.

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to predict weather the passenger survives or not.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Feature Selection/Extraction
6. Predictive Modelling
7. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Target Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/145106098-e881f0d0-6101-4cfb-9a52-bba1c36ecc06.png" /></p>

**2. Categorical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/145106132-32713d65-f22b-4769-9002-e652a1160772.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/145106214-6fa6f6a1-0cd5-46ca-b789-da6ed3cba52f.png)
![image](https://user-images.githubusercontent.com/54996245/145106229-8ad2469f-0480-467f-b237-3447ad5f7406.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/145106255-a0352942-3779-4c3f-a568-205df5480cec.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/145106272-c881c1b8-2515-40ec-bde3-a5ea8b670f6b.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/145106292-ab50cc88-68df-4887-bcc9-3bb6e04fdaf9.png)

**7. VIF & RFE Scores & PCA Decomposition**
  
![image](https://user-images.githubusercontent.com/54996245/145106331-7819bac1-4f99-4ac7-8164-09418ca4b238.png)
![image](https://user-images.githubusercontent.com/54996245/145106349-d563866a-e607-4829-94d7-ac55fada12df.png)
![image](https://user-images.githubusercontent.com/54996245/145106378-861a9788-077b-43ef-8e5c-cfcce595bec9.png)
![image](https://user-images.githubusercontent.com/54996245/145106391-0578911f-35ca-432c-8c03-fb7a8b5c1229.png)

**8. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/145106410-ffe4d97d-b990-4a72-aab4-4cfa24e4e872.png)

**9. Tree Plot & Feature Importance in Random Forest
  
![image](https://user-images.githubusercontent.com/54996245/145106427-6ff267c2-5cb1-436e-b6c4-093027940b98.png)
![image](https://user-images.githubusercontent.com/54996245/145106449-2bf244c5-5dee-41f2-80bb-d476abcc05a8.png)


**10. ML Algorithm's Scores for the Dataset**
  
![image](https://user-images.githubusercontent.com/54996245/145106473-5a9f0e87-66fe-4137-bdf7-c101d5deac76.png)
![image](https://user-images.githubusercontent.com/54996245/145106489-bf55df02-ca20-4a41-858e-854bad3ac17f.png)

  
### Here are some of the key outcomes of the project:
- The Dataset was small totally around 88 thousand samples & after preprocessing 10.6% of the datasamples were dropped. 
- The samples were slightly imbalanced after processing, hence SMOTE Technique was applied on the data to  balance the classes, adding 12.0% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the feature-set.
- Feature Selection/Eliminination was not carried out and appropriate features were not shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The Boosting & Random Forest Classifier performed exceptionally well on the current dataset, considering F1-score as the key-metric.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive, but comes at the cost of slight misclassifications.

