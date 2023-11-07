# Capstone-3
The VIX Index is a financial benchmark designed to be an up-to-the-minute market estimate of expected volatility of the S&P 500 Index, and is calculated by using the midpoint of real-time S&P 500® Index (SPX) option bid/ask quotes. More specifically, the VIX Index is intended to provide an instantaneous measure of how much the market thinks the S&P 500 Index will fluctuate in the 30 days from the time of each tick of the VIX Index.


Cboe Options Exchange® (Cboe Options®) calculates the VIX Index using standard SPX options and weekly SPX options that are listed for trading on Cboe Options. Standard SPX options expire on the third Friday of each month and weekly SPX options expire on all other Fridays. Only SPX options with Friday expirations are used to calculate the VIX Index.* Only SPX options with more than 23 days and less than 37 days to the Friday SPX expiration are used to calculate the VIX Index. These SPX options are then weighted to yield a constant maturity 30-day measure of the expected volatility of the S&P 500 Index.

* Cboe Options lists SPX options that expire on days other than Fridays. Non-Friday SPX expirations are not used to calculate the VIX Index.

Intraday VIX Index values are based on snapshots of SPX option bid/ask quotes every 15 seconds and are intended to provide an indication of the fair market price of expected volatility at particular points in time. As such, these VIX Index values are often referred to as "indicative" or "spot" values. Cboe Options currently calculates VIX Index spot values between 3:15 a.m. ET and 9:15 a.m. ET (Cboe GTH session), and between 9:30 a.m. ET and 4:15 p.m. ET (Cboe RTH session) according to the VIX Index formula that is set forth in the White Paper.

The generalized formula used in the VIX Index calculation is:

![Vix](../Figures/vix_formula.png)

VIX Index Formula
Originally posted (Apr 14 2016); updated (Jun 29 2016); updated (May 15 2018); updated (Oct 8, 2019)[1]

[1]: https://www.cboe.com/tradable_products/vix/faqs/