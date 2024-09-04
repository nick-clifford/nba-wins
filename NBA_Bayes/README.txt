Final project submission for DS 6014 Bayesian Machine Learning
University of Virginia School of Data Science Fall 2019
Dated: 9 December 2019
Authors: Nick Clifford, Brigitte Hogan, Kevin Malloy

Files

This folder includes the following files:
- README.txt [this file]
- bask_clean.csv [data set]
- NBA_A_ConjPrior.ipynb [code]
- NBA_B_Hierarch.ipynb [code]
- NBA_C_Overlay.ipynb [code]
- NBA_A_ConjPrior.html [html]
- NBA_B_Hierarch.html [html]
- NBA_C_Overlay.html [html]

Data

The data file 'bask_clean.csv' contains the results of regular season basketball games for 30 NBA franchises for the 2016-2017, 2017-2018, 2018-2019, and 2019-2020 seasons. The 'Wins', 'Loss', and 'Games' column indicates the number of games won, lost, and played, respectively, through December 5th of each season. The 'Final' column indicates the total number of games won over the entire 82 regular-game season (this data is missing for the 2019-2020 season). The 'Proj' column indicates the projected wins at the start of the season based on oddsmakers projections. This data was extracted from the following websites:
- https://www.basketball-reference.com/leagues/NBA_2019_standings_by_date_eastern_conference.html
- https://www.actionnetwork.com/nba/nba-win-totals-betting-odds-2019-2020
- https://www.si.com/nba/2017/08/30/nba-over-under-win-totals-all-30-teams-2017-2018-season
- https://www.foxsports.com/nba/story/2016-2017-nba-season-win-total-odds-and-predictions-092016

Code

Code is written in Python 3.7.4 using Jupyter Notebooks and are intended to be run in the order listed above, although they will run independently of one another. The file 'NBA_A_ConjPrior.ipynb' contains code for generating predictions using the conjugate prior approach. The file 'NBA_B_Hierarch.ipynb' contains code for generating predictions with a hierarchical model. The file 'NBA_C_Overlay.ipynb' contains code for providing a visual comparison of the two approaches. HTML versions of the code and output are provided for reference. 
