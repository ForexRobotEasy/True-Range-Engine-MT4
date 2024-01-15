# True Range Engine MT4

This is a night scalping expert advisor developed by the Forex Robot Easy Team. The True Range Engine MT4 utilizes a smart grid system and machine learning-based indicators to open and close positions during the night session.

## Features
- Night scalping: The expert advisor is designed to operate during the night session.
- Smart grid system: The order grid is dynamically adjusted based on the true range to optimize trading opportunities.
- Machine learning-based indicators: The expert advisor utilizes machine learning indicators to determine the direction of the market.

## Global variables
- `LotSize`: Initial lot size for opening positions.
- `GridSize`: Size of the order grid.
- `TakeProfit`: Take profit level for closing positions.
- `StopLoss`: Stop loss level for closing positions.

## Initialization
The expert advisor initializes by setting the timeframe to M5 and loading the machine learning-based indicators. It also initializes the order grid and sets the active order feature.

## Tick function
In the tick function, the expert advisor checks if it is the night session. If it is, it calculates the true range, adjusts the order grid, and opens positions based on the machine learning indicators. It also closes positions when the price reaches the take profit or stop loss levels.

## Additional functions
- `InitializeOrderGrid()`: Initializes the order grid.
- `DeinitializeOrderGrid()`: Deinitializes the order grid.
- `SetActiveOrderFeature()`: Sets the active order feature.
- `IsNightSession()`: Checks if it is the night session.
- `CalculateTrueRange()`: Calculates the true range.
- `AdjustOrderGrid()`: Adjusts the order grid based on the true range.
- `OpenBuyPosition()`: Opens a buy position.
- `OpenSellPosition()`: Opens a sell position.
- `ClosePositions()`: Closes positions.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample and may need modifications to work with the specific product. For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/true-range-engine-mt4-review-night-scalping-smart-grid-system/](https://forexroboteasy.com/forex-robot-review/true-range-engine-mt4-review-night-scalping-smart-grid-system/). To find the official developer of this product, please use MQL5.
