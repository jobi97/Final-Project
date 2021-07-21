# Final-Project
Boot Camp Final Project
Boot Camp Final Project Justin O'Brien: predicting whether the state voted for trump or biden based on vaccination rates, infection rates, polling data on vaccine willingness, statewide vaccine supply used, poll data on willingness to wear a mask in public. Being someone who believes in science, covid politics has always been something that is very interesting to me.  Looking into a few different factors that would contribute to the spread of covid and how the population feels about certain preventative measures should be sufficient enough to be able to predict which way the state voted in the 2020 election.

## DATA BASE 
Using sql, i will build a relational database from all the data i will be collecting. A large amount of the work will be extracting the data that is needed from the csv files that i have pulled. Some are much more expansive than needed. I will also likely have to build the tables for poll data and election results because they are not available as a csv. this wont be difficult and the primary keys will be the states (for mask data, vaccine willingness data, and the 2020 election result data). primary key of States will be essential becasue we will have to merge all the tables created on the state column. once everything is cleaned and pulled into one large dataset, we will then be able to perform any type of analysis we would like within SQL.

## machine learning
Plan is to perform similar analysis to what was done in our supervised learning module.  After that module, it appeared as though the two ensemble methods were the most successfull in classification.  I will use the random forrest and adaboost classifiers and see which one is more accurate at predicting which candidate the state voted for.  
