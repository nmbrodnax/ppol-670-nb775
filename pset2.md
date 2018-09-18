## PPOL 670-01 Fall 2018
### Problem Set 2 - Due by 11:59 on Monday, September 24

#### Submission Instructions 
For this assignment, you will create Python scripts called *pset2_part1_netid.py* and *pset2_part2_netid.py*, and a CSV file called *pset2_part2_netid.csv*. In all cases, replace "netid" with your Georgetown netid. Submit all three files on Canvas.

#### Part 1 - Web Scraping (25 points)

Include all code for this section in a script called *pset2_part1_netid.py*.

 1. Create a list called `datasets` with the following strings as contents: 'airport', 'baseball', 'calcium', 'electricbill', and 'freethrows'.  Use print statements and references to display the following:
    
    * the first item in the list
    * the third and fourth items in the list
    * the second-to-last item in the list

 2. Create a dictionary called `data_info` for the *airport* dataset with keys for 'title' and 'observations'.  The dataset's title is *US Airport Statistics* and it has 135 observations.  Use a print statement and reference to display the title of dataset.

 3. Write a loop that will display each string in `datasets` with the extension *.txt* on the end.

 4. Create a function called `add_extensions()` that accepts a list of strings, adds '.txt' to each string in the list, and returns a list of the new strings.  To test the function, include a statement calling `add_extensions()` with `datasets` as an argument.

 5. Add statements to import the `requests` and `bs4` Python packages.  (Reminder: Import statements should be placed at the beginning of your script.) Use the `.get()` method to request the contents of the following webpage: [http://www.gutenberg.org/](http://www.gutenberg.org/). Use a print statement to display the HTTP response code for the request.

 6. Review the Quick Start documentation for [Beautiful Soup 4.4.0](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start). Add statements to your script to create a Beautiful Soup object and display a list of instances containing "h2" tags.


#### Part 2 - APIs (25 points)

Include all code for this section in a script called *pset2_part2_netid.py*.  This script should produce a CSV file called *pset2_part2_netid.py*.

 1. Review the [API documentation](https://github.com/DataUSA/datausa-api/wiki/Data-API) available from [DataUSA](https://datausa.io).

 2. Modify the script [ppol670_ipeds_api.py](https://github.com/nmbrodnax/ppol-670-nb775/blob/master/ppol670_ipeds_api.py) to query two variables from any DataUSA dataset other than IPEDS (e.g., Bureau of Labor Statistics, County Health Records, etc.).  Your python script should produce a CSV file with the results of your query.  NOTE: Do not use the "Download as CSV" query option available through the API.







