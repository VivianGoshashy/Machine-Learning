# Machine-Learning

Independent Study on Machine Learning. I will look into Overfitting and Regularization, Optimization, and Supervised and Unsupervised Learning topics.

1. Introduction, Overfitting, and Regularization

Regularization:

This is the technique that helps in avoiding overfitting and also it increasese model interpretability

This is a form of regression, that constrains / regularizes or shrinks the coefficient estimates towards zero.

In addition, this technique discourages learning a more complex or flexible model, so as avoid the risk of overfitting. 

Overfitted Model:

The model is not able to predict the output or target column for the unseen data by introducing noise in the output.

"Noise" - this means those data points in the dataset which don't really represent the true properties of your data, but only due to a random chance.

Types of Regularization Techniques

a. Ridge Regression
Ridge Regression is also known as L-2 norm. It is one of the Regularization technique that is used to avoid overfitting or underfitting models by adding the penalty equivalent to the sum of the squares of the magnitude of coefficients. By changing the values of the penalty function, we are controlling the penalty term. The higher the penalty, it reduces the magnitude of coefficients. This technique shrinks the estimated coefficients towards zero. It seeks coefficient estimates that fit the data well, by making the RSS small.


b. Lasso Regression
Lasso stands for Least Absolute and Selection Operator which is know as the L-1 norm. Lasso regression is used to reduce the complexity of the model. Lasso regression is similar to Ridge regression except that the penalty term incudes the absolute weights instead of a square weights. In this technique, the L1 penalty has the eﬀect of forcing some of the coeﬃcient estimates to be exactly equal to zero which means there is a complete removal of some of the features for model evaluation when the tuning parameter λ is suﬃciently large. Therefore, the lasso method also performs Feature selection and is said to yield sparse models


2. Supervised Learning

- It is also known as Supervised Machine Learning. It uses labeled datasets to train algorithms to classify data / predict outcomes accurately. It uses a training set to teach models to yield the desired output. The algorithm measures its accuracy through the loss function, adjusting untill the error has been sufficiently minimized.

Types of Supervised Learning

   1. Regression
   
   - Used to understand relationship between dependent (predictors) and independent (respose) variables
   
      i. Linear Regression
      
      - Useful tool for predicting a quantitative response
      
          a. Simple Linear Regression
          
             - It predicts a quantitative response Y on the basis of a single predictor variables x

          Equation: Y = Beta_0 + Beta_1 * X, where Beta_0 and Beta_1 are coefficients / parameters
          
          b. Multiple Linear Regression
          
             - Useful approach in predicting a response variable on the basis of multiple predictor variables

         Equation: Y = Beta_0 + Beta_1 * X_1 + Beta_2 * X_2 + ......+ Beta_p * X_p + epsilon
          
     ii. Logistic Regression
     
    iii. Polynomial Regression
    
   2. Classification
   
   - Uses an algorithm to accuratly assign test data into specific categories
   
      i. Naive Bayes Classifier
      
     ii. Support Vector Machine (SVM)
     
    iii. Decision Tree
    
     iv. K-nearest neighbor (KNN
     
      V. Random Forest
   
3. Unsupervised Learning

     - A set of statistica, tools intended for the setting in which we have only a set of features x1, x2,.....,xn measured on n observations.

     - This method is not intended to make predictions because there is no associated response variable. The goal is to discover interesting things about the measurement on x1, x2,....,xn


     i. Principal Component Analysis
     
     - Tool used for data visualization / data pre-processing before     supervised techniques are applied
     
     ii. Clustering
     
     - A borad class of methods for discovering unknown subgroups in data.
        
        a. K-Mean Clustering
        
        - A simple and elegant approach for partitioning a dataset into K
        distinct, non-overlapping clusters
        
        b. Hierarchical Clustering
        
        - Result to tree based representation of the observations called a dendrogram

4. Optimization

  a. Gradient Descent
  
  b. Stochastic Gradient Descent















































References 

[1] C. Aggarwal, Neural Networks and Deep Learning: A Textbook, Springer International Publishing, 2018.

[2] M. Awad and R. Khanna, Efficient Learning Machines: Theories, Concepts, and Applications for Engineers and System Designers, Apress, 2015.

[3] R. Berk, Statistical Learning from a Regression Perspective, Springer International Publishing, 2020.

[4] F. Chollet, Deep Learning with Python, Manning, 2017.

[5] A. Geron ´ , Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts,
Tools, and Techniques to Build Intelligent Systems, O’Reilly Media, 2019.

[6] G. James, D. Witten, T. Hastie, and R. Tibshirani, An Introduction to Statistical
Learning: with Applications in R, Springer Texts in Statistics, Springer New York, 2013.

[7] B. Lantz, Machine Learning with R, Community experience distilled, Packt Publishing, 2013.

[8] J. Leskovec, A. Rajaraman, and J. Ullman, Mining of Massive Datasets, Cambridge
University Press, 2014.

[9] S. Shalev-Shwartz and S. Ben-David, Understanding Machine Learning: From Theory
to Algorithms, Cambridge University Press, 2014.

[10] A. Smola and S. Vishwanathan, Introduction to Machine Learning, Cambridge University
Press, 2008.

[11] G. Strang, Linear Algebra and Learning from Data, Wellesley-Cambridge Press, 2019

