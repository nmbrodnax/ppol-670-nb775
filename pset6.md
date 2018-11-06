## PPOL 670-01 Fall 2018
### Problem Set 6 - Due by 11:59 on Monday, November 12

#### Submission Instructions 
For this assignment, you will create a Jupyter Notebook called *pset6_netid.ipynb* to be submitted on Canvas. Replace "netid" with your Georgetown netid. 

Include both code and responses to questions in your Jupyter notebook.  Python code should be thoroughly commented and executed in code cells and all text should be placed in [Markdown](https://www.markdownguide.org/) cells with proper formatting.  Before submitting the notebook on Canvas, you must run all cells in the notebook and save it.

For this assignment, you will apply one of the techniques discussed in class.  Your Jupyter notebook should begin with all necessary import statements and include sensible section headers throughout. In cases where you are required to review and summarize documentation, your responses must be in your own words.  No points will be earned for copying and pasting text from another source.

#### Data
This assignment requires the file *heart.csv*, which can be found on Canvas.  The file includes the following variables:

 * Age - age in years
 * Sex - 1 = male; 0 = female
 * ChestPain - chest pain type
    * 1 = typical angina
    * 2 = atypical angina
    * 3 = non-anginal pain
    * 4 = asymptomatic 
 * RestBP - resting blood pressure in mm Hg
 * Chol - serum cholesterol in mg/dl
 * Fbs - fasting blood sugar > 120 mg/dl, 1 = true; 0 = false
 * RestECG - resting electrocardiographic results
    * 0 = normal
    * 1 = having ST-T wave abnormality
    * 2 = showing probable or definite left ventricular hypertrophy
 * MaxHR - maximum heart rate during exercise
 * ExAng - exercise induced angina, 1 = yes; 0 = no
 * Oldpeak - ST depression induced by exercise relative to rest
 * Slope - the slope of the peak exercise ST segment
 * Ca - number of major vessels (0-3) colored by flourosopy
 * Thal - Thallium stress test
    * 3 = normal 
    * 6 = fixed defec
    * 7 = reversable defect
 * AHD - angiographic heart disease diagnosis


#### Decision Tree Classification

 1. Load and examine the variables from the Heart dataset.  What variables, if any, are missing observations?

 2. Create a feature matrix and target array from the Heart dataset, with the aim of predicting heart disease diagnosis. 

 3. Create a `DecisionTreeClassifier` model object.  Fit the model using all available data. 

 4. Perform a five-fold cross-validation using the `cross_val_score` function.  Discuss the performance of your model based on the results.

 5. Display a visualization of your decision tree.

 6. Create a DataFrame with two columns: variable name and variable importance. Hint: You can extract variable importance from the Decision Tree model.

 7. Create a horizontal bar plot titled "Variable Importance" with the variable names sorted by importance.  Discuss the relative importance of the variables for predicting a heart disease diagnosis.



