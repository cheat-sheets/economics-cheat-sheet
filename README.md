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

# Week 2

### Overview

1. **Federal Reserve's Dual Mandate**: The Federal Reserve operates under a Dual Mandate to achieve maximum employment and stable prices, guiding its monetary policy decisions.

2. **Monetary Policy Tools**: The Fed uses traditional tools like open market operations and the discount window, along with unconventional tools post-2008, such as forward guidance and large-scale asset purchases.

3. **Adaptability in Policy**: The Federal Reserve can adapt its monetary policy tools, including influencing longer-term interest rates, especially when short-term rates are at zero.

### History and Structure of the Federal Reserve

1. **Foundation and Purpose of Central Banks**: Central banks, like the Swedish Riksbank, were established to address issues of price stability and banking system stability. By controlling the money supply, central banks aim to prevent excessive inflation and act as a lender of last resort to prevent bank runs.

2. **Formation of the Federal Reserve System**: The Federal Reserve System, established in 1913, was a response to the need for a central bank in the U.S. to control money supply and provide stability during banking crises. Its establishment was influenced by earlier banking panics, notably the Panic of 1907.

3. **Structure of the Federal Reserve System**: The Federal Reserve comprises three main components: 
    - the Board of Governors, 
    - 12 Regional Federal Reserve Banks, and 
    - the Federal Open Market Committee (FOMC). 
   
   These bodies collectively guide monetary policy, supervise financial institutions, and implement central bank functions like open market operations and foreign exchange interventions.

### Five Key Function of the Federal Reserve System

1. **Monetary Policy and Financial Stability**: The Federal Reserve's primary functions include conducting monetary policy to achieve maximum employment, stable prices, and moderate long-term interest rates, and promoting financial stability in the financial system through micro-prudential and macro-prudential approaches.
    - Conducting Monetary Policy: Managing the economy through monetary policy.
    - Financial System Stability: Ensuring stability in the financial system.
    - Regulating Financial Institutions: Overseeing and regulating banks.
    - Managing Payment Systems: Facilitating payments and currency management.
    - Consumer Protection: Implementing consumer protection laws.

2. **Regulation and Supervision of Financial Institutions**: The Federal Reserve is responsible for the regulation and supervision of financial institutions, involving the creation and enforcement of rules to ensure compliance, maintain financial stability, and oversee the safety and soundness of individual financial institutions.

3. **Payment System and Consumer Protection**: The Federal Reserve manages an efficient payment system, including currency issuance, check clearing, and bank transfers, and promotes consumer protection and community development through various laws and regulations, such as the Community Reinvestment Act and the Truth in Lending Act.

## Traditional Monetary Policy

### Money Supply

1. **Quantitative Theory of Money**: The theory posits that the value of all goods and services must equal the total money supply, factoring in the velocity of money circulation.

   - **M (Money Supply)**: Represents the total amount of money in circulation in the economy, including cash and bank deposits.

   - **V (Velocity of Money)**: Indicates how frequently money is used for transactions within a certain period. A higher velocity means money changes hands more rapidly.

   - **P (Price Level)**: Reflects the average price of goods and services in the economy.

   - **T (Volume of Transactions)**: The total number of transactions involving goods and services in the economy over a given period.

   The equation **M * V = P * T** illustrates that the product of the money supply and the velocity of money in an economy is equal to the product of the price level and the volume of transactions. This relationship is central to the quantitative theory of money, linking the money supply with economic activity and inflation.

2. **Measuring Money Supply**: Money supply is measured in various forms: 
    - monetary base (currency in circulation and bank reserves), 
    - M1 (monetary base plus transaction deposits), 
    - M2 (M1 plus savings and small deposits), and 
    - M3 (M2 plus large deposits and other liquid assets).

   [M1](https://fred.stlouisfed.org/series/M1SL)

3. **Central Bank Influence on Money Supply**: Central banks, like the Federal Reserve, can affect money supply through reserve requirements, open market operations, and influencing the money multiplier, thereby impacting interest rates and economic activity.

### Federal Reserve's Balance Sheet

1. **Growth and Composition of Assets**: The Federal Reserve's balance sheet has grown significantly, especially during the 2008 financial crisis and the COVID-19 pandemic, with major assets being government securities and mortgage-backed securities. This growth reflects the Fed's increased involvement in stabilizing the economy.

2. **Financing the Balance Sheet Expansion**: The expansion was financed not by printing more currency but by increasing bank reserves at the Federal Reserve, reflecting a shift in how the Fed manages its balance sheet.

3. **Liabilities and Monetary Base**: The main liabilities on the Federal Reserve's balance sheet are the monetary base, comprising currency in circulation and bank reserves. The balance sheet's size has increased tenfold due to financial crises, impacting the composition and scale of the Fed's liabilities.

### Open Market Operations

1. **Role in Monetary Policy**: Open Market Operations (OMOs) are the Federal Reserve's primary tool for implementing monetary policy, used to adjust the supply of reserves in the banking system, which influences the federal funds rate.

    1. The Federal Open Market Committee (FOMC) decides on the target interest rate.
    2. The implementation of the target rate is handled by the Federal Reserve Bank of New York (FRBNY), which has a large trading desk. This desk manages the System Open Market Account (SOMA) and executes trades.
    3. The FRBNY's trading desk purchases securities from selected dealers.
    4. These dealers have reserve accounts at the Federal Reserve.
    5. When the trading desk completes a purchase, the Federal Reserve's balance sheet expands: securities increase on the asset side, and reserves increase on the liability side.

2. **Pre- and Post-Financial Crisis Approaches**: Before the 2008 crisis, the Fed used OMOs to manage daily reserve levels, keeping the federal funds rate on target. Post-crisis, with increased bank reserves, OMOs shifted focus to managing the size and composition of the Fed's balance sheet.

3. **Impact on Federal Funds Rate**: The Federal Reserve adjusts the federal funds rate by buying or selling securities, which alters the reserve levels in banks. These changes influence the availability of funds in the market and consequently, the interest rates.

### The Discount Window

1. **Purpose and Mechanism**: The discount window is an original monetary policy tool used by the Federal Reserve to provide short-term, collateralized loans to banks for liquidity, traditionally calculated by discounting interest from the loan's face value.

2. **Types of Discount Window Lending**: There are three types of lending through the discount window: Primary Credit for sound banks needing short-term liquidity, Secondary Credit for less financially stable banks, and Seasonal Credit for banks with significant seasonal fluctuations in loans and deposits.

3. **Role in Monetary Policy and Stigma Effect**: The discount window supports the upper limit of the federal funds rate, acting as an alternative to federal funds borrowing. However, banks often avoid using it due to the stigma effect, fearing it signals poor liquidity.

## Non-traditional Monetary Policy

### Forward Guidance

1. **Forward Guidance as a Policy Tool**: Forward guidance is an unconventional monetary policy tool used by the Federal Reserve to communicate future policy intentions, particularly effective when traditional tools like interest rate adjustments reach their limits, such as the lower bound of zero.

2. **Types of Forward Guidance Communication**: The Federal Reserve employs various communication methods for forward guidance, including FOMC statements, minutes from meetings, summary of economic projections (including the "dot plot" of federal funds rate expectations), and press conferences.

3. **Impact on Financial Markets**: Forward guidance significantly influences market expectations and behavior, as seen in episodes like the "taper tantrum," where market interpretations of Fed communications can lead to substantial market reactions.

### Large-Scale Asset Purchases

1. **LSAP as an Unconventional Monetary Policy Tool**: Large-scale asset purchases, also known as quantitative easing (QE), are used by the Federal Reserve as an unconventional monetary policy tool, particularly when short-term interest rates are at or near zero, to stimulate the economy by directly affecting long-term interest rates.

2. **Implementation and Impact of QE Programs**: The Federal Reserve has implemented several QE programs since 2008, involving the purchase of long-term Treasury securities and agency mortgage-backed securities. These programs aimed to lower long-term interest rates, reduce borrowing costs for households and firms, and encourage economic activities like home buying.

3. **Influence on the Federal Reserve's Balance Sheet**: QE programs significantly increased the Federal Reserve's balance sheet, demonstrating their impact on the financial system and the broader economy. The programs were designed to lower long-term interest rates and support market functioning during economic downturns, such as the 2008 financial crisis and the COVID-19 pandemic.

### The Overnight Reverse Repurchase Agreement Facility

1. **ONRRP as a Monetary Policy Tool**: The ONRRP was introduced as part of monetary policy normalization in 2014 after the Federal Reserve set the federal funds rate to zero and engaged in large-scale asset purchases (LSAP) following the 2008 financial crisis. It was designed to help return to traditional monetary policy by increasing the federal funds rate.

2. **Role of the Repo Market**: To address the challenge of reducing reserves in a market with ample reserves, the Federal Reserve turned to the repo market. Rather than selling securities, the Federal Reserve used reverse repo agreements in the repo market, with treasury securities as collateral. The ONRRP was created to facilitate these transactions.

3. **Two-Dimensional Impact of ONRRP**: The ONRRP operates on two dimensions. First, it offers an interest rate in an overnight funding market, similar to the federal funds market. If the ONRRP rate is higher than the federal funds rate, banks have an incentive to lend to the ONRRP, setting a lower bound for the federal funds rate. Second, the ONRRP reduces the total amount of reserves available, ensuring that the banking system retains only the reserves needed for liquidity purposes, effectively controlling the level of reserves.

