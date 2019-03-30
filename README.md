## A Model to Predict Secondary Equity Offerings

Secondary offerings are one of the ways companies meet their financing needs.  Typically when a secondary offering is announced, the stock dips causing the price to fall meaning the ability to predict could allow a speculator to gain by shorting the stock.  To do this profitably, however, the time frame of the prediction would have to be very (perhaps unattainably) tight since the magnitude of price drops are typically only several percent(?) and that is generally easily swamped by normal equity volatility.  Nonetheless, this could possibly be one factor in a more general buy-sell-short decision and is an interesting problem to consider

## Variable of Interest

- likelihood of a secondary offering in specific time period
- (some measure of magnitude of raise would be useful too)
- ultimately would be nice if could predict likelihood of effect on return of secondary offering in a time frame

For now we will use likelihood of a secondary offering in specifc time period as our response variable.

## Data

A list of possible predictors and an a priori guess of whether we expect them to be positively or negatively correlated
with our response variable

Company Finances
- cash flow: -corr
- indebtedness:  +corr
- previous history of secondaries: +corr
- length since last secondary: +corr (or maybe -short-term +med-term -long-term?)
- age of co?
- recent acquisitions, announcement of acquisitions: +corr
- stock price: +corr
- net asset value
- stock price/net asset value: +corr
- p/e ratio: +crr
- earnings: -corr
- access to other financing sources: some composite meausre including indebtedness, loan covenants, etc?

Sector Factors
- tot secondaries of peers: +corr

Macro Factors
- tot secondaries: +corr
- interest rates: +corr
- inflation? est'd real interest rates


