# Titanic Survival Prediction Using Naive Bayes Classifier  

## Objective  
In this assignment, a **Naive Bayes classifier** is implemented to predict the survival of passengers on the Titanic. Using the Titanic dataset, the goal is to explore, preprocess, and use the data to train and evaluate a predictive model.  

---

## Assignment Tasks  

### 1. Data Exploration and Preprocessing  
- Load the train and test datasets using `pandas`.  
- Explore the data to understand the features and their types (numerical, categorical, etc.).  
- Handle missing values appropriately by imputing or removing.  
- Convert categorical features into numerical ones using techniques like one-hot encoding.  
- Normalize or scale the features if necessary for better model performance.  

### 2. Feature Selection  
- Identify and select key features for training the model.  
- Justify the selection of features based on their relevance and impact on survival prediction.  

### 3. Model Implementation and Evaluation  
- Use **scikit-learn** to implement a Naive Bayes classifier:  
  - Choose between `GaussianNB`, `MultinomialNB`, or `BernoulliNB` based on the feature types.  
- Train the model on the training dataset.  
- Evaluate the model using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.  
- Perform cross-validation to ensure the robustness of the model.  

### 4. Prediction  
- Use the trained model to make predictions on the test dataset.  


