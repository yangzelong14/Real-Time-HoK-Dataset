# Tencent AI Lab Real-Time Dataset for Honor of Kings, a Popular Mobile MOBA Esport
A sample dataset for real-time MOBA game prediction.
## Introduction
Honor of Kings (HoK) is one of the world's most popular and highest-grossing MOBA game, attracting more than 80 million daily active players and 200 million monthly active players. This sample dataset contains 100 HoK games, which are randomly chosen from the 184,162 games in the full dataset to be released in the camera-ready version. This dataset can be used for real-time win prediction for MOBA esports.
## Data Description
View the sample dataset from: https://github.com/yangzelong14/Real-Time-HoK-Dataset/raw/master/hok_sample_100.json.
Each line in the file corresponds to one game's data. The data is sampled every half minute. At each time-point, there is data from both the "losecp" and "wincp", where "wincp" is the team that eventually won this game and "losecp" is the team that lost. In both "losecp" and "wincp" fields, there are data fields such as "num_baron", "hero" and so on.
## Highlights
There are several highlights about our dataset:
1. To ensure the quality of games, only Conquerors-level games whose participants are top 1% players are collected.
2. The dataset is large-scale and containing rich real-time features.
## Final Words
Thanks for using our dataset! The current dataset is a sample dataset containing 100 sample games. In the camera-ready version of our work submitted to CIKM2020, we will release the full dataset that contains the anonymized information of all the 184,362 games that happened within a randomly chosen day in June 2019 from the official game database. Prior experiments for data scale indicate that one day's data is sufficient for the prediction task.
## Contacts
If you have any question, please contact us: yangzelong14@gmail.com
