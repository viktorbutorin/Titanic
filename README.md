Titanic Kaggle Solution

This a solution of popular "Titanic: Machine Learnig From Disaster" dataset. Method used is Random Forest, optimal parameters were found using GS. When submited, this solution scored at top-11%.

Features/Hypotheses analyzed, steps taken:

1) Correlation between numeric variables
2) Hypothesis #1: Women had a higher chance of survival
3) Hypothesis #2: Age affects survival
4) Hypothesis #3: Children had a higher chance of survival
5) Instead of age add four age groups: NaN, 0-15, 15-60, 60+
6) Hypothesis 4: Cabin location affected survival chances
7) Hypothesis 5: Title affected survival rate
8) Update NaN age values with mean of their Title group
9) Group titles into honored, mr, miss, mrs, master; apply one hot encoding to tiles
10) Hypothesis 6: Size of family affected survival rate; assign passengers to three categories of family size: 1, 2-4, 5+
11) Hypothesis 7: Port of embarkment does not affect survival rate; apply one-hot encoding for each port
12) Hypothesis 8: Fare affected survival rate; split fare into three groups: $0-10, $10-26, $26+
13) Run SelectFromModel to choose important variables
14) Run GS for RF
15) Fit model





