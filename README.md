# Best 11 for T20 World Cup 🏏 
This project is about find the best combination squad for T20 World Cup, players should be able to score 180 runs in an innings and be able to defend 150 runs on an Average

## Roadmap

1. Collection of Data from ESPN CricInfo Website for T20 Matches held between 2020 to 2022.

2. Converting an unstructured JSON to CSV, Performing Data Cleaning such as Removing the NULL values and unwanted data. 

3. Adding the columns such as Stage column in Matches Table for dividing data in Group Stage
and World Cup Matches then boundary runs in Batting and bowling Info Table.

4. Creating Measures for Total Runs, Total Innings, Batting Average, Bowling Average, 
Overall Strike Rate, Total bowls faced, Average Batting Position, Boundary%, Total Wickets,
Total Runs Conceded, Bowling Economy, Bowling Strike Rate, Bowling Average.


## Criteria Used for Filtering Players

1. Openers Criteria:-
   - Should have batting average above 30
   - Strike Rate should be greater than 140
   - Total Innings batted should be greater than 3
   - Boundary percentage should be greater than 50%
   - Average Batting Position should be less than 4

2. Anchors / Middle Orders:-
   - Should have batting average above 40
   - Strike Rate should be greater than 125
   - Total Innings batted should be greater than 3
   - Average Balls Faced should be greater than 20
   - Average Batting Position should be greater than 2

3. Finishers / Lower Order Anchor:-
   - Should have batting average above 25
   - Strike Rate should be greater than 130
   - Total Innings batted should be greater than 3
   - Average Balls Faced should be greater than 12
   - Average Batting Position should be greater than 4
   - Innings Bowled is greater than 1

5. All-Rounders / Lower Order :- 
   - Should have batting average above 15
   - Strike Rate should be greater than 140
   - Total Innings batted should be greater than 2
   - Average Batting Position should be greater than 4
   - Innings Bowled is greater than 2
   - Bowling Economy should be less than 7
   - Bowling Strike Rate should be less than 20

6. Specialist Fast Bowlers:-
   - Innings Bowled should be greater than 4
   - Bowling Economy should be less than 7
   - Bowling Strike Rate should be less than 16
   - Bowling Style of the Player should contain "FAST"
   - Bowling Average should be less than 20









## Tables of Player Stats:

1. Batting Info Table :-
    This table contains batting data for players who played in matches between 
    2020 to 2022. This table contain data for runs, balls, fours, sixes, strike rate
    etc for every batsmen played.

2. Bowling Info table :-
    This table contains bowling data for players who played in matches between 
    2020 to 2022. This table contain data for overs, runs, maidens, wickets, economy etc
    for every bowler played.

3. Bowling Info table :-
    This table contains bowling data for players who played in matches between 
    2020 to 2022. This table contain data for overs, runs, maidens, wickets, economy etc
    for every bowler played.

4. Player Info table :-
    This table contain player information which contains Team, batting style, bowling style
    playing role, image and description of the player

5. Match Info table :- 
    This table contain match information which is team names, winner, margin, ground and
    Date.



## DAX Functions Used

SUM(), COUNT(), AVERAGE(), DIVIDE(), ROUND(), DISTINCTCOUNT(), ISFILTERED(), IF()




## Tech Stack

**Tech:** Python, PowerBI Desktop, Dax, PowerBI Service, Jupyter Notebook

## Batting Chart

![image](https://github.com/amitkumargoyal1990/T20-World-Cup-Cricket-Data-Analytics/assets/90434295/fcc2dd54-54be-4b67-aa5a-bc4e13a8f39a)


## Bowling Chart

![image](https://github.com/amitkumargoyal1990/T20-World-Cup-Cricket-Data-Analytics/assets/90434295/8b8b354e-b08f-4574-ada8-0c19059f4adb)


## Player Chart

![image](https://github.com/amitkumargoyal1990/T20-World-Cup-Cricket-Data-Analytics/assets/90434295/98ef6e90-901a-4ef1-9e71-33a04c1f78cc)


## Selected Playing 11

![image](https://github.com/amitkumargoyal1990/T20-World-Cup-Cricket-Data-Analytics/assets/90434295/d2baace2-029d-442f-b62c-fab7d5160480)



### Conclusion
Web Scrapping and Analysing data. Data transformation in power query.
PowerBI Chart creation. Adding Measures using DAX Functions. Adding Filters
and selecting Final 11.

