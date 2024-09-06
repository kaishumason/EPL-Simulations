# EPL-Simulations
My submission to the CMSAC reproducible research competition. The order in which the code should be run for my analysis is 
+ goal_timing_EDA.ipynb: Exploratory data analysis of goal timings in EPL games from 2015 to 2022
+ data_cleaning_and_wrangling.ipynb: Aligns FIFA game match summaries,events, shots, and FIFA ratings to a common ID
+ xg_prediction.ipynb: Models expected goals(xG) as a function of game state parameters such as players on the field, half, score differential, etc...
+ hazard_function.ipynb: Validates a weibull model for the time between goal scoring events for individual teams
+ copula.ipynb: Fits a gaussian copula to model the correaltion between goal scoring times for competing teams. Uses this joint distribution to simulate games.
+ substitution_analysis.ipynb: Using the simulations in copula.ipynb, analyses the effect of substituions on the win probability of a team.

If one wants to run a notebook out of order, the corresponding pkl files are available. However, one must unzip the all_fifa_player_ratings.pkl.zip file in the data folder.
