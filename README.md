# Trading bot running on Bybit, Binance, OKX and Bitget

:warning: **Use at own risk** :warning:

v5.9.0


## Overview

Passivbot is a cryptocurrency trading bot written in Python, intended to require minimal user intervention.  
It is observed that prices in a market will fluctuate up and down, creating opportunities for capitalizing on the noise.  
The bot's purpose is to automate the harvest.

It operates on spot or futures markets by listening to websocket stream of live trades,
automatically creating and cancelling limit buy and sell orders.

Because passivbot's live behavior is deterministic, it may be simulated on historical price data, using the included backtester.  
Also included is an optimizer, which finds better configurations by iterating thousands of backtests with different candidates.  

The strategy is integrated -- the bot only needs a predefined configuration to run.

## Requirements

- Python >= 3.8
- [requirements.txt](requirements.txt) dependencies

Solana Tether USD (USDT):  
9hUCHBQA261PU6rUSbwgMoxn8nrdcXPAYgbASRgA8dtm

Monero (XMR):  
49gUQ1jasDK23tJTMCvP4mQUUwndeLWAwSgdCFn6ovmRKXZAjQnVp2JZ2K4UuDDdYMNam1HE8ELZoWdeJPRfYEa9QSEK6XZ

Bitcoin (BTC):  
bc1qcc3kr9gudg35gnsljg64zeaurt0y24pfej36w6
