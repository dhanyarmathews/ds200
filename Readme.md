DS200 Module 4 - Assignment
============================
This report gives the details of Python plots and the commands used to upload to Github.

Data Source
------------
State-wise IEM part-A data on Investment and Employment from August 1991 to till last month [1] was obtained as a .csv file and was used for generating the plots. 


Line Plot
---------
The plot shows state-wise data about number of industries, investment and employment. Following are the observations:
(1) The employment was expected to be in propotional to the investment made, but in Orissa and Chattisgarh, the number of jobs in various industries was less than the investment made in those industries. Few states like Mizoram, Lakshadweep, Arunancha Pradesh did not showed neither an increase nor a decrease in the number of employments per investment made.
(2) Employment was maximum in Maharashtra. Uttar Pradesh had secons most employment rate.

Scatter Plot
------------
Scatter plot was mode to understand the following relations:
(1) Employment vs Investment
(2) Employment vs Number of industries

The motive was to understand whether an increase in number of industries attributes to an increase in employment always.

Following observations were made:
(1) The number of jobs shows a rising trend with increase in number of industries but the trend is not linear.  Assuming that it depends on a number of other factors like demographics and the state.
(2) From the scatter plot on investment vs employment,  as observed from the line plot, an increase in investment does not always result in an increase in employment. There are some states that showing this trend as identified from line plot.

Box Plot
--------
A box plot was made using the same data to understand the quartiles for number of industries, investment and employment. Following observations were made:
(1) The number of industries does not show significant variance.
(2) For investment and employment, the median is towards the smaller values. It shows a skew in data points. Assumtption is that this can also be due to the area of the state, as a larger state can hae more industries and hence more possibility for employment.
(3) The north-eastern states and union territories had less investments and employment.

References
-----------
[1] Government of India, State-wise IEM part-A data on Investment and Employment from August 1991 to till last month. Retrieved October 12, 2019 from https://data.gov.in/resources/state-wise-iem-part-data-investment-and-employment-august-1991-till-last-month




GIT Commands used:
------------------
1. git config user.name <>
2. git config user.email <>
3. git add ds200_code_and_plots.zip
4. git commit -m "Code for commit." 
5. git remote add origin https://github.com/dhanyarmathews/ds200.git
6. git push -u origin master
