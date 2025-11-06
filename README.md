# Service-Center-Calls
Final project for Python analysis, using public data sets
https://www.kaggle.com/datasets/waseemalastal/customer-support-ticket-dataset
https://www.kaggle.com/datasets/heemalichaudhari/consumer-complaints
Added data sets 
pandas.read_csv()
pulling public call center data to review stats(KPI's) most commonly collected to determine quality and productivity of Service Center employees.

Two center data files are used.

loading data in Colab worksheet
checking for data quality
determining what questions to ask
Do the fastes calls have the lowest customer ratings or highest complaints
Is the volume of calls reflected by the time of year

Finding call sheets small enough to download into GitHub was a significant challenge. I have attempted to pull in multiple files with satisfactory data points to make some determination of direction or need, and have failed to find anything small enough. Made a decision to create a uniquie file that should at least give some coding examples.
final_customer_cases combines the complaint call count and the customer 'age' and 'gender' file. 
I have no idea if the customerID was actually tied to a complaint ID, but it had enough rows to make anayalsis possible. 

my intentions are as follows
Remove the Null values from the age and gender columns to review full sets of data Create a new file to return to with 330512 rows.
get a list of how many channels
sort for male, female
make-up histogram of ages
is there a pattern for reasons
see if there is a correlation between reason and gender and date

