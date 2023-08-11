![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)


# Final-Project

## Dependencies

- FinRL
- Python 3.7
- Alpaca SDK

  ## Overview
  # Ensemble Strategie A2C DDPG PPO Method

First, a disclaimer - Do NOT invest any money in any type of trading bot or algorithmic engine that you are not willing to lose.

The google collab notebook Pulls trading data for (DJI) with Yahoo Finance Downloader API
It Creates a simulated trading environment using real trading data with FinRL
Trains an neural network to predict that Stock Price using reinforcement learning inside this simulation with FinRL
Once trained, backtests the predictions on the past years data to compute potential returns with FinRL

Unfortunately there are some problems and discrepancies with FinRL and the Backtesting software, so that I wasnt able to get all the insights, and the Google Collab notebook started crashing multiple times, which lost the data.

This will require a lot of work to get all of the insights on point, but the Neural Network Machine learning model works and produces a well trained modell, which need minor improvements in its parameters.

The requirements file is empty because everything will be installed via google collab notebook.

The File has to be imported into a Google Collab Notebook, where it will be mounted and then executed.
