# Economics Cheat Sheet

[Central Banks and Monetary Policy](https://www.coursera.org/learn/central-banks-monetary-policies/home/week/1)

# Week 1

## Short-Term Funding Market

### The Market for Federal Funds

1. **Reserve Requirements**: Banks must hold minimum reserves at the Federal Reserve; pre-COVID-19, this was 3%, then reduced to zero during the pandemic.
   - https://www.federalreserve.gov/monetarypolicy/reservereq.htm
   - 0% starting from  March 26, 2020
   - 3% or 10% before March 26, 2020, depending on the amount threshold in the account
2. **Excess Reserves**: Banks keep extra reserves for unforeseen needs, notably during the COVID-19 crisis.
3. **Reserve Levels**: Post-2008 crisis, reserves increased significantly, from $40 billion in 2007 to $3.7 trillion by 2021, influenced by lower interest rates and Federal Reserve policies.
4. **Federal Funds Market**: Banks borrow from each other here, usually overnight, to manage reserve shortfalls.
5. **Impact on Interest Rates**: The federal funds rate, set by the Federal Reserve, affects banking costs and the overall cost of credit in the economy.
   - https://fred.stlouisfed.org/series/FEDFUNDS
6. **Open Market Operations**: The Federal Reserve controls the federal funds rate by trading assets with banks, impacting economic interest rates.

### The Repo Market

1. **Repo Market Overview**: The repo market, crucial for overnight lending in the US, started growing in the early 1980s, reaching about $4.8 trillion before the financial crisis and $4 trillion in Q4 2020. In December 2020, transactions worth nearly $37 trillion occurred.

2. **How Repos Work**: In a repurchase agreement (repo), a party sells a security with an agreement to buy it back later at a higher price. This acts as a collateralized loan. The interest rate is calculated from the price difference between selling and repurchasing.

3. **Example and Risks**: Selling a $200 security to repurchase at $200.02 yields a 3.6% annual interest. If the market price drops, the seller might opt not to repurchase. To mitigate this, a 'haircut' is applied, where the buyer pays less than the full value, reducing the risk of price fluctuation.

4. **Haircuts in Repos**: Haircuts depend on the security's credit quality, price volatility, and market conditions. They ensure the seller is motivated to repurchase, even if the market price drops.

5. **Common Securities in Repos**: Government-backed securities, like treasury bonds, are common in repos due to low credit risk and price stability. General collateral repos involve these securities and have low transaction costs.

6. **Tri-Party Repo System**: For efficiency, especially in overnight borrowing, a custodian manages the transaction, transferring securities and funds between the buyer's and seller's accounts.

7. **Repo Market Popularity**: It's the largest cash market, accessible to various financial institutions, not just banks. Money market mutual funds are significant repo purchasers.

8. **Regulatory Reforms Post-2008 Crisis**: The 2008 crisis highlighted issues like Lehman Brothers' use of 'Repo 105', leading to regulatory reforms.

In summary, the repo market is a vital financial instrument for secured lending, offering flexibility and security through mechanisms like haircuts and tri-party systems, widely used by various financial institutions.

### Short-term Interest Rates

1. **LIBOR's Role and Challenges**: The London Interbank Offered Rate (LIBOR) has been a key benchmark for various loans worldwide. However, it faced issues like susceptibility to credit risks and manipulation scandals, especially highlighted during the 2008 financial crisis.

2. **Introduction of SOFR**: In response to LIBOR's shortcomings, the Secured Overnight Financing Rate (SOFR) was introduced. SOFR is based on overnight repurchase agreements with Treasury collateral, making it a more stable, risk-free interest rate.

3. **Transition from LIBOR to SOFR**: The transition from LIBOR to SOFR marks a significant shift in reference interest rates for loans, driven by SOFR's stability, larger transaction volume, and reduced credit risk compared to LIBOR.

## Government Securities and Long-term Interest Rates

### Nominal and Real Interest Rates

1. **Nominal vs. Real Interest Rates**: Nominal interest rates represent the percentage increase in money, while real interest rates account for inflation's impact on purchasing power. The real interest rate equals the nominal rate minus inflation, illustrating the difference in value over time.

2. **Fisher Effect**: This concept, named after economist Irving Fisher, links nominal and real interest rates with inflation. It suggests that the real interest rate is approximately the nominal interest rate minus the inflation rate, demonstrating how inflation affects investment returns.

3. **Treasury Inflation-Protected Securities (TIPS)**: TIPS are unique in that they adjust their principal based on inflation, measured by the Consumer Price Index (CPI). The yield on TIPS reflects real interest rates and provides insights into market inflation expectations, influencing investor behavior.
    - https://fred.stlouisfed.org/series/DFII10

### Treasury Securities and Their Importance

1. **US Treasury Market Size and Liquidity**: The US Treasury market is the largest debt market globally, with over $24 trillion in outstanding securities. Its size and liquidity make it a preferred choice for a wide range of investors, including international ones, making it the most liquid security market in the world.

2. **Risk-Free Nature of US Treasuries**: US Treasuries are considered risk-free because they are backed by the full faith and credit of the US government. This guarantees payment of interest and principal, making their interest rates a reliable measure of the risk-free interest rate.

3. **Components of Long-Term Treasury Interest Rates**: Long-term nominal interest rates on US Treasuries consist of three components: 
    - the real interest rate (adjusted for inflation), 
    - expected inflation, and 
    - the term premium, which accounts for long-term risks. 

   These rates are closely analyzed in financial markets to gauge expected inflation and other economic indicators.

### Term Structure of Interest Rates

1. **Definition of Term Structure of Interest Rates**: The term structure of interest rates, or the yield curve, compares the yields of securities from the same issuer but with different maturities on a given day. It accounts for bond prices to determine yields, showing that bond yields and prices move inversely.

2. **US Treasury Securities and Yield Curve**: US Treasury securities are ideal for measuring yields because they have no credit risk, are issued at various maturities, and have minimal transaction costs. The most important yield curve is based on these securities.

3. **Understanding Yield Curve Shapes**: An upward sloping yield curve (higher yields for longer maturities) suggests market expectations of rising interest rates or inflation, common during economic expansions. Conversely, a downward sloping or inverted yield curve indicates expectations of lower future interest rates, often before recessions.

4. **Factors Influencing Yield Curve**: Expectations of Federal Reserve actions, inflation predictions, and fiscal policies affecting government debt supply all influence the shape of the yield curve.

5. **Yield Curve as a Recession Predictor**: The yield curve, especially the spread between 10-year and 2-year Treasury notes, has historically inverted before recessions, making it a strong predictor of economic downturns.

6. **Key Learnings**: The yield curve is a vital economic indicator, with its shape providing insights into market expectations about interest rates, inflation, and economic growth. An upward sloping curve is typical during expansions, while an inverted curve often signals upcoming recessions.

[10-Year Treasury Constant Maturity Minus 2-Year Treasury Constant Maturity](https://fred.stlouisfed.org/series/T10Y2Y)

### Money Market Mutual Funds

1. **Popularity and Function of Money Market Funds**: Money market mutual funds, managing over $4.4 trillion in early 2021, are popular due to their ability to offer higher interest rates compared to bank deposits. They invest in low-risk, short-term debt securities like US Treasury bills and highly rated commercial paper, making them a significant component of the financial system for short-term lending.

2. **Comparison to Bank Deposits**: Although similar to bank deposits in their liquidity and on-demand redeemability, money market funds differ by offering higher interest rates and not being insured like bank deposits. This lack of insurance means there's a small risk of losses, especially in prime funds which invest in slightly riskier assets.

3. **Role in the Shadow Banking System and Financial Stability**: Money market funds are crucial in the shadow banking system, providing short-term funding to various financial institutions and corporations. However, they can create systemic risks, as seen during the 2008 financial crisis when large redemptions from these funds led to a significant reduction in short-term credit availability, impacting the broader financial system.

### Securitization

1. **Scale and Impact of Securitization**: Securitization, involving bundling and transforming loans into securities, is a vast market in the U.S., with about $12 trillion in bonds related to securitization as of 2021. This process primarily involves mortgages but also includes other loans like small business loans and accounts receivable.

2. **Principles and Profitability of Securitization**: The success of securitization relies on the law of large numbers, where risks are spread across a large pool of loans, allowing more precise estimation of expected cash flows and losses. This allows the issuance of various debt tranches, with senior debt being the least risky, followed by junior and equity portions. Securitization enhances profitability by enabling issuers to borrow from the market and create more loans.

3. **Dependence on Short-Term Funding Markets**: Securitization is closely linked to short-term funding markets. Issuers often rely on short-term funding like commercial paper to build loan pools before securitization. Disruptions in these markets, as seen during the 2008 financial crisis, can break the securitization chain and significantly impact credit availability to businesses and households.



