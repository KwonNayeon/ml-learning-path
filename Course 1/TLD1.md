# Today I Learned

## March 21, 2023

- Classification: K-Nearest Neighbors (KNN) algorithm
  - Learned how to build a KNN model to make predictions and how to access the model's accuracy
  - Clarified the concepts of underfitting and overfitting in machine learning
  - Discovered an effective way to see the change of accuracy according to the number of neighbors by using a for loop

## March 22, 2023

- Git
  - I was supposed to take a lesson regarding regression.
  - Instead, today I learned how to use Git to manage version control for my code projects.
  - It took some time and effort, but I successfully connected Git and GitHub, and also integrated Git with my Jupyter Notebook workflow.
  - I am writing this on Jupyter notebook, and it will be automatically in my GitHub page. Amazing!
  
## March 23, 2023

- Regression
  - I learned that in scikit-learn, features must be represented as a two-dimensional array.
  - I figured out that if I have a one-dimensional feature vector, I can convert it into a two-dimensional feature matrix with one column using NumPy's reshape() method, which is the required format for scikit-learn.

## March 24, 2023

- Even though I was tired from a job interview earlier today, I was determined to dedicate my time to learning regression models.
- Regression
  - During my review of regression models, I focused on two common evaluation metrics: R-squared (R^2) and Root Mean Squared Error (RMSE).
  - At first, I was confused about how to calculate these metrics using Python. However, I was able to figure it out and now have a better understanding of how to use libraries like sklearn.metrics and numpy to compute R^2 and RMSE for regression models.
  
## March 25, 2023

- Cross-validation
  - I learned how to run cross-validation on Python using sklearn.
  - When I was taking an advanced regression analysis course, this was one of the hardest concepts for me to understand.
  - However, now I realize it is quite simple to implement and I understand what it's for.

- Regularized regression: Ridge & Lasso
  - I ran Ridge and Lasso, which are forms of regularized regression.
  - These were also concepts I struggled to understand, especially the formulas.
  - However, upon reviewing them, I found them to be quite simple and I understood the difference between them.
  - Specifically, Lasso has some functions that allow for variable selection, unlike Ridge.
  
## March 27, 2023

- Deciding on a primary metric
  - I reviewed about metrics for evaluating ML models, such as accuracy, recall, F1 score, and precision.
  - I used to find it confusing to know which metric to use, but after taking a quiz, it became clearer.
  - I learned how to calculate these metrics using Python's scikit-learn library.
   
## March 28, 2023

- Logistic regression
  - Today I reviewed logistic regression, which is a quite familiar concept, but I mainly used it for calculating propensity score. It was a kind of new perspective to use this model for machine learning.
- ROC curve
  - I also reviewed ROC curve and AUROC. During a previous machine learning project, the ROC score was almost close to random guess, and I didn't know why it was a huge problem. After finishing the review, I finally grasped the concept and understood the problem I had with that project.
   
## March 31, 2023

- Hyperparameter Tuning
  - I always lacked confidence in hyperparameter tuning. However, I now have a clear understanding of the differences between Grid Search and Random Search and the advantages of each method. I am eager to try these methods in my machine learning project.
- Grid Search
  - Grid Search starts with defining a search space grid that consists of selected hyperparameter names and values.
  - This method searches for the best combination of hyperparameters within the defined search space grid.
- Random Search
  - Random Search defines distributions for each hyperparameter, which can be defined uniformly or with a sampling method.
  - Unlike Grid Search, Random Search does not test all possible values of hyperparameters, but randomly selects some values to evaluate the model's performance.
  - This method returns a relatively good performing model in a significantly shorter time compared to Grid Search.
 
 ## April 2, 2023
 - Preprocessing
  - It became clear why we delete one of the dummy variables.
  - First, let's say we have 7 categories. When the value of the 6 dummy variables is known, the seventh is directly referred to in this case.
  - Second, the seventh dummy variable makes it impossible to calculate the inverse matrix of X'X.
  
 ## April 3, 2023
 - Handling missing data
  - Today I learned how to drop missing data using Python. It was a great opportunity to expand my missing data handling skills in a programming context, as I have previously worked with missing data in R.
  - Additionally, I used a pipeline in Python for the first time.