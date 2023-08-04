# football-players-data-analysis

## Description
This dataset contains stats for 10 football players from Europe's top leagues. You will use this data to solve the following problem statement.

## Case Study
Manchester United football club wants to know which player they should sign for the Striker position from the list provided. You need to perform a comparative Analysis between players and suggest two players whom they should sign.

**Additional Note:**
- One of the players should be less than 25 years of age
- One of the players should have preferably played in the English premier league

## Column name & description
![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/07ccc1bb-e001-4783-9eec-e5713b1be796)

- Player Name: Name of the player
- Age: The age of the player
- Current Club: Name of the club that the player currently plays for
- Opponent: Name of the team that the player played against
- Competition: Name of the competition.
- Date: Date of the match played
- Position: Playing position of the player
- Mins: Minutes played
- Goals: Total goals
- Assists: Total assists
- Yel: Yellow card
- Red: Red card
- Shots: Total shots
- PS%: Pass success percentage
- AerialsWon: Aerial duels won
- Rating: Rating per match

## Exploratory Data Analysis
- **Check the number of players with ages less than and greater than 25 years.**
   -  **Observation:** Six players with ages less than 25 years
  
![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/206f69f7-b750-4d1e-aa5e-119f063d87ae)

- **Check the number of players played in the English premier league.**
  - **Observation:** Three players have played in the English premier league

![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/00d05be1-467f-4823-b006-25694dbaef38)

- **Check the total number of goals & assists scored by each player**
   - **Observation:**
      - Victor Osimhen & Harry Kane are the top 2 in goals.
      - Randal Kolo Muani is at the top for assists.
      - Six players with goal contributions of more than 20.
    
![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/4f7f68a4-b08f-4cb2-a015-4a99642229c4)
   
- **Check the average no. of Shots, PS%, AerialsWon & Ratings per match by each player**
   - **Observation:** Top players based on, 
      - Avg. Shots per match – Mitrovic & Osimhen
      - Avg.  PS% per match – David, Ramos, Thuram, Højlund
      - Avg.  AerialsWon per match – Mitrovic, Toney
      - Avg. Rating – Multiple players

![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/81a7330d-3467-49ed-ac7d-d4710fc8621c)

- **Check the Mean, Median & Mode Ratings per match by each player**
   - **Observation:**
      - Not much difference between the players

![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/f9fa5d34-d164-446b-a7ae-27d7d033ecbd)

- **Check Variance & Std. Deviation for each player to find the player whose ratings vary the least**
   - **Observation:**
      - If the standard deviation is high, this means that values are typically a long way from the mean. If the standard deviation is low, values tend to be close to the mean
      - **Harry Kane** & **Dusan Vlahovic** are the players which Manchester United should target. Both players satisfy the criteria.

![image](https://github.com/aditigangar-dataanalystduo/football-players-data-analysis/assets/110927056/e765e74c-103d-43b1-8c5d-7905853211b6)


## Note
- This dataset belongs to @dataanalystduo. Unauthorized use or distribution of this project prohibited @dataanalystduo
- Dataset has been downloaded from the internet using multiple sources. All the credit for the dataset goes to the original creator of the data

**Link to dataset:** https://www.kaggle.com/datasets/kalpeshg0509/football-players-data
