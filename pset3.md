## PPOL 670-01 Fall 2018
### Problem Set 3 - Due by 11:59 on Monday, October 1

#### Submission Instructions 
For this assignment, you will create a Jupyter Notebook called *pset3_netid.ipynb* and a CSV file called *pset3_data_netid.csv*. In all cases, replace "netid" with your Georgetown netid. Submit both files on Canvas.

Include both code and responses to questions in your Jupyter notebook.  Python code should be executed in code cells and all text should be placed in [Markdown](https://www.markdownguide.org/) cells.  Before submitting the notebook on Canvas, you must run all cells in the notebook and save it.

**BONUS:** This assignment requires you to acquire a dataset in CSV format.  If the data of interest are available through an API, you may earn up to 10 additional points by acquiring your data through the API rather than via CSV download.  All code for the bonus must be included in your Jupyter notebook and follow the RAPTOR model.

#### Part 1 - Data (15 points)

Find a dataset in CSV format from [data.gov](https://catalog.data.gov/dataset) in a policy area of interest to you.  Answer the following questions in your Jupyter notebook under a heading called "Overview":

 1. Provide a description of the dataset with regard to the policy topic, publisher, and the years included.  What government agency and/or organization produced the dataset?  What were the data originally used for?

 2. What other data formats are provided by the publisher?

 3. What interests you about this dataset?  List at least three questions that this dataset might be used to answer?


#### Part 2 - Exploration (35 points)

Download the dataset described above in CSV format and save it as *pset3_data_netid.csv*. The dataset must be saved in the same directory as your Jupyter notebook. Complete the following in a new section of the notebook with the heading "Exploration."

 2. Review the [`pandas`](http://pandas.pydata.org/pandas-docs/stable/) documentation for `.isnull()`, `.notnull()`, and `.fillna()`.  Describe the basic functionality of these functions in your Jupyter notebook.

 3. Create a dataframe object from your dataset.  Display the first ten rows of the dataframe.

 4. Create a subset with at least three quantitative variables.  Display the first ten rows of the subset.

 4. Use `pandas` functionality to answer the following questions: Are your variables missing any observations?  If so, how many?

 5. Use `pandas` functionality to compute the following descriptive statistics for each variable: mean, variance, and standard deviation.





