# teaching-support

Support for using the Fragile Families Challenge as a teaching tool in courses

For students who download the FFChallenge_v5 file from the OPR Data Archive, this repository contains code that will read background.dta and train.csv and save a simplified version of those data, called example_prepared_data.

That example file contains 37 variables: the challengeID identifier, 29 background variables, the 6 outcome variables, and a variable named "set" which indicates which observations are part of the training data (for which outcomes are available if observed) and which are part of either the holdout or the leaderboard data (for which outcomes are NA).

Here are some other things that might be helpful in your classes.

- Videos from Fragile Families Challenge Scientific Workshop: https://www.youtube.com/channel/UCjluzrRT8fqXCx3qHjQAb5A
- Podcast about the Challenge: https://www.npr.org/programs/invisibilia/597779069/the-pattern-problem
- Fragile Families Challenge Blog (many helpful posts): https://www.fragilefamilieschallenge.org/blog/
- Some slides about Challenge: https://github.com/fragilefamilieschallenge/slides
- Special issue of Socius about the Challenge: https://journals.sagepub.com/topic/collections-srd/srd-1-fragile_families/srd

It is no longer possible to use our hosted leaderboard. The code for our leaderboard is [here](https://github.com/fragilefamilieschallenge/codalab-competitions).
