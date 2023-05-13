# **Churn Prediction with Neural Networks**
This project aims to build a churn prediction model using artificial neural networks. Churn prediction is a common problem in the telecommunications industry, where companies want to identify customers who are likely to cancel their service and take proactive steps to retain them. By building an accurate churn prediction model, companies can reduce customer attrition, increase customer lifetime value, and improve their bottom line.

The dataset used in this project is sourced from Kaggle, and contains information about customers of a telecommunications company, including their demographic data, usage patterns, and account information. The goal is to predict whether a customer will churn or not based on these features.

## **Installation**
To run this project, you need to have the following libraries installed:

*  numpy
*  pandas
*  scikit-learn
*  keras
*  seaborn
*  matplotlib 

You can install these libraries using pip:

```python
pip install numpy pandas scikit-learn keras seaborn matplotlib
```

## **Usage**
To use this project, you can follow these steps:

1. Clone the repository to your local machine.
2. Open a terminal window and navigate to the project directory.
3. Run the churn_prediction.ipynb notebook using Jupyter or any other compatible tool.
4. Follow the instructions in the notebook to train and evaluate the model.

To clone the repository to your local machine you can run the line:

```python
git clone https://github.com/Steeroy/telco_churn_modelling
```

The telco_churn_modelling.ipynb notebook contains detailed instructions and explanations for each step of the process, including data exploration, preprocessing, feature engineering, model building, and evaluation.

## **Results**
After training the neural network model on the dataset, we achieved an accuracy of ~80% on the test set, which indicates that the model can accurately predict whether a customer will churn or not. We also visualized the performance of the model using a confusion matrix and classification report, which showed that the model has high precision and recall for both the churn and non-churn classes.

## **Future**
There are several ways to improve the performance of the churn prediction model, including:

*  Collect more data to improve the model's accuracy and generalization.
*  Experiment with different neural network architectures and hyperparameters to optimize the performance.
*  Perform more feature engineering to identify additional features that are relevant to the problem.
*  Use ensemble learning techniques to combine multiple models and improve the overall performance.

## **Conclusion**
In conclusion, this project demonstrates how artificial neural networks can be used to build an accurate churn prediction model. By identifying customers who are likely to churn, companies can take proactive steps to retain them and improve their bottom line. With further development and optimization, this model has the potential to be a valuable tool for telecommunications companies and other industries facing customer attrition.
