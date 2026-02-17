This project focuses on analyzing historical IPL data to extract meaningful insights about player performance, team statistics, and match outcomes. The analysis was performed using Python for data cleaning, MySQL for querying, and Power BI for interactive visualization.

The dashboard highlights key metrics such as:
  Top batsmen by runs and strike rate
  Best bowlers by wickets and economy
  Top all-rounders based on combined performance
  Team performance across seasons
  Match trends and outcomes

The goal of this project was to simulate a real-world data analyst workflow, starting from raw datasets to building a professional interactive dashboard.

Step 1: Data Collection

Collected IPL datasets containing:
  Match details
  Ball-by-ball data
  Player statistics

Files used:
  match_data.csv
  match_info_data.csv

Step 2: Data Cleaning (Python)
Performed preprocessing using Python:

Key steps:
  Removed null and duplicate values
  Standardized team and player names
  Converted data types
  
  Created new calculated columns:
    Total runs per ball
    Wickets taken
    Batting averages
    Strike rates
    Economy rates

Step 3: Feature Engineering
Created new metrics:
For batsmen:
  Total runs
  Strike rate
  Average

For bowlers:
  Wickets taken
  Economy rate
  Runs conceded

For all-rounders:
  Combined batting and bowling performance

Step 4: Power BI Dashboard Creation

Imported processed datasets into Power BI.
Created:
  KPI cards
  Bar charts
  Leaderboards
  Player performance comparisons
  Team statistics visuals

Step 5: Dashboard Design

Focused on:
  Clean layout
  Clear color coding
  Easy-to-understand visuals
  Interactive filters for teams and players  

Key Insights from the Project
You can adjust these slightly after viewing the final dashboard.

Player Insights
  Identified the top 20 batsmen based on total runs and strike rate.
  Found the most economical bowlers with consistent wicket-taking ability.
  Highlighted the top all-rounders who contributed in both batting and bowling.

Team Insights
  Certain teams showed higher win percentages across seasons.
  Teams with strong all-rounders had more consistent performances.

Match Insights
  Higher strike rates strongly influenced match outcomes.
  Teams with lower economy bowlers performed better defensively.
