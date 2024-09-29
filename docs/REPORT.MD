### Regression Model
- **Document Name:** REPORT.md
- **Authors:** Prem
- **Date:** 09/10/2024

### 1. AI System Overview
### 1.What type of AI system will the team investigate?
 The investigate on Regression AI System We utilized supervised learning techniques to train and construct a model based on dataset. The aim of our project is to predict the value of the dependent variable based on the independent variable.



### 2.What AI system has the team selected?
The  selected regression model that predicts how many calories burned during an exercise. It predicts the output based on given input variables for that we have selected the regression model. Our project involves building regression models, particularly linear regression and XGBoost, to predict calories burned during exercise. 



### 3.What sources of information has your team used to  get started?


To get started with our project, we explored into various sources of information to understand the concepts of linear regression, XGBoost, and relevant Python libraries. We extensively relied on online resources such as wikipedia, geekforgeeks(for implementation), Kaggle(for the dataset), Javapoint, scikit-learn, study.com, DANA PESSACH∗, EREZ
SHMUELI. 21 Jan,2020. Algorithmic Fairness, Department of Industrial Engineering, Tel-Aviv University, Israel. https://arxiv.org/abs/2001.09784 (This is a paper on ‘Algorithimic Fairness’) and study.com. These websites provided comprehensive explanations, tutorials, and examples to help us grasp the fundamental concepts and practical applications of linear regression and XGBoost.

 And referred various sources for guidance. The online platforms like Wikipedia, GeeksforGeeks, Kaggle, Javapoint, and study.com. These websites provided us with detailed explanations, tutorials, and real-world examples with demonstrative implementations, helping us grasp the core concepts of both algorithms, linear regression and XGBoost. Additionally, we explored Python libraries such as pandas, matplotlib, and seaborn to understand how to manipulate data, visualize it, and analyze it effectively. We also delved into academic papers such as "Algorithmic Fairness" by DANA PESSACH and EREZ SHMUELI from Tel-Aviv University, which provided valuable insights into ethical considerations in machine learning. By leveraging these diverse resources, we gained a comprehensive understanding of the techniques needed to build our AI system. This approach enabled us to implement linear regression and XGBoost algorithms for our project.

 ### 2.Relevant Theoretical Background
 #### 1.What your AI system does and How the system works.
 AI system predicts the number of calories burned during exercise based on various input variables such as exercise type, duration, age, heart rate, etc. It utilizes regression techniques, specifically linear regression and XGBoost regression, to model the relationship between these input variables and the target variable (calories burned).
 
 The AI system initiates by collecting exercise session data, encompassing variables like exercise type, duration, age, and heart rate. Following data preprocessing, including handling missing values and encoding categorical variables, the system trains two models: Linear Regression and XGBoost Regression. Evaluation metrics like MSE and RMSE gauge model performance, culminating in predictions of calories burned during exercise based on provided parameters. Overall, the system efficiently predicts calories burned by iteratively refining models through training, evaluation, and prediction phases.

***Key Concepts and Techniques***

In this project, supervised learning invole training our AI model with labeled data, pairing inputs (such as exercise type, duration, age, heart rate) with corresponding outputs (calories burned), allowing the model to predict calorie expenditure accurately.


Regression, as applied in our project, focuses on predicting a continuous value in this case, the amount of calories burned during exercise by establishing relationships between input variables (e.g., exercise type, duration, age, heart rate) and the output variable (calories burned).

Linear regression as a statistical tool within our supervised learning framework, helping us discern and forecast linear associations between independent variables (e.g., exercise parameters) and the dependent variable (calories burned), ultimately identifying the optimal linear equation that best fits observed data.

Gradient boosting, modified to our regression task, combine numerous weak prediction models, typically decision trees, to form a robust predictive model. Through iterative refinement, it minimizes prediction errors, enhancing accuracy in forecasting the target variable (calories burned).

XGBoost, or eXtreme Gradient Boosting, is a important algorithm deployed in our project for constructing regression models. Utilizing a gradient boosting framework, it iteratively enhances model performance by sequentially integrating decision trees to rectify errors made by prior models. This method is particularly adept at handling structured data, making it well-suited for predicting calorie expenditure during exercise sessions based on various input parameters.




#### 3.AI System Development and Evaluation



The AI system we are developing is a regression model that predicts the amount of calories burned based on various factors. The system is developed using Python and several libraries for data manipulation, visualization, and machine learning, including pandas, numpy, matplotlib, seaborn, scikit-learn, and XGBoost.

##### Choosing and Loading the Dataset

The first step in the development of our AI system was to choose an appropriate dataset. We chose the 'exercise-and-fitness-metrics-dataset' from Kaggle, which contains various factors like gender, age, weight, exercise type, and weather conditions, along with the amount of calories burned. This dataset was loaded into a pandas DataFrame.


##### Designing the AI Model

The next step was to design the AI model. We decided to use two regression algorithms for this task: Linear Regression and XGBoost. Linear Regression is a simple and commonly used algorithm for regression tasks, while XGBoost is a more complex and powerful algorithm that often provides better performance.

##### Splitting the Dataset into Trainig and Testing Data

To train and test our AI model, we have split the dataset into training data and testing data. In our dataset we have ID, Calories Burn, Dream Weight, Actual Weight, Age, Duration, Heart Rate, BMI, Exercise Intensity. So the training data is x_train, y_train and testing data is x_test, y_test. In x_train and x_test I have placed the Dream Weight, Actual Weight, Age, Duration, Heart Rate, BMI, Exercise Intensity and in x_test and y_test I have placed the calories burn data.

##### Training the AI model

After designing the model, we trained it using x_train and y-train. So now we have trained the AI system with the x_train which is having the Dream Weight, Actual Weight, Age, Duration, Heart Rate, BMI, Exercise Intensity and y_train which is having the calories burn data. Both the Linear Regression and XGBoost models were trained using the "fit()" function provided by scikit-learn and XGBoost respectively.

##### Testing the AI Model

Once the models were trained, they were tested using the x_test data. The "predict()" function was used to make calories burned predictions on the X_test data, and these predictions were compared to the actual values i.e, y_test to evaluate the performance of the models.

##### Performance Evaluation

The performance of the models was evaluated using the Mean Absolute Error (MAE), a common metric for regression tasks. The MAE was calculated using the mean_absolute_error() function from scikit-learn's metrics module. The performances of the Linear Regression and XGBoost models were compared to determine which one provided better results.

##### Comparison of Algorithms

Finally, we compared the performance of the Linear Regression and XGBoost algorithms to determine which one was more suitable for our task. This was done by comparing the MAE of the two models. The model with the lower MAE was considered to be the better model for our task.

In conclusion, the development and evaluation of our AI system involved choosing and loading a suitable dataset, designing and implementing a regression model using two different algorithms, training and testing the model, evaluating its performance, and comparing the performance of the two algorithms.





### 6. References
References:

study.com. “Using a Linear Regression Model to Calculate a Predicted
Response Value | Statistics and Probability.” Accessed April 5, 2024.
https://study.com/skill/learn/using-a-linear-regression-model-to-calculate-apredicted-response-value-explanation.html.


“What Is Linear Regression? | IBM.” Accessed April 5, 2024. https://www.ibm.com/topics/linearregression.

Zach. “How to Make Predictions with Linear Regression.” Statology (blog),
July 27, 2021. https://www.statology.org/predictions-regression/.

dummies. “Using Linear Regression to Predict an Outcome.” Accessed April 5, 2024. https://www.dummies.com/article/academics-thearts/math/statistics/using-linear-regression-to-predict-an-outcome-169714/.

“Exercise and Fitness Metrics Dataset.” Accessed April 14, 2024. https://www.kaggle.com/datasets/aakashjoshi123/exerciseand-fitness-metrics-dataset.

Nipas, Marte, Aimee G. Acoba, Jennalyn N. Mindoro, Mon Arjay F. Malbog,
Julie Ann B. Susa, and Joshua S. Gulmatico. “Burned Calories Prediction
Using Supervised Machine Learning: Regression Algorithm.” In 2022 Second
International Conference on Power, Control and Computing Technologies
(ICPC2T), 1–4, 2022. https://doi.org/10.1109/ICPC2T53885.2022.9776710.
https://www.nist.gov/news-events/news/2024/01/nist-identifies-typescyberattacks-manipulate-behavior-ai-systems

Shein, Esther. “Governments Setting Limits on AI.” Communications of the
ACM 67, no. 4 (April 2024): 12–14. https://doi.org/10.1145/3640506.

Rogers, Jillian. “Artificial Intelligence Risk & Governance.” AI at Wharton
(blog), January 11, 2023. https://ai.wharton.upenn.edu/white-paper/artificialintelligence-risk-governan

Wikipedia, Algorithmic Bias. April 1, 2024.https://en.wikipedia.org/wiki/Algorithmic_bias#:~:text=Algorith

DANA PESSACH∗, EREZ SHMUELI. 21 Jan,2020. Algorithmic Fairness, Department of Industrial Engineering, Tel-Aviv University, Israel.
https://arxiv.org/abs/2001.09784

abhishekm482g. 2022. “Calories Burnt Prediction Using Machine Learning.”
GeeksforGeeks. November 7, 2022. https://www.geeksforgeeks.org/caloriesburnt-prediction-using-machine-learning/.

Kaggle, Calories burn prediction, 2022. https://www.kaggle.com/code/pragathiputhran/caloriesburnt-prediction/data

Linkedin, Mohammed Bahageel What are some strategies for AI explainability
and transparency? , https://www.linkedin.com/advice/0/what-some-strategiesai-explainability-transparency-wcp2c#:~:text=Strategies%20include%20using%20interpretable%20models,%2C

www.javatpoint.com. “Risks of Machine Learning - Javatpoint.” 2021.
https://www.javatpoint.com/risks-of-machine-learning.

scikit-learn. “Sklearn.Model_selection.Train_test_split.” Accessed April 14,
2024. https://scikit-learn/stable/modules/generated/sklearn.model_selection.train_test_split.html

### Appendix

Figure 1

![image](../Src/distribution_age.png)

Figure 2

![image](../src/distribution_weight.png)

figure 3

![image](../src/gender_count.png)

Mean Absolute Error for Linear Regression =  98.48020991759081

Mean Absolute Error for XGBoost Regressor =  105.47760091815255
