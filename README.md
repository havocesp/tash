# TAISH
_Technical Analysis Indicators for SHell environments_
## Description
Get some altcoin's assets technical analysis indicators result value from command line.

Now you can combine Technical Analysis Indicators with shell scripting or cron to execute actions based on indicators result.
## Data source
 _TODO_
## Requirements
- Python3 interpreter
- TA-Lib
- fire
- krakenex
## Basic usage
 **tash** indicator asset_pair _[arguments ...]_
## Example
Simple Moving Average for ETHEUR asset pair with 9 as period value:

 **tash** sma ETHEUR --timeperiod 9
