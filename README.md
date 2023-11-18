# Study-on-Cart-Abandonment
# Introduction
Shopping cart abandonment is a common problem faced by e-commerce websites, where customers add items to their online shopping carts but then fail to complete the purchase. It is estimated that the average shopping cart abandonment rate is around 69%, which results in significant revenue losses for businesses. In order to tackle this issue, it is important to understand the reasons why customers abandon their carts.

# Work Done/ Steps that I have followed
⇒ Data Structure Analysis: Analyzed the structure of the dataset I were using, which consisted of 4284 rows and 13 different attributes. This step helped me to understand the type and distribution of the data I were working with.

⇒ Exploratory Data Analysis (EDA): Performed exploratory data analysis using univariate and bivariate analysis techniques for both numerical and categorical data. This helped me to identify any patterns or trends in the data and get a better understanding of the relationships between different attributes.

⇒ Correlation Plot Visualization: Visualized the correlation plot between different attributes to identify any strong or weak relationships between them. This helped me to identify which attributes were most important in terms of predicting shopping cart abandonment.

⇒ Data Preprocessing: Applied various data preprocessing techniques to clean and prepare the data for analysis. This included handling missing values, handling outliers using min-max normalization and box-cox normalization, and performing feature selection.

⇒ Oversampling using SMOTE: Since the dataset was imbalanced, with a larger number of instances where customers did not abandon their carts, I used SMOTE (Synthetic Minority Over-sampling Technique) to balance the data. This ensured that the model built would not be biased towards one class.

⇒ Model Building: Built models using Supervised ML algorithms like Logistic Regression, Support Vector Machine(with rbf kernel), Multi-Layer Perceptron, Ada Boost Technique. 

⇒ Model Evaluation: Finally, evaluated the performance of the model using various performance metrics, such as accuracy. This helped me to determine how well the model was performing and identify areas for improvement.

⇒Accuracy of different models are as follows:

    Logistic Regression     : 98.63

    Support Vector Machine  : 98.70

    Multi-Layer Perceptron  : 98.77

    Ada Boost Classifier    : 98.90
