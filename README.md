# Football Positions: A Multi-class Classification Problem

Machine Learning Course Submission

Football is arguably the most famous sport with a global following of approximately 3.5 to 4 billion fans, and has the highest television audience in sports worldwide. It is a sport played with 11 players per team, each with a particular designation. In this study, the players are classified into 8 different position classes which are determined by the difference in roles and location of play inside the field.

The dataset consisted of players from the FIFA22 player database. Players from the top 5 European leagues were included in this study. These leagues are the English Premier League, Spanish La Liga, French Ligue 1, Italian Serie A and the German Bundesliga 1.

After filtering, 35 features were selected corresponding to different player abilities except for goalkeeping abilities. Each player has one or more corresponding position label, but for this study, the main player position was used as the official label and target variable. Goalkeepers were also excluded from the dataset because they were easily identifiable as they use a different set of player abilities. A total of 2650 players were used as our final data set.

See full report [HERE](https://github.com/mbdelaresma/football-position-classification/blob/main/FinalReport.ipynb)

![image](https://user-images.githubusercontent.com/71246479/188298459-04dbe876-c9b9-4200-a48d-c5d382d339c8.png)

# Highlights

1. Shannon Entropy balance can be used to determine the imbalance of a multi-class dataset.

2. Cost sensitive parameters like class weight can be used instead of sampling to address imbalance.

3. In this study, LIME method was more helpful in showing the local interpretability of the results.

4. Seeing the other possibilities for each class help establish the related positions with each other.

5. Ability improvement and position shift are some of the insights that can be derived from the study.
