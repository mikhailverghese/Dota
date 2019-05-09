# Dota

This dataset is respective to all radiant picks from radiant won games extrapolated from the original kaggle Dota 2 Matches dataset by Devin 'https://www.kaggle.com/devinanzelmo/dota-2-matches'. 

We have then split, joined, pivoted, dummied, cleaned and preprocessed this data into a more efficient and usable format to perform machine learning algorithms mainly by extrapolating dummied binary hero columns to depict hero presence. 

These new datasets include:
radiantwins_5radiantpicks.csv which contains information regarding the 5 Radiant Team picks for all games where Radiant won. 

The first hero column 'Abaddon' has been dropped for ml purposes. 
Each record has five 1 values. If Abaddon is one of the heros then that record will have four 1 values.
