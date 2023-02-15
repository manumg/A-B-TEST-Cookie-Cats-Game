# A-B-TEST-Cookie-Cats-Game
A/B Testing the puzzle mobile game Cookie Cats
PROJECT DESCRIPTION:
In this project I do an A/B test on a dataset from a mobile game called Cookie Cats. This dataset is from a DataCamp project, but the dataset has been publishedin Kaggle. I do not have a Datacamp account, I have used the public dataset from Kaggle. Link to the dataset:
https://www.kaggle.com/datasets/yufengsui/mobile-games-ab-testing?datasetId=272421&sortBy=voteCount

Cookie Cats is a puzzle game. As players progress through the game, they will encounter gates that force them to wait some time before they can progress or make a purchase. In this project we analyze the result of an A/B test where the first gate of Cookie Cats was moved from level 30 to level 40.

Data Description:
The data is from 90,189 players that installed the game while the AB-test was running. The variables are:

-userid - a unique number that identifies each player.

-version - whether the player was put in the control group (gate_30 - a gate at level 30) or the test group (gate_40 - a gate at level 40).

-sum_gamerounds - the number of game rounds played by the player during the first week after installation

-retention_1 - did the player come back and play 1 day after installing?

-retention_7 - did the player come back and play 7 days after installing?

When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.

Project Plan:

INDEX 

1.Import packages and data

2.Exploratory data analysis

3.A/B Test

4.Bootstrapping

