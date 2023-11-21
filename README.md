# Spread Meter mt4

Spread Meter mt4 is a custom indicator for MetaTrader 4 that displays the current spread on the chart. This indicator helps traders monitor the spread of their chosen currency pairs in real-time, allowing them to make informed trading decisions.

## Indicator Properties

- `indicator_chart_window`: The indicator will be displayed in a separate chart window.
- `indicator_buffers 3`: Three indicator buffers will be used to store the spread data.
- `indicator_color1 Green`: The color of the first buffer will be green.
- `indicator_color2 Red`: The color of the second buffer will be red.
- `indicator_color3 Blue`: The color of the third buffer will be blue.

## Indicator Initialization Function

The `OnInit()` function is called during the initialization of the indicator. In this function, we set up the indicator buffers and assign them to the indicator.

## Indicator Iteration Function

The `OnCalculate()` function is called for each new tick received by the indicator. In this function, we update the spread buffer with the current spread data.

We calculate the maximum, minimum, and average spread values using the `ArrayMaximum()`, `ArrayMinimum()`, and `ArrayAverage()` functions, respectively. These values are then stored in separate buffers.

## Disclaimer

This code is not an official product of Forex Robot Easy Team. We are showcasing a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

## Product Description

Spread Meter mt4 is a powerful tool for traders who want to keep track of the spread of their chosen currency pairs. By displaying the spread in real-time, traders can make more informed decisions and adjust their trading strategies accordingly.

With Spread Meter mt4, you can easily monitor the spread of multiple currency pairs simultaneously, allowing you to identify the most favorable trading conditions. This indicator is particularly useful for scalping, midnight, and intraday strategies, where spread plays a crucial role.

Key Features:
- Real-time spread monitoring
- Display of maximum, minimum, and average spread values
- Easy-to-use interface
- Customizable color scheme

To learn more about Spread Meter mt4 and to see detailed reviews and trading results, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/spread-meter-mt4-review-download-real-results-the-key-to-choosing-the-right-broker-and-account-type-for-scalping-midnight-and-intraday-strategies/).
