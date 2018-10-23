## PPOL 670-01 Fall 2018
### Problem Set 5 - Due by 11:59 on Monday, October 29

#### Submission Instructions 
For this assignment, you will create a Jupyter Notebook called *pset5_netid.ipynb* to be submitted on Canvas. Replace "netid" with your Georgetown netid. 

Include both code and responses to questions in your Jupyter notebook.  Python code should be thoroughly commented and executed in code cells and all text should be placed in [Markdown](https://www.markdownguide.org/) cells with proper formatting.  Before submitting the notebook on Canvas, you must run all cells in the notebook and save it.

For this assignment, you will apply one of the techniques discussed in class.  Your Jupyter notebook should begin with all necessary import statements and include sensible section headers throughout. In cases where you are required to review and summarize documentation, your responses must be in your own words.  No points will be earned for copying and pasting text from another source.

 1. Review the [user guide](http://scikit-learn.org/stable/modules/neighbors.html#classification) and [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html) for the `KNearestClassifier` function from the `sklearn.neighbors` module.  Discuss the trade-off between higher and lower values of k.  Describe the purpose of the `n_neighbors` and `weights` arguments of the function.

 2. Create a feature matrix and target array from the Iris dataset, with `species` as the target. Next, create a `KNeighborsClassifier` model object with k = 1.  

 3. Generate predictions from the model, using all available data. Using the [`accuracy_score`](http://scikit-learn.org/stable/modules/model_evaluation.html#accuracy-score) function from `sklearn.metrics`, compute and display the accuracy scores for the model with k = 1 and k = 5. Discuss the impact of varying k on the accuracy score.  

 4. Using the [`train_test_split`](http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) function from `sklearn.model_selection`, create training and test sets for X and y, using a 50% split and a seed of zero.  

 5. Fit your `KNeighborsClassifier` model for k = 5 on the training data and predict y on the test data.

 6. Compute and display the accuracy score for the predictions generated from the test data.  Is this accuracy score equivalent to the accuracy score obtained in Step 3?  Explain why or why not.

 7. Review the documentation for the [`cross_val_score`](http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html#sklearn.model_selection.cross_val_score) function from the `sklearn.model_selection` module.  Describe what this function does.  Give an example of a scenario in which you would use this function. 

 8. Create a `KNeighborsClassifier` model object with k = 3. Using `cross_val_score`, compute and display the scores from a five-fold cross-validation. Discuss the performance of your model based on the results.  

BONUS: Write a function called `knncv()` that accepts as arguments a list of k (neighbor) integer values and an integer for the number of cross-validation folds.  It may include other arguments.  The function should return a summary of the scores associated with each k and cross-validation fold combination.  Provide a demonstration of the function's use.                                                 





