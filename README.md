# Linear-Regression-and-Perceptron-Regressor-Implementation
This Notebook checks the correlation between the stock prices of the various sectors with the college student's enrollment in those sectors. If the stock prices of a particular sector is doing really well, should we expect the college student's enrollment in those sectors to be high. Is there some sort of relationship with these two? Or is it completely random for the college students to enroll in a particular sector irrespective of its performance in the stock market? By the end of this notebook we will be able to conclude for years from 2009-2018 if there exists a relationship between these two things.

Reference Sites:

#Subjects Available
https://www2.census.gov/programs-surveys/acs/tech_docs/pums/subjects_in_pums/2018_5yr_PUMS_Subjects.pdf?#


#Main Overview Page
https://www.census.gov/programs-surveys/acs/data/pums.html


#Data Request Page
https://data.census.gov/mdat/#/


#Census.gov API reference:
https://www.census.gov/data/developers/guidance/api-user-guide.Overview.html


#Tutorial on how to make api requests:
https://www.dataquest.io/blog/python-api-tutorial/

In this Project I have made use of Pickles

What are Pickles?
It is a type of data file used in python for saving python objects. it is a helper function to save objects. Since the dataset is huge once we download the data and save it in a pickle, we don't have to download it again, because the data will get stored in our local folder as a pickle file.

After extracting the data and preprocessing it, I have split the 70% data into train and 30% data into test, I fitted the linear regression model to the train data set.

Similarly, I fitted the train data into MLPRegressor. After the observing the r^2 value from both the models, I concluded that there is no correlation between the stock market performance and college enrollment data in that sector.
