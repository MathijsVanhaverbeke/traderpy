# Traderpy

Welcome to the traderpy repository! This repository was created to exploratively test whether a buy and hold strategy weightedly copying Congress members' trades would be more profitable than simply investing in the S&P 500 index.

Current results show that there is no large performance difference, with the copytrading strategy even underperforming slightly. One explanation, however, might be that this is because there is currently no limit to the stock holding period, possibly overshooting the optimal period to sell. Because of this, in a next step, I'll try to add scraped short trade data from congress members to the strategy, to try to include a dynamic holding period definition (also posing a lower limit to avoid daytrading-like behavior).
