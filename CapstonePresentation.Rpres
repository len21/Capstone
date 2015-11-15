Data Science Capstone - Final Presentation
========================================================
author: Moira Lennox
date: 22 November 2015

Introduction
========================================================
The goal of this project was to come up with a question or problem that was of interest based on Yelp data, and to answer it by exploring and researching the relationship between sets of variables and files. My question was “Can the data show there is an increase in welcoming pets into various businesses?” I used the variable "dogs allowed" from the business file and since there was no variable about increase in welcoming pets, I created a variable called “petcount” by data mining the review text and looking for references to the words "pet" or "dog".  I narrowed my focus to two main categories, hotels and restaurants, and reviewed data for years 2008-2014.

I compared businesses that allow dogs with the new “petcount” variable. I looked for a correlation to the variable to see if I could use other variables as predictors and then looked at locations as well.


Methods and Data
========================================================
Multiple linear regression was used to model the relationships after investigating how the variables were related to one another. I did this graphically by constructing scatter plots of all pair-wise combinations of variables in the data frame. 

I tried three different models from the GLM family using the variables from the scatter plot that looked like good candidates.

* GLM Poisson (link=log) model
* Zero-inflated base model
* Zero-inflated negative binomial model

Based on my analysis and review of the best model fit, I chose the Zero-inflated negative binomial model for modeling the data. This model works well for count variables with excessive zeros. 


Results
========================================================
There is a general increase in the “petcount” mean showing and an overall increase year over year.  In 2008 the mean for petcount was 0.94 and in 2014 was 4.29. The variables “revcount” and “voteusefulcount” showed the strongest correlation to percount, however they were not very strong at 0.56 and 0.47 respectively.

For country location, the UK shows an increase on the average pet count by 2.25 times, followed by USA at 1.51 times.


Discussion
========================================================
I took a very simplistic approach and extracted words like "pet" and "dog" to create a new variable from the review text data so it could be researched. That said I do believe having better designed data elements would almost always guarantee better results. Even thou there was not a very strong correlation between the “petcount” and the other predictors, there seems to be some indication that there is an increase in commentary around pets in hotel and restaurant businesses. This could lead us to believe that this indicates an increase in pet-friendly places.

For country location, the UK showed a stronger correlation than the USA and led all other countries.
