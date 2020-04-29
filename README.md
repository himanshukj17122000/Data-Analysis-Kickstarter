### What Makes a Successful Project Idea in the USA?

For this project we decided to use the kickstart Dataset from Kaggle. There are 
323750 rows and 13 relevant columns in this dataset. Kickstarter is a global 
crowdfunding platform where different products can be listed in different 
categories like music, arts, technology etc. Till date, the company has received
over $4.6 billion in funding from almost 17.2 million backers. We believe that 
it would be interesting to analyze the data from this company to recognize the
reason behind its success and how useful it might be for upcoming projects.

Our general research question to find out what are the most important factors in contributing to the success of a startup project in the United States. Our 
dataset is comprised of the statistics from over 300,000 Kickstarter proposals, 
collected directly from the Kickstarter Platform (found on Kaggle). It includes 
variables that could be essential to determining the success of a startup such 
as, the amount of money pledged to a startup, the number of backers the 
projecthas, or the industry the company is in. The key variable we are looking 
at is the binary variable called "state", which shows which startups were 
successful and which failed. This will be our response variable in the analyses.

We hypothesized that the variables pledged, the amount of money pledged to a 
project, goal, the amount of money a project orginally wsihed to raise, backers,
the number of backers/supports a project has, and main category, the general 
category or industry the idea falls under, would be the most important variables
in determining state.

 By using both a logistic model and k-nn model to determine the prediction 
 accuracy of using these variables for determing state, we discovered that 
 pledged and goal were the two key variables in determing state, and whose 
 values could predict whether or not a project failed with 95% accuracy using 
 the k-nn model and an apparent almost 100% using the logistic model.
 
 In conclusion, when starting a project the values of your goal and pledged 
 numbers are essential, and the relationship between the two is as well. While, 
 pledged does not necessarily have to be greater than or equal to goal for a 
 project to succeed the two variables must at least be very similar. A project 
 with a large goal but relatively small amount of money pledged will almost 
 certainly fail. 
