# AmesHousingData Problem Statement
**DOMAIN**
The Ames Housing data set was created by Dean De Cock.This data set is a collection of different features representing the houses sold in Ames, Iowa between 2006 and 2010.

**PROBLEM STATEMENT**
The EDA of the Ames Data involves data cleansing and doing some EDA like the contigency tables,distribution plots,pairs plots etc.
The data is preprocessed by deskewing the numerical features and one-hot encoding the categorical features.We use different statistical techniques to identify the 10 most important features.

**DATA DESCRIPTION**
The Ames Housing data set consists of 2930 observations and 82 features.These features include 20 continuous variables,46 categorical(23 nominal and 23 ordinal) and 14 discrete.After doing some EDA we get to see that the data set includes 13944 NA values and 48760 empty values.

While doing some EDA we found that 5 observations are outliers and can be removed.
The data set occupies the size of 1.49 MB.

**PROPOSED SOLUTION**
The data set is created for building the regression model.A simple model can be built by using only few variables.A complicated model can be built using any number of variables.

**BENCHMARK MODEL**
A naive benchmark model would be the linear regression model.

**PERFORMANCE METRIC**
We can assess the accuracy of the model using Mean Square Error(MSE),Mean Absolute deviation.

**REFERENCES**

http://www.amstat.org/publications/jse/v19n3/decock/DataDocumentation.txt
http://ww2.amstat.org/publications/jse/v19n3/decock.pdf
