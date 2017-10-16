# TASH: Technical Analysis Indicators from SHell

## Description
Tash provide is a pure python 3 altcoin exchanges assistant project mostly who provides exchanges pairs assets calculation results based on Technical Analyslis Indicators.

This project made possible get some altcoin's assets technical analysis indicators result value from command line. 

It is shell scripting friendly it should be useful for Shell Scripting Algorithmic trading. Combine Technical Analysis Indicators with shell scripting (or with cron) to execute actions based on indicators result.

## Python 3 requirements
- TA-Lib (this require a C++ TA-Lib install also)
- fire
- krakenex

## Basic usage
 **tash** indicator asset_pair _[arguments ...]_
 
## Example
Last 3 Simple Moving Average, Relative Stregth Index and Money Flow Index candles for ETHEUR pair (using OHLC 15 min candles):

 **tash** ti sma rsi mfi XETHZEUR --interval 15 --output-limit 3
