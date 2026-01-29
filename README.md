## Diabetes Prediction Using Perceptron From Scratch

## Project Overview
This project demonstrates the implementation of a Perceptron algorithm from scratch to predict diabetes outcomes.  
Instead of relying on machine learning libraries for modeling, the Perceptron logic is manually implemented to build a strong foundation in core machine learning concepts.

The model is trained on a diabetes dataset and learns to classify whether a patient is diabetic or not based on medical features.

## Objectives
• Understand how the Perceptron algorithm works internally  
• Implement forward pass and weight updates manually  
• Train a binary classification model without using sklearn models  
• Evaluate model performance on unseen data  

## Dataset Description
The dataset contains medical diagnostic features such as  
• Glucose level  
• Blood pressure  
• BMI  
• Insulin  
• Age  

Target variable  
• Outcome  
0 represents Non Diabetic  
1 represents Diabetic  

## Technologies Used
• Python  
• NumPy  
• Pandas  
• Matplotlib  
• Jupyter Notebook  

## Perceptron Algorithm Explanation
The Perceptron is a linear binary classifier that works by  
• Initializing weights and bias  
• Computing weighted sum of inputs  
• Applying an activation function  
• Updating weights using error and learning rate  

Weight update rule  
new_weight = old_weight + learning_rate × error × input  

## Project Workflow
1 Load and explore the dataset  
2 Preprocess data and separate features and labels  
3 Initialize weights and bias  
4 Train the Perceptron using iterative updates  
5 Track errors during training  
6 Test the model on unseen data  
7 Visualize training performance  

## Model Training
• Learning rate is defined manually  
• Training is done over multiple epochs  
• Error count per epoch is recorded  
• Model gradually reduces misclassifications  

## Evaluation Metrics
• Accuracy score  
• Error count per epoch  
• Visual inspection of learning trend  

## Results
The Perceptron model successfully learns to classify diabetes outcomes with reasonable accuracy.  
Training error decreases over epochs showing effective learning.

## Key Learnings
• How gradient based learning works at a fundamental level  
• Importance of learning rate and epochs  
• Difference between library based models and manual implementation  
• Debugging and improving ML logic  

## Future Improvements
• Feature scaling for better convergence  
• Compare results with sklearn Perceptron  
• Extend to Logistic Regression from scratch  
• Add confusion matrix and precision recall metrics  

## How To Run
1 Clone the repository  
2 Open the notebook in Jupyter  
3 Run all cells sequentially  
4 Observe training output and plots  

## Author Credit
Author Satyam Gajjar  
