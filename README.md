# FantasySports-Analytics :basketball:

### DS 6410: Machine Learning II
#### Final project
#### Team: Jade Preston, Zack Jackoes, and Karolina Naranjo

This repository contains code for running a Gaussian process and linear optimization on fantasy basketball data. The data used in this repository is sourced from Kaggle and Yahoo Sports.

## Getting Started
* To execute the Gaussian process, you will use `FantasyGaussian` and launch two files. First, initiate the historical data `playerGameData.csv`. Second, you should start the playoff data for teams `playoffData.csv`. In our case, we played with four teams: Miami Heat, NY Knicks, Golden State Warriors, and LA Lakers.

Once you have executed the Gaussian process, you can check your results with our linear optimizer. To do this, use the file `line-upLP` and take the datasets `player_historical_info.csv` and `sixGamePlayoffwindow.csv`. Then, initiate it to check the results and see if you can win with your fantasy team :money_mouth_face:!

## Running the Code

1. Open `FantasyGaussian.ipynb` 
2. Execute `python playerGameData.py` to process historical player data.
3. Launch `python playoffData.py` to process playoff data for the selected teams.
4. Initiate `python line-upLP.py player_historical_info.csv sixGamePlayoffwindow.csv` to check your results with the linear optimizer.


## Requirements 
- `Python 3.x`
- `Numpy`
- `Pandas`
- `matplotlib`
- `Scipy`
- `pulp`



