# league-of-legends-data-analysis-and-prediction-model

This is the home for Keshava's thesis advancement and code.
The main focus of this project is doing a statistical analysis of the league of legends database obtained from oracle's elixir, this database contains most of 2020's league of legends professional matches with in depth fields to describe each game and it's outcome.

What i'm trying to do is find recurring patterns in each match in respect to the winner of each match, which implies data pre-processing such as eliminating un-important fields, dealing with missing values and aranging the database in such a way that it's easy to work with.

Another objective aside from finding recurring paterns is attempting to create a model to predict the outcome of matches based on the information found on the database.

As of this moment the project has only made it's first baby steps as only half the data pre processing has been done and i've only created a "draft" model to establish a baseline for future advancements and to confirm that the data present in this database is optimal to create a model to predict the results of each match.

The following files can be found as of this moment:
- 2020_LoL_esports_match_data_from_OraclesElixir_20201016.zip
  - this file is a zip containing the original oracles elixir database, it was compressed as a .zip file due to it's original size, it's required in case you want to replicate the results found on this project
- out.csv
  - this file is a momentary database it's only here as a backup in case my thesis assesor advices me to backtrack from certain advancements i've made on my own
- team_df.csv
  - this file is the "final version" of the teams only database, it's only a temporary file meant to be used to extract a baseline and determine if this database has optimal data for the project
- lol_df_creation.ipynb
  - this is where all the data pre-processing is being done and where you'll be able to find the code used to create the main database used for this project
- team_only_prediction.ipynb
  - this file is where you can find the process through which i found the basline for the project and where we determine wether this database is optimal or not
  
If you have any questions about the usage of this project you can contact me directly at keshava.t.s.b@gmail.com
