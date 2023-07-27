# TAC Indicator (Tolerance Average Chandle)
=============================================

## TAC Philosophy:

TAC (Tolerance Average Chandle) is an indicator for the TradingView platform that is used to calculate the difference between the closing price and the Exponential Moving Average (EMA) for each candle over a period of time. This indicator assists traders in identifying price trend changes based on the difference between the closing price and the EMA.

## Description:

This repository contains the source code for the TAC (Average Chandle Tolerance) indicator developed for the TradingView platform. This indicator displays the TAC value as a line on the chart, with the color of the line changing according to the TAC value. If TAC is positive, the line will be green, if TAC is negative, the line will be red, and if TAC is zero, the line will be white.

## How to use TAC:

1. Copy the entire code in the "tac_indicator.pine" file.
2. Open the TradingView platform and go to the "Pine Editor" section.
3. Paste the TAC code in the Pine Editor and save the script with the desired name.
4. Add the TAC indicator to the chart by clicking the "Indicators" button and searching for the name of the indicator you saved.
5. Set the EMA period according to your preference using the provided inputs.
The TAC indicator will appear on the chart and display a colored line indicating the TAC value in each chandle.

## Code Description:

- `ema(close, periods)`: This function calculates the Exponential Moving Average (EMA) of the closing price. EMA is calculated using an exponential formula to give more weight to recent price data.
- `spread(close, emaValue)`: This function calculates the difference between the closing price and the EMA.
- `getTACValue(close, emaValue)`: This function calculates the TAC value (difference between the closing price and the EMA) based on the position of the closing price relative to the EMA. If the closing price is above the EMA, the TAC value will be positive, and if the closing price is below the EMA, the TAC value will be negative. If the closing price equals the EMA, the TAC will be zero.
- `emaPeriods`: This variable is input from the user to define the desired EMA period.

## Licence:

This indicator is provided under the Mozilla Public License 2.0, which means you can use it freely and even modify the source code. We really appreciate the contribution and input from users to improve this indicator.

## Enjoy Trading

Happy trading using the TAC indicator! Hope this indicator helps you in identifying better trading opportunities. Feel free to provide feedback or questions in the "Issues" section if you have any suggestions or would like to discuss further about this indicator.

Thanks for using the TAC indicator and good luck in your trading!

Read in [id](https://github.com/affanyunas/tac-Indicator/blob/main/BACA.md)