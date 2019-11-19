# 95_778.Final_Project

This is the final project for CMU 18 Fall 95_778 R for Data Science.
Group members: Zhexin Chen, Shuting You and Xiaodi Tao.

# Explain data we chose


The datasets contain 142 features and 1 label (only for the training set). The datasets give comprehensive description of a household surveyed, and the features contain information about several aspects of important information of a household: including household finance, household items, house condition, family composition, education, and basic demographics. 


Below is a list of some representative features:


Household Finance:
  v2a1, Monthly rent payment
  ...
 
  
Household Items:
  v18q1, number of tablets household owns
  refrig, =1 if the household has refrigerator
  ...
 
  
House Condition:
  rooms,  number of all rooms in the house
  paredblolad, =1 if predominant material on the outside wall is block or brick
  ...
 
  
Family Composition:
  hhsize, household size
  tamviv, number of persons living in the household
  hogar_adul, Number of adults in household
  ...
  
  
Education:
  instlevel1, =1 no level of education
  ...
 
  
The label "Target" has 4 levels, coded as: "1", "2", "3" and "4", where “1” stands for extreme poverty and "4" stands for non vulnerable households.


The training set has 9557 observations and the testing set has 23856 observations. In order to obtain a higher accuracy on the testing set, on the one hand, our model should include as much information as possible, and on the other hand, we should restrict our model to be overfitting.


By the way, we find the data has already been dummified, like below:
lugar1, =1 region Central
lugar2, =1 region Chorotega
lugar3, =1 region PacÃƒÂfico central
lugar4, =1 region Brunca
lugar5, =1 region Huetar AtlÃƒÂ¡ntica
lugar6, =1 region Huetar Norte


# Business Question


Business Problem Overview: 
Inter-American Development Bank is working on a social program to aid impoverished individuals in Costa Rica. Impoverished individuals are usually unlikely to have direct financial documents(income or expenses) to prove that they truly need the aid. Current models (PMT), which take observable household attributes into account (eg.how many rooms in a house? how many households? )  still needs improvement in terms of prediction accuracy. Our team is working on solving these challenges and helping Inter-American Development Bank identify the most impoverished individuals to give aid to. 

The business questions we aim to address in our project are: 
What are the most important variables that goes into identifying household poverty level  
What model to recommend to improve household poverty identification accuracy for the Inter-American Development Bank to offer aiding programs to the people that are most in need. 





