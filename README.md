# Heatmap Volume Profile

This code is a custom indicator for the MetaTrader 5 (MQL5) trading platform. It calculates and displays a heatmap volume profile on the chart. The heatmap volume profile shows the distribution of trading volume at various price levels.

## How it Works

1. The code initializes the indicator by setting the number of heatmaps to display (`heatmapCount`) and the range of each heatmap in pips (`heatmapRange`).

2. The `OnInit()` function calculates the levels for each heatmap based on the current Ask price and the heatmap range. The levels are stored in the `heatmapLevels` array.

3. The code sets up the indicator buffers and styles. The heatmap levels are set as the first buffer, and a colored line is drawn to represent each level.

4. An indicator label is created to display the name of the indicator.

5. The `OnCalculate()` function is called for each new tick or bar. It calculates the volume profile by iterating over the price data and adding the volume for each price level to the corresponding heatmap index.

6. The indicator values are set based on the volume profile.

## Product Description

Heatmap Volume Profile is a powerful tool for analyzing trading volume in the forex market. It provides a visual representation of the volume distribution at different price levels, helping traders identify areas of high or low activity.

With Heatmap Volume Profile, you can:

- Gain insights into the market by understanding where the majority of trading volume is concentrated.
- Identify support and resistance levels based on volume clusters.
- Spot potential areas of price reversals or breakouts.
- Enhance your trading decisions by incorporating volume analysis into your strategy.

To use Heatmap Volume Profile, simply install the indicator on your MetaTrader 5 platform and apply it to your desired currency pair or financial instrument. The indicator will automatically calculate and display the volume profile on your chart.

Please note that Forex Robot Easy is not the official developer of this product. We are providing this sample code as an example of how the indicator can work. For the official developer and more information about this product, please visit [MQL5](https://www.mql5.com/).

For detailed reviews and trading results of this product, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/heatmap-volume-profile-review-your-key-to-forex-trading-success/).
