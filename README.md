# Neural Generator of Crypto Signals (Especially solution for Quant Trading & Technical Analysis)

Track and analysis over 500 coins across Binance, Bittrex, Bitfinex, Coinbase, and more. 

## Technical Analysis Automated:
* Momentum
* Relative Strength Index (RSI)
* Ichimoku Cloud (Leading Span A, Leading Span B, Conversion Line, Base Line)
* Simple Moving Average
* Exponential Moving Average
* MACD
* MFI
* OBV
* VWAP

## Alerts:
* SMS via Twilio
* Email
* Slack
* Telegram
* Discord

## Features:
* Modular code for easy trading strategy implementation
* Easy install with Docker

You can build on top of this tool and implement algorithm trading and some machine learning models to experiment with predictive analysis.

## Installing And Running
The commands listed below are intended to be run in a terminal.

1. Install [docker CE](https://docs.docker.com/install/)

1. Create a config.yml file in your current directory. See the Configuring config.yml section below for customizing settings.

1. In a terminal run the application. `docker run --rm -v $PWD/config.yml:/app/config.yml xaindex/Neural-Generator-of-Crypto-Signals:master`.

1. When you want to update the application run `docker pull xaindex/Neural-Generator-of-Crypto-Signals:master`

## Configuring config.yml

For a list of all possible options for config.yml and some example configurations look [here](docs/config.md)

# Contact
Feel free to contact us if there is any question (tech@xaindex.ai).

