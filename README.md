## **Deep learning approach for diabetes prediction**

#### Description

       - This dataset presents a comprehensive compilation of information related to diabetes, specifically focusing on predictive factors. The dataset encompasses 520 entries, providing a detailed overview of various aspects related to individuals' health.
       - Each entry includes 17 columns, capturing essential information such as age, gender, and the presence or absence of symptoms related to diabetes. The dataset's structure enables a thorough analysis of potential predictors, allowing for the exploration of patterns and trends that may contribute to diabetes diagnosis.
       - The columns include both numerical and categorical data types, offering versatility for diverse analytical approaches. This dataset serves as a valuable resource for developing predictive models using deep learning techniques, aiming to enhance the accuracy of diabetes diagnosis. The inclusion of categorical variables like gender and binary indicators for symptoms ensures a nuanced exploration of the factors influencing diabetes prediction.
       
#### Objective
```The primary goal of this dataset is to delve into the intricate landscape of diabetes prediction by thoroughly analyzing individual health attributes. By harnessing the rich information embedded in the dataset, our project aims to unravel critical insights into the factors influencing diabetes, discern patterns indicative of the condition's onset, and construct robust predictive models. Through this exploration, we seek to advance our understanding of the nuanced relationships between various health indicators, paving the way for more accurate and timely predictions of diabetes in individuals.```

#### **Exploratory Data Analysis (EDA)**

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Distribution of Diabetes Based on gender
       </summary>
                     <p align='center'>
                            <img src='[https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Attri_dis.PNG](https://github.com/Shuhaib73/Diabetes_Prediction_DeepLearning/blob/main/d1.PNG)' style='width: 50%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Distribution of Diabetes Based on Age
       </summary>
                     <p align='center'>
                            <img src='[https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Age_att.PNG](https://github.com/Shuhaib73/Diabetes_Prediction_DeepLearning/blob/main/d2.PNG)' style='width: 70%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Classification Report for Training set
       </summary>
                     <p align='center'>
                            <img src='[https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/gender_at.PNG](https://github.com/Shuhaib73/Diabetes_Prediction_DeepLearning/blob/main/d4.PNG)' style='width: 50%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Classification Report for Testing set
       </summary>
                     <p align='center'>
                            <img src='[https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Dep_at.PNG](https://github.com/Shuhaib73/Diabetes_Prediction_DeepLearning/blob/main/d5.PNG)' style='width: 70%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Confusion Matrix for Training & Testing
       </summary>
                     <p align='center'>
                            <img src='[https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/city_at.PNG](https://github.com/Shuhaib73/Diabetes_Prediction_DeepLearning/blob/main/d3.PNG)' style='width: 70%;' />
                     </p>
</details>


## The project pipeline can be summarized in the following steps: 
#### **Data Understanding and Exploration** : 
```In the initial phase of our project, we focus on understanding and exploring the dataset. This involves loading the data and delving into the characteristics of the available features. By performing exploratory data analysis (EDA), we gain insights into the distribution of variables, identify potential patterns, and understand the relationships between different features. This understanding guides us in selecting relevant features for our final model, laying the foundation for subsequent phases.``` 
#### <strong>Data Preprocessing</strong>: 
```The data preprocessing phase is crucial for ensuring the quality and reliability of our model. We address missing values, handle outliers, and perform any necessary data cleansing tasks. This step contributes to the overall data integrity and prepares the dataset for model training. Additionally, we consider feature engineering and transformations to enhance the model's performance by creating new meaningful features or transforming existing ones.```
#### <strong>Feature Selection and Engineering</strong>: 
```Building on insights gained from EDA, we refine our feature selection strategy to focus on the most influential variables. Feature engineering techniques are explored to further improve the predictability of our model. This phase aims to enhance the model's ability to capture relevant patterns in the data, contributing to better overall performance.```
#### <strong>Model Building and Hyperparameter Tuning</strong>: 
```The heart of the project lies in building and fine-tuning our model. We explore various machine learning models, with a specific emphasis on Artificial Neural Networks (ANN) – a powerful tool for complex pattern recognition. The architecture of the ANN is carefully crafted, and hyperparameters are tuned to optimize model performance.```
#### <strong>Model Evaluation</strong>: 
```The final phase assesses the performance of our model using appropriate metrics. In the context of our project, the focus is on accurately classifying different employee status categories. We analyze metrics such as accuracy, precision, recall, and F1-score to gauge the model's effectiveness.```
#### <strong>Conclusion</strong>: 
```The model exhibits exceptional performance on the training and testing set, achieving 100% precision, recall, and F1-score for both classes (0 and 1). The support values indicate that all instances of both classes were accurately predicted. The overall accuracy of the model is also perfect, with a value of 1.00. This outstanding performance underscores the model's ability to precisely classify employee status, making it a highly reliable tool for predicting terminations.```
