# Algorithmic Trading Basics

## Quantitative Analysis

Quantitative analysis is applied to measure and assess efficiency and value of financial tools as well as to predict future events, i.e., change in stock profitability. Quantitative analysis involves building computerized trading models and aids investors in assessing investment opportunities as well as in developing the most successful trading strategy and investing basket. Compared to normal charting analysis, quantitative analysis is more disciplined, systemic, and synchronized with convenient backtesting and varying trading frequencies thanks to computer programs.
 
The main difference between quantitatve analysis and technical analysis is that quantitative analysts do not focus on what the market will be like in the future. Rather, quantitative analysts try to develop a trading and investing strategy that can be quantified.

- Risk - Premium
- Seasonality Effect
- Momentum Strategy (Spot & Derivative) - ML
    - Principal component analysis (PCA) is a technique for reducing the dimensionality of such datasets, increasing interpretability but at the same time minimizing information loss. It does so by creating new uncorrelated variables that successively maximize variance.
    - PCA squeezes stock dataset from (2515x30) matrix to (20x30) components for a latest day: YYYY-MM-DD. Total variance of data is explained by 20 components (factor_betas) is about 92.5%, which is a very good rate.
- Quantitative Value Investing Strategy

## Quantitative Investing Process

### General
- Collect data
- Develop hypothesis / strategy
- Backtest hypothesis / strategy
- Implement strategy

### Quantitative Analysis & Auto-Trading
1. Cumulative returns
2. Annualized volatility - 30 day window
3. Risk premium - investing basket, portfolio
4. Manual trading
5. Auto-trading with backtest simulator

### Risk Parity Strategy
1. Build trading bot
2. Backtest and optimize parameters
3. Test on demo account
4. Live trading on real account
5. Track & quality control
- Buy from 3 stock tickers and keep them for a considerable period of time (>= 12 months) for maximal effectiveness.
- Capital is distributed according to volatility target (10-15% risk).
- Adjust monthly based on volatility - risk
    - Bot buys on the 19th and sells on the 25th monthly.

## Common Statistics

### General
- Annualized return (%)
- (Year) return (% - typically the returns of the most recent 2 - 5 years)
- Last 3 months (%)
- Return since inception (%)
- Best monthly return (%)
- Worst monthly return (%)

### Risk / Return
- Annualized standard deviation (%)
- Downside deviation (%)
- Upside deviation (%)
- Maximum drawdown (%)
- Sharpe ratio
- Sortino ratio
- Percentage of positive months (%)

### Risk Premium
- Ann. return (%)
- Ann. volatility (%)
- Ann. Sharpe
- Ave. Ann. Turnover (%)
- Tot. Profit ($)
- Costs (%Profit)

### Backtest
- Annual return (%)
- Cumulative returns (%)
- Annual volatility (%)
- Sharpe ratio
- Calmar ratio
- Stability
- Max drawdown (%)
- Omega ratio
- Sortino ratio
- Skew
- Kurtosis
- Tail ratio
- Daily value at risk (%)
- Alpha
- Beta

### Momentum
- Momentum (1YR, 6MNT, 1QTR, 1MNT, 1WK)
- Mean reversion 5Day
- Mean reversion 5Day smoothed
- Overnight sentiment
- Overnight sentiment smoothed

## Common Charts
- Growth of $1 invested in Company A ($ - compared to a benchmark i.e. S&P 500)
- Profitability distribution (y-axis: %)
- Cumulative returns (y-axis: cumulative returns)
- Rolling portfolio beta to (some market index - y-axis: beta)
- Rolling Sharpe ratio (6-month - y-axis: Sharpe ratio)
- Underwater plot (y-axis: drawdown)
- Cumulative returns on Country A and Country B asset classes, Year - Year
- PCA [x-axis: principal components; y-axis: explained variance ratio || cumulative explained variance (overhead line), individual explained variance (bar)]
- Momentum - Alpha factors cumulative returns for all quantiles
    - Momentum factors perform the best
    - Sentiment factors show a fair to weak performance
    - Mean reversion factors show poor perform performance

## Tables
### Comparisons between investing baskets with different levels of risk
| Ratio | Basket A | Basket B (risk 25%) | Basket B (15%) |
| --- | --- | --- | --- |
| Annualized profit | 25% | 27% | 17% |
| Annualized volatility - risk | 26% | 20% | 12% |
| Max drawdown | 38% | 26% | 16% |
| Sharpe ratio | 0.99 | 1.34 | 1.34 |

## Technical Analysis on Trading View


## Challenges Faced By Quant Analysts & Traders in Frontier Markets
- Market information and statistics are not synchronized to conduct a complete quantitative analysis. Individual traders face even more obstacles in this regards due to even greater lack of trustworthy publicly available information.
- Lack of dependable quant analysis tools; available tools mostly depend on technical analysis tools i.e. charting analysis tools.
- Lack of softwares to connect brokers as well as to allow individual brokers auto-trading.
- Lack of instructional courses on this topic.
- Lack of publicly available quantitative analysis research: most effective investing strategies have been kept private.
- Required familiarity with programming (R & Python), data science (with a focus in finance), and trading / auto-trading.

## Glossary
| Vocabulary | Definition |
| --- | --- |
| API (Application Programming Interface) | API allows interaction with others' software using your own code. For my basic algorithmic trading projects, I use GET requests to gather data from IEX Cloud API. |
| POST | POST adds data to the database exposed by the API. (Create only) |
| PUT | PUT adds **and overwrites** data in the database exposed by the API. (Create or replace) |
| DELETE | DELETE deletes data from the API's database. |
| Pair Trading (Pairs Trade) | Pair trading is a market neutral trading strategy enabling traders to profit from virtually any market conditions: uptrend, downtrend, or sideways movement. This strategy is categorized as a statistical arbitrage and convergence trading strategy. |
| Risk Parity | Risk parity is a portfolio allocation strategy that uses risk to determine allocations across various components of an investment portfolio. The risk parity strategy modifies the modern portfolio theory (MPT) approach to investing through the use of leverage. |
| Seasonality Effect | The stock market is subject to seasonal stock trends that at certain times of the year, month or even week, share prices can rise or fall. This can be because of changes in the number of traders active in the market or because technical analysis has made historical price patterns more 'self-fulfilling.' |
| Basket Investing | A basket is a collection of multiple securities (e.g., stocks, currencies, etc.) which have a similar theme or share certain criteria. For instance, a sector exchange traded fund (ETF) may contain a basket of stocks that are all in the same industry. |
| Hedge Fund | A hedge fund is a pooled investment fund that trades in relatively liquid assets and is able to make extensive use of more complex trading, portfolio-construction, and risk management techniques in an attempt to improve performance, such as short selling, leverage, and derivatives. Put simply, a hedge fund is a private investment partnership and funds pool that uses varied and complex proprietary strategies and invests or trades in complex products, including listed and unlisted derivatives. |
| Renaissance Technologies LLC | Renaissance Technologies LLC, also known as RenTech or RenTec, is an American hedge fund based in East Setauket, New York, on Long Island, which specializes in systematic trading using quantitative models derived from mathematical and statistical analysis. |
| EBITDA | EBITDA, or earnings before interest, taxes, depreciation, and amortization, is a measure of a company's overall financial performance and is used as an alternative to net income in some circumstances. |
| Quantitative Analysis (QA) | QA is a technique that uses mathematical and statistical modeling, measurement, and research to understand behavior. Quantitative analysts represent a given reality in terms of a numerical value. |
| IB Trader Workstation (TWS) | A market maker-designed IB Trader Workstation (TWS) that lets traders, investors and institutions trade stocks, options, futures, currencies, bonds and funds on over 135 markets worldwide from a single integrated account. |
| Credit Suisse | Credit Suisse Group AG is a global investment bank and financial services firm founded and based in Switzerland. |
| Frontier Market | A frontier market is a country that is more established than the least developed countries (LDCs) but still less established than the emerging markets because it is too small, carries too much inherent risk, or is too illiquid to be considered an emerging market. Frontier markets are also known as pre-emerging markets. |
| Volatility | Risk management (volatility 25% for risk appetitte 25%). |
| Quality Control | Quality control involves testing units and determining if they are within the specifications for the final product. The purpose of the testing is to determine any needs for corrective actions in the manufacturing process. Good quality control helps companies meet consumer demands for better products. |
