## **Predecting Employee Termination Using Advanced Neural Network (ANN)**

#### Description

       - This dataset encapsulates information about employee status, specifically highlighting terminations. For each of the 10 years covered, the dataset provides details on both active employees and those who have undergone termination.* 
       - The provided dataset comprises 49,653 entries and includes 18 columns, each representing a specific aspect of employee information.* 
       - This dataset is well-structured and includes diverse information about employees, allowing for a comprehensive analysis of factors influencing employee status, with a particular emphasis on terminations. The combination of numerical and categorical data types in the columns provides flexibility for various analytical approaches, such as trend analysis, predictive modeling, and exploration of employee demographics.

#### Objective
```The primary objective of this dataset is to assess and analyze the employment status of individuals based on the available data. By leveraging the information provided, the project aims to uncover insights into the factors contributing to terminations, identify patterns in employee turnover, and develop predictive models for future employment outcomes.```

#### **Exploratory Data Analysis (EDA)**

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Employee Attrition Status 
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Attri_dis.PNG' style='width: 50%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Attrition Count Based on Age
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Age_att.PNG' style='width: 70%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Attrition Count Based on Gender
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/gender_at.PNG' style='width: 50%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Attrition Count By Department
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Dep_at.PNG' style='width: 70%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Attrition Count By City
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/city_at.PNG' style='width: 70%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Classification Report
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/clss.PNG' style='width: 60%;' />
                     </p>
</details>

<details>
       <summary>
              <strong>​✒️<Click here to see :</strong> Confusion Matrix
       </summary>
                     <p align='center'>
                            <img src='https://github.com/Shuhaib73/Employee_Attrition-Deep_Learning-ANN/blob/main/Confu.PNG' style='width: 90%;' />
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
