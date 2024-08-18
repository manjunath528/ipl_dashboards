Here I have created the dashboards for the data that I have previously processed from the snowflake .

**Project Overview:**

This project involves the creation of interactive Tableau dashboards that provide insights into the analysis of the ipl cricket history and the players historical details. The analysis explores trends, patterns, and other data points that can be used to derive meaningful conclusions about ipl cricket and all about the player details like their performance in the ipl whole history.

**Datasets Used:**

 I have used the datasets that have previously cleaned and prepared from the json data using the snowflake and the tables include the two fact tables and 10 diamension tables .
 Link fir the datasets is: 
 [my previous work on cleaning data](https://github.com/manjunath528/ipl_data_processing_sf/tree/main/5.final_csv_files)

Tables are: 
1. Match_Fact ,which includes the complete details about the match.
2. Delivery_Fact , which include the all the details about the each delivery in the ipl.
3. Finally we have different diamension tables wich stores the details about the team_details, season_details, venue_details etc,

**Objective:**

 The primary objective of this project is to:
1. Provide an interactive and user-friendly way to explore data related to ipl cricket.
2. Provide the details about the all the players of the ipl cricket .
3. Provide the details of the each season historical data like total sixes in that tournament , total fours etc,
4. Provide the details about the player details like total runs, top 10 perforamnces in his ipl history etc,

**Dashboards:**
     
Here I have created 2 Dashboards each dashoborad has its own meaningful insights.
1. IPL Seasonwise Dashboard:
Here it says the complete details about the seasonwise data, it includes the sheets like
    1. Total Runs Scored in the entire season
    2. Total Sixes hit in the entire season
    3. Total Fours scored in entire season
    4. Total Wickets fall 
    5. Map, saying the details about the total matches held in each venue and their historical backgorund
    6. Top 10 Batsmen with highest socre
    7. Top 10 Bowlers based on wickets they took
    8. Team with highest runs scored in a single match
    9. Player with best spell in entire season
    10. Player with the highest individual score in single match
    11. Points table of the teams performances
Finally the dashboard looks as below:
       ![1](https://github.com/user-attachments/assets/5cbb45af-e680-47c7-9e09-471412467b3b)

2. Player Dashboard:
Here we can find the all details about the each player who represented in the ipl cricket like
    1. Title which stores the details like player name and class he belongs and the strike rate of the player navigation to the first dashboard
    2. 3 KPI's providing the details about the total runs he scored, sixes , fours and wickets took in his ipl career.
    3. Map to provide the details about the his performance in each venue he played.
    4. Top 10 perforamnces as a batsmen
    5. Top 10 performances as a bowler 
    6. Total matches that he played for each team in his ipl career
    7. Player best spell as bowler
    8. Player highest score in his ipl career
Finally the dashboard looks as below:
     ![Dashboard2](https://github.com/user-attachments/assets/2506bcf4-d643-4b43-a67b-9be421065763)


**Technologies Used:**
    Tableau: For data visualization and dashboard creation.
    Snowflake/Excel/SQL : For data cleaning, transformation, or any pre-analysis steps.
    Data Sources: [main source](https://cricsheet.org/downloads/ipl_json.zip)


**Conclusion:**

The IPL Cricket Dashboard project provides an interactive platform to explore the rich history of the Indian Premier League. By analyzing both season and player performances over the years, the dashboards offer valuable insights into various aspects of the tournament, such as top-performing players, season statistics, and match outcomes. Users can easily filter and interact with the data to uncover trends, such as which player consistently perform well, which players dominate in batting or bowling, and how these performances have evolved across different IPL seasons.

This dashboard serves as a comprehensive tool for cricket enthusiasts, analysts, and decision-makers who want to dive deep into the nuances of the IPL. The insights can help in better understanding player potential and overall tournament dynamics. Future work could include adding predictive analytics to forecast outcomes or integrating live match data for real-time insights.

Ultimately, this project showcases the power of data visualization in making complex cricket data accessible and actionable, transforming raw numbers into stories that captivate the cricketing world.
  
    

