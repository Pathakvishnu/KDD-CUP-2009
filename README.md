# KDD-CUP-2009 : Customer Relationship Management

Customer Relationship Management (CRM) is a key element of modern marketing strategies. The KDD Cup 2009 offers the opportunity to work on large marketing databases from the French Telecom company Orange to predict the propensity of customers to switch provider (churn), buy new products or services (appetency), or buy upgrades or add-ons proposed to them to make the sale more profitable (up-selling).

The most practical way, in a CRM system, to build knowledge on customer is to produce scores. A score (the output of a model) is an evaluation for all instances of a target variable to explain (i.e. churn, appetency or up-selling). Tools which produce scores allow to project, on a given population, quantifiable information. The score is computed using input variables which describe instances. Scores are then used by the information system (IS), for example, to personalize the customer relationship. An industrial customer analysis platform able to build prediction models with a very large number of input variables has been developed by Orange Labs. This platform implements several processing methods for instances and variables selection, prediction and indexation based on an efficient model combined with variable selection regularization and model averaging method. The main characteristic of this platform is its ability to scale on very large datasets with hundreds of thousands of instances and thousands of variables. The rapid and robust detection of the variables that have most contributed to the output prediction can be a key factor in a marketing application.

The challenge is to beat the in-house system developed by Orange Labs. It is an opportunity to prove that you can deal with a very large database, including heterogeneous noisy data (numerical and categorical variables), and unbalanced class distributions. Time efficiency is often a crucial point. Therefore part of the competition will be time-constrained to test the ability of the participants to deliver solutions quickly.

# Challenges: 

1. Highly Imbalanced data (To many -1 (False) labels and less of 1 (True) labels). <br/>
2. Too many null values in each feature. There are 223 features in a train dataset and what I did I applied a filter to each one of the feature containing more than 80 percent of null values then removed that feature. You will be amazed that after this process I was left with only 73 features. And then......................<br/>

![Alt Text](https://tenor.com/view/pokemon-confused-psyduck-gif-5762799.gif)

# Approach:
 
It seems to be very challenging problem when you first encounter the dataset and you know what it is. This project for me was the most challenging and entertaining. 


# Refrences:
1. Data is available here https://www.kdd.org/kdd-cup/view/kdd-cup-2009 <br/>
2. Some research paper to read : <br/>
  a. http://proceedings.mlr.press/v7/guyon09/guyon09.pdf <br/>
  b. http://proceedings.mlr.press/v7/niculescu09/niculescu09.pdf <br/>
