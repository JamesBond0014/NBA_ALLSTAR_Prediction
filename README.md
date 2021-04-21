# NBA_ALLSTAR_Prediction

This repo contains our version of TabNet, which attempts to train on 20 NBA seasons worth of player statistics in order to predict who will be selected into the NBA All-Star game every year. 

## Data Extraction
extract_data.ipynb contains the code to scrape players statistics and All-Star information from NBA.com, this will ultimately generate ASG_data.csv which will be used to train our models

## Model
NBA_TABBET.ipynb contains the code where we run train our Tabnet model using various experiments and evaluate each experiment. 

NBA_SVM.ipynb contains the code where we build a quick SVM model to compare against our TabNet model. 
