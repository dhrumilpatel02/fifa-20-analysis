# FIFA Players Analysis

#### Project Status: [Active]

## Objective
The purpose of this project is to determine which attributes a footballer needs in order to excel in a particular position (Defense/Midfield/Attack).

### Methods Used
* EDA
* Machine Learning
* Data Visualization
* Classification Algorithms (k-NN, Decision Tree, Neural Nets Classifer)

### Technologies Used
* Python (pandas, numpy, seaborn, matplotlib, plotly, scikit-learn)

## Project Description
* Data Source- Kaggle (FIFA 20 complete player dataset).  
* Details- The data source consisted of footballers data from the FIFA 15 to FIFA 20. All the datasets from the years had the same format so it was easier to connect them all.  
* EDA- The EDA consisted of looking at which were the best players in the game when fitted in a particular formation (4-4-3/3-5-2). Next, I pulled up the ratings and financial value of players from a particular club (Manchester United) and what is their potential rating in the game is. Next, I plotted the current and potential rating of the Top 5 Players in the games to a line chart to show the rise/decline over the last 5 years.  
* Model- First, I normalized the main attributes by the player's overall rating. This gave me the relative strength of the player rather than comparing the absolute strength between players. Second, I fit the data and try to predict the best position for each player given the relative strength of those players, through a confusion matrix.  

## Findings
* Central Defenders: Physic, that can protect the ball or go toe to toe with a striker when needed
* Full/Wing Backs: Defending and dribbling skills, that can stop the counterattacks and start their own.
Central Midfielders (Defensive and Attacking): Passing and dribbling skills, they remain the focal point in the line up that connect every other player.
* Left or Right side Midfielders: Good passing skills and shooting skills, they spray diagnals and long balls to strikers after receiving pass from the back of central Midfielders.
* Wingers and Inside Forwards: Shooting skills with fast pace, they support the striker in every sense and chip a few goals when needed, Shooting accuracy and pace helps in scoring.
* Centre Forward: Dribbling to get past defenders and shooting skills to finish the throught balls provided, good physic can give you extra advantage to crush the defenders in the air!
