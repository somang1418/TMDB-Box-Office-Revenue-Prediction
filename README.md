# TMDB-Box-Office-Revenue-Prediction

![photo](data:image/jpeg;base64,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)


**The Goal of the Competition:** <br>
Using metadata on over 7,000 past films from The Movie Database, I will predict their overall worldwide box office revenue <br>

**Simplified Version of How to Start with Gradient Boosting Models:**
1. Perform an Exploratory Data Analysis (EDA) on the dataset
2. Feature engineering: take the features that you already have and combine them or extract more information
3. Build a quick and dirty model, or a baseline model, which can serve as a comparison against later models that you will build
4. Monitor performance and early stopping for avoiding model fitting issues. Also take a look at feature importance of variables and check 5. whether the variables that you are seeing make sense
6. Tune parameters of models (I usually focus on tuning parameters for Tree Booster, such as eta, max_depth, min_child_weight).
7. Compare different models by metric (ex. RMSE)
8. Get a model that performs better!


My kaggle notebook: https://www.kaggle.com/somang1418/eda-lgb-xgb-modelings-with-a-cute-panda-meme
