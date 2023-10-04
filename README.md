# BTC_Market_Simulation
Simulate BTC prices and generate traders based on Geometric Brownian Motion

The model works in the following way:
1. Input parameters are set to prepare GBM for price generation
2. The GBM is run to generate the BTC prices
3. Based on the generated prices, script generates traders and their deals based on user's preferences (inputs) (e.g. number of deals per trader)
4. The final result is presented in pandas DF and contains generated trader's address, block number, input currency, output currency, timestamp and price changes before/after 52 hours for potential event study.
