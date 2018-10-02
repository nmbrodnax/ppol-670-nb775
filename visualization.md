## PPOL 670-01 Fall 2018

## Background
You have recently been hired as a data scientist for the [National Conference of State Legislatures](http://www.ncsl.org/) (NCSL).  Founded in 1975, the NCSL is a bi-partisan organization created to represent the interests of state legislatures. 

As Congress has [recently allowed the Farm Bill to expire](https://www.yahoo.com/news/congress-fails-pass-farm-bill-213424383.html), your supervisor has been asked to prepare comments on the Supplemental Nutrition Assistance Program (SNAP) for the next joint conference meeting of the House and Senate agriculture committees.  Your first task will be to review competing narratives around the Farm Bill based on the opening statements of [Sen. Pat Roberts](https://www.agriculture.senate.gov/newsroom/rep/press/release/after-seven-farm-bills-chairman-roberts-leads-conference-committee) (R-KS) and [Sen. Debbie Stabenow](https://www.agriculture.senate.gov/newsroom/dem/press/release/ranking-member-stabenow-delivers-opening-remarks-at-farm-bill-conference-committee-meeting-) (D-MI) from the last conference committee meeting.  Seemingly lost in these narratives are the interests of states.

## Data
You log onto data.gov and find the following state-level variables pertaining to SNAP (downloadable from Canvas):

#### STATE_CD
Two-digit U.S. Postal Service code identifying State.

#### STFIPS
Two-digit Federal Information Processing Standards (FIPS) code identifying State.

#### PRGNUM
Estimated number of active SNAP/Food Stamp Program (FSP) participants. Data are available for 1989, 1993, 1995, and every year from 1997 through 2012 for States and through 2010 for counties. Participant counts are usually for the month of July. The Census Bureau controls the county-level values to their State-level value. When the original data cover an area larger than a single county, the Census Bureau uses a measure of poverty in the multiple areas to apportion the SNAP/FSP caseload numbers across the multiple areas. State-level data through 2006 represent a 12-month average, with a 6-month delay. For instance, the values presented for 1995 are based on the monthly average between July 1995 and June 1996. Since 2007, the data are based on the Federal fiscal year; for example, the values for 2012 are based on the monthly average between October 2011 and September 2012. Data fields for years prior to the introduction of the Food Stamp Program in a particular county or State are coded as "-9995." If the county's number of FSP participants was fewer than 50, the field is coded as "-9998." 

#### PRGBEN 
Estimated total annual amount of SNAP/FSP benefits (in thousands) issued to State or county residents in a year. Data are available for every calendar year from 1969 through 2010. To obtain an estimate of average total benefits issued to all State or county residents during a month, multiply the data value by 1,000 and divide by 12. These data are provided by the Regional Economic Accounts Directorate of the Bureau of Economic Analysis (BEA) of the U.S. Department of Commerce. The data measure the value of program benefits issued to qualifying low-income households to supplement their ability to purchase food. The State estimates are based on USDA's tabulations of the value of distributed benefits. County estimates are either based on payment data from the various State departments of social services or imputed. State-level data through 2006 represent a 12-month average, with a 6-month delay. For instance, the values presented for 1995 are based on the monthly average between July 1995 and June 1996. Since 2007, the data are based on the Federal fiscal year; for example, the values for 2010 are based on the monthly average between October 2009 and September 2010.

#### POP
Estimated population count, with the year for the data indicated by the last two digits of the variable name. Data are provided for every year from 2000 through 2010. The reference date for estimates is July 1.

#### NUMPOV
Estimated total number of poor people, with the year for the data indicated by the last two digits of the variable name. Data are provided for 1999, 2000, 2006, 2007, and 2010.

## Activity

 1. Prepare one plot to provide your supervisor with insight on how state legislatures might interpret the SNAP data.  Your plot must meet the following requirements: effective use of plot elements; appropriate titles and labels; effective use of color and contrast; meaningful measure and scale; and adherence to best practices for legibility. Email your plot to Prof Brodnax no later than 5:30 pm.

 2. Write a brief (one- to two-minute) comment that your supervisor can include weighing in on the debate between Senators Roberts and Stabenow over the treatment of SNAP in the Farm Bill.  

NOTE: You may wish to review the documentation for [`matplotlib.pyplot`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.html) or for [merging data with pandas](https://pandas.pydata.org/pandas-docs/stable/merging.html).
