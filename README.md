# Reboot-Box-plots-for-education
Finding a better way to classify resources may help clarify different spending approaches and drive toward strategies to use the dollars we spend on education more effectively and efficiently.

The primary work is helping school districts use their resources more strategically. The goal is to use data to predict aspects of a school's budget, and use that to make more effective decisions.

DATASET USED

The training data contains 400278 rows and 23 columns
23 columns contains 14 features and 9 predefined labels.
There were 104 labels among 14 features to assign into 9 different categories.
Submission format contains 50064 rows and 104 columns where each value shows the probability of specified label with the corresponding features.

DATA PREPROCESSING

The dataset was cleaned.
Train dataset was separated based on the features and labels.
Missing values are filled Null.
String data was handled with One-hot encoding.
StandardScaler is used  to transform the data such that its distribution has a mean 0 and standard deviation of 1 for every column

METHODS USED

Our task is a multi-class-multi-label classification problem with the goal of attaching canonical labels to the free form text in budget line items.
Random Forest Classifier suits the problem for getting better accuracy. 
Random Forest classifier creates a set of decision trees from randomly selected subset of training set. It then aggregate the votes from different decision trees to decide the final class of the test object.

The metric used for this competition is affectionately named 'multi-multi'. In this competition we have multiple dependent variables, and each of these variables can take on one of multiple labels. So, multiple dependent variables, multiple labels in each, multi-multi-class-log loss.



Team members
1.Khushboo Paddiyar

2.S.GopiChand

3.Ch.Sai Poorna Chandu

4.N.Sandeep                       
