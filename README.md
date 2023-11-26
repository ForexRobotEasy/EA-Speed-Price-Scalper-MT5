# EA Speed Price Scalper MT5

This is an Expert Advisor (EA) called Speed Price Scalper MT5, developed by the Forex Robot Easy Team. It is designed for MetaTrader 5 (MT5) platform.

## Expert Advisor Parameters

- LotSize: The trading lot size.
- StopLoss: The stop loss value in pips.
- TakeProfit: The take profit value in pips.
- MaxSpread: The maximum allowed spread in points.

## Expert Advisor Initialization

The OnInit function is called when the EA is initialized. You can add initialization logic here.

## Expert Advisor Deinitialization

The OnDeinit function is called when the EA is deinitialized. You can add deinitialization logic here.

## Expert Advisor Start Function

The OnTick function is called on every tick. It processes the tick data and performs the trading logic.

1. It calculates the current price by getting the Ask price of the symbol.
2. It checks for high price fluctuations by comparing the absolute difference between the current price and the previous close price on the H1 timeframe.
3. If the price fluctuation is greater than 10 points (10 * Point), it opens pending orders.
4. If the current price is greater than the previous close price, it opens a BuyStop pending order with the specified lot size, stop loss, and take profit.
5. If the current price is lower than the previous close price, it opens a SellStop pending order with the specified lot size, stop loss, and take profit.

## Expert Advisor Program End

This is the end of the Expert Advisor program.

# Product Description

The EA Speed Price Scalper MT5 is an automated trading system developed by the Forex Robot Easy Team. It is designed to take advantage of high price fluctuations in the forex market. The EA opens pending orders when it detects significant price movements, aiming to capture quick profits.

Key Features:
- Works on MetaTrader 5 platform.
- Allows customization of trading parameters such as lot size, stop loss, take profit, and maximum spread.
- Uses pending orders to enter trades during high price fluctuations.
- Suitable for scalping strategy.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer and obtain the full version of this EA, please visit MQL5 marketplace. For detailed reviews and trading results of this product, you can visit [Forex Robot Easy's review page](https://forexroboteasy.com/forex-robot-review/review-ea-speed-price-scalper-mt5-real-results-and-monitoring/).
