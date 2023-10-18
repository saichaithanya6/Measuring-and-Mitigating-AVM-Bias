### AVM(Automated Valuation Model)
Typically, a home is assessed for its value either by a human appraiser or by using an automated valuation model (AVM). Human appraiser bias is a risk, as a multitude of anecdotes and recent research attests to 
the systemic injustice in the home appraisal process and the harms appraisal bias causes. Multiple news reports suggest that Black homeowners often feel they must “whitewash” their property by removing all 
evidence of their racial background to get a fair valuation. Whereas the human appraiser bias may be evidenced by racial and ethnic references in appraiser’s reports, AVM researchers and AVM developers often suggest that 
their models are race-neutral since they do not explicitly use race as a predictor in the model and as such AVMs should be used to eliminate human appraisers’ racial bias. However, more work is required to study AVM bias as
there is an abundance of evidence that AVMs may be unfair to majority-Black and majority-Latino neighborhoods when compared with majority-White neighborhoods because they produce higher error rates when applied to 
properties in communities of color.


### Problem Statement
Test an AVM for racial bias in model outcomes, quantify the size of the bias, if any, identify model features that drive the bias, and describe potential societal harms that can result from this bias. 

### Data descriptions used in the project:

The model to be explored in this hackathon is an AVM that allegedly estimates home values based on 7.5 million statistical and machine learning models. While the predicted home value and contract or sale price
for each property are not given in the dataset, the log errors, i.e., the difference between the log of a Zestimate value and the log of a sale price, are given and the log error should be treated as the model 
target.

a. properties_2016.csv - all the properties with their home features for 2016.
b. properties_2017.csv - all the properties with their home features for 2017 
c. train.csv - the training set with transactions from Jan 2016 to June 2017
d. test.csv - the training set with transactions from July 2017 to October 201
