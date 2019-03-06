# Expected-Goals-Analysis
An exploration of the season-long performance of expected goals models

In progress....

## Description

In association football (soccer) the most common advanced statistical metric is expected goals, which measures the probability that some action (whether shot or non-shot such as a pass) will result in a goal.  Due to the video technology required to calculate player position and other variables, most such data is proprietary.  However, some public sources do exist.  For example, FiveThirtyEight.com uses several expected goals metrics for their soccer predictions (shot-based and non shot-based) and publish their game data from time to time [here](https://github.com/fivethirtyeight/data/tree/master/soccer-spi).

As a beginning step, we access the FiveThirtyEight data and summarize it for each team over a season.  Becasue expected goals has variance game-to-game, we sum it up to reduce this variance and look at its correlation with actual goals scored over a season.  For comparison across different leagues, which can have differing numbers of games, we average all such data on a per game basis.

The summarization is done with Python in a Jupyter notebook.

Visualization is currently being constructed using Tableau Public.  It will be published when in more of a finished form.

## File Structure
 - The Resources file contains the data:
  + `spi_matches.csv` contains the raw data from FiveThirtyEight
  + `538_Season_Per_Game.csv` contains the summarized per game data for individual teams
 - The Python code contains the cleaning code
  + The individual notebook is entitled `xG_notebook.ipynb`
 - This file, `README.md` contains an explanation of the project


