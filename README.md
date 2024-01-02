# PeakBottom EA

PeakBottom EA is an expert advisor developed by the Forex Robot Easy Team. This EA is designed to identify and trade market peaks and bottoms.

## How it works

The EA uses two global variables, `previousPeak` and `previousBottom`, to store the previous peak and bottom values respectively. 

In the `OnInit` function, the necessary indicators and variables are initialized. 

In the `OnTick` function, the current market price is obtained using the `MarketInfo` function. The EA then checks if the current price is a new peak or bottom by comparing it with the previous values.

If the current price is higher than the previous peak, the EA implements the peak strategy. Similarly, if the current price is lower than the previous bottom, the EA implements the bottom strategy.

After implementing the relevant strategy, the previous peak or bottom value is updated with the current price.

Finally, the trading logic can be added based on the peak and bottom strategies.

## Product Description

PeakBottom EA is a low-risk and profitable forex trading tool. It is designed to identify and trade market peaks and bottoms, allowing traders to take advantage of potential profit opportunities.

This expert advisor is developed by the Forex Robot Easy Team, a well-known and reputable team in the forex trading community. Please note that ForexRobotEasy is not the official developer of this product. The sample code provided here is for demonstration purposes only and may not be the exact code used in the official product.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/peakbottom-ea-review-low-risk-profitable-forex-trading-tool/). 

To find the official developer of this product and to obtain the official version, please use MQL5.
