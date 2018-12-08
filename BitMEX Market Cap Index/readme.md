# BitMEX Market Cap Weighted Index

`BINANCE:ADAUSD^0.0266*BITTREX:BCHUSDT^0.0936*BINANCE:BTCUSDT^0.3152*BINANCE:EOSUSD^0.0613*BINANCE:ETHUSD^0.3152*BINANCE:LTCUSD^0.0353*BINANCE:TRXUSD^0.0169*BINANCE:XRPUSD^0.1359`

**Description**: An index of the derivatives on BitMEX weighted by market cap.



Methodology:
- Available supply * close price
- Bitcoin mcap adjusted to match ETH's to reduce its dominance in weighting.
- Source for supply and price: Coinmarketcap
- Source for candles: Binance + Bittrex
- Date used for weighting: 15 June 2018. An older date was used to have more valid historical data. Newer dates don't vary much.



[v1.0]Release - Candles/EMA + Stochastic.
- Made into an indicator so I would be able to view intraday + have stoch accessible on a BTC chart

[v1.1]Update  - 8 Dec. 18 - Replaced Binance BCH with Bittrex BCH due to depreciated BCH ticker.
- The 'real' value of BCH is ABC + SV but BitMEX will follow only ABC until expiry. 
  - Citation: https://blog.bitmex.com/site_announcement/bitcoin-cash-hardfork-policy-and-impact-on-bchz18/

