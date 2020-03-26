# Data Science Bootcamp project 2

This is the secound immersive project of the Data Science bootcamp at [neuefisch Germany](https://www.neuefische.de/) form 2020.
The goal here is to use [Lending Club](https://en.wikipedia.org/wiki/LendingClub) data from 2007 to 2011 of this web based peer to peer landing palttform to perdict the charge-off risk for loans by means of machine learning.

## orginal task discription:
For this project we chose a dataset from Lending Club approved personal loans between 2007 and 2011. 
The data can be found on www.lendingclub.com. The purpose of the analysis is to reduce defaults, 
improve profitability and help the company and investors determine interest rates. We will use machine 
learning models to analyze credit risk as a binary classification problem.

How to choose the Performance metrics? - well the model (whichever you pick) will 
be used to determine who should be approved for a loan and who shouldn’t, denying the loan to a 
client who will end up paying in full (false positives) represents a loss, but because interest is 
usually only a portion of principal the company will most likely be more comfortable not taking the
chance when the risk is not to get reimbursed at all and lose the entire principal which represents a higher amount. 
Thus the main concern here is to avoid approving somebody who won't be able to repay or in other words avoid 
false negatives. This is achieved by a model with a high recall rate. 
What would be right performance metric- precision, recall, accuracy, F1 score, or something else?

## more details
Find also the presentation and more information in the jupyter notebook : [LendingClub_Main.ipynb](LendingClub_Main.ipynb)

