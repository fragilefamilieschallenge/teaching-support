# teaching-support

Supporting for using the Fragile Families Challenge as a teaching tool in courses

For students who download the FFChallenge_v5 file from the OPR Data Archive, this repository contains code that will read background.dta and train.csv and save a simplified version of those data, called example_prepared_data.

That example file contains 37 variables: the challengeID identifier, 29 background variables, the 6 outcome variables, and a variable named "set" which indicates which observations are part of the training data (for which outcomes are available if observed) and which are part of either the holdout or the leaderboard data (for which outcomes are NA).