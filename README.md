# Predicting 2018-2019 EPL Player Salaries Using Neural Networks

## Dataset Overview
* We will be using a 2018-2019 English Premier League Players Dataset provided by https://footystats.org/download-stats-csv#whats_included
* The original dataset did not include any annual salary feature, so additional 2018-2019 salary data from was web scraped and joined to the existing dataframe to get a complete dataset https://www.spotrac.com/epl/rankings/2018/
* The datasets are both cleaned and stored in the folder CleanData listed above 

## Data Description
![](images/Data_Overview.png)

## Data Sample
![](images/dataframe_head.png)

## More Info
Listed above are folders that include various items: 
* The RawData folder includes the raw data for the players dataset and the salary dataset. 
* The CleanData folder includes the clean datasets for the players concatenated with salary dataset and the non top 4% in salary dataset. 
* The plots folder includes the Exploratory Data Analysis Visualizations and some will be listed below. 
* Lastly the notebook folder includes the jupyter notebook with all of the code to run for yourself. Enjoy!

# Exploratory Data Analysis

To gain greater insight into our label annual_salary, here is the distribution: 

![](plots/annual_salary_dist.png)

As we can see most players are paid $5 million and less




Now let's see which features have mild, strong, or no correlation with annual salary

![](plots/correlation_heatmap.png)

We can see that most features have a positive effect on a player's salary with factors such as goals_overall and clean_sheets_overall leading the way.




Let's take a look at the clean_sheets_overall feature and see where most players

![](plots/clean_sheets_count.png)

Most players never achieved a clean sheet throughout the season, while some players obtained 20 or more clean sheets.




Let's delve deeper and look at leaguewide in respect to which teams carry a certain amount of each position

![](plots/position_team_distribution.png)

We can see that most teams carry about the same number of each position




Most notably teams spend a certain amount on their players, so here is a disribution of salary spent by team

![](plots/












