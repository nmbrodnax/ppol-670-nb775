## PPOL 670-01 Fall 2018
### Problem Set 4 - Due by 11:59 on Monday, October 22

#### Submission Instructions 
For this assignment, you will create a Jupyter Notebook called *pset4_netid.ipynb* to be submitted on Canvas. Replace "netid" with your Georgetown netid. 

Include both code and responses to questions in your Jupyter notebook.  Python code should be thoroughly commented and executed in code cells and all text should be placed in [Markdown](https://www.markdownguide.org/) cells with proper formatting.  Before submitting the notebook on Canvas, you must run all cells in the notebook and save it.

For this assignment, you will apply one of the supervised learning techniques discussed in class.  Your Jupyter notebook should begin with all necessary import statements and include sensible section headers throughout. In addition, any visualizations should adhere to the best practices we have discussed in class. This assignment requires the file *county_demographics_2016.csv*, which can be found on Canvas.  

 1. Create a dataframe object by loading the file *county_demographics_2016*.  Display the first five rows of the dataframe.  

 2. Create a scatterplot with the percentage of high school graduates on the x-axis and median income on the y-axis.  

 3. Create a second scatterplot with percent of high school graduates on the x-axis and the natural logarithm of median income on the y-axis.  How does the log transformation change the plot?  Describe the relationship between the percentage of high school graduates and median income.

 4. Create a feature matrix and a target array from your dataframe object, where `X` includes percentage of high school graduates and `y` includes the log of median income.

 5. Use the `LinearRegression` model from `sklearn.linear_model` to fit a linear regression model with an intercept.  Display the coefficient for percentage of high school graduates.

 6. Create an array with 100 random observations within the range for percentage of high school graduates. Predict median income for this set of new observations.  

 7. Create a scatterplot showing the data and the best line of fit.









