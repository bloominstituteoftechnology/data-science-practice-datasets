# Detailed NFL Play-by-Play Data 2009-2018

Source: [Kaggle](https://www.kaggle.com/maxhorowitz/nflplaybyplay2009to2016)

Point of Interest: This is a great dataset to teach students about **leakage**. For instance, if I want to build a model that predicts whether a play in the redzone will result in a touchdown, I can't use features that describe the results of the play (eg. `'yards_gained'`). Rather, I can only use features that would be available to a model before the ball is snapped.