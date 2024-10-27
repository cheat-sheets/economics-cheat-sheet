# Economics Cheat Sheet

[Central Banks and Monetary Policy](https://www.coursera.org/learn/central-banks-monetary-policies/home/week/1)

# Week 1: Overview

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

[United States - Government Bonds Yield Curve](https://www.investing.com/rates-bonds/usa-government-bonds)

### Money Market Mutual Funds

1. **Popularity and Function of Money Market Funds**: Money market mutual funds, managing over $4.4 trillion in early 2021, are popular due to their ability to offer higher interest rates compared to bank deposits. They invest in low-risk, short-term debt securities like US Treasury bills and highly rated commercial paper, making them a significant component of the financial system for short-term lending.

2. **Comparison to Bank Deposits**: Although similar to bank deposits in their liquidity and on-demand redeemability, money market funds differ by offering higher interest rates and not being insured like bank deposits. This lack of insurance means there's a small risk of losses, especially in prime funds which invest in slightly riskier assets.

3. **Role in the Shadow Banking System and Financial Stability**: Money market funds are crucial in the shadow banking system, providing short-term funding to various financial institutions and corporations. However, they can create systemic risks, as seen during the 2008 financial crisis when large redemptions from these funds led to a significant reduction in short-term credit availability, impacting the broader financial system.

### Securitization

1. **Scale and Impact of Securitization**: Securitization, involving bundling and transforming loans into securities, is a vast market in the U.S., with about $12 trillion in bonds related to securitization as of 2021. This process primarily involves mortgages but also includes other loans like small business loans and accounts receivable.

2. **Principles and Profitability of Securitization**: The success of securitization relies on the law of large numbers, where risks are spread across a large pool of loans, allowing more precise estimation of expected cash flows and losses. This allows the issuance of various debt tranches, with senior debt being the least risky, followed by junior and equity portions. Securitization enhances profitability by enabling issuers to borrow from the market and create more loans.

3. **Dependence on Short-Term Funding Markets**: Securitization is closely linked to short-term funding markets. Issuers often rely on short-term funding like commercial paper to build loan pools before securitization. Disruptions in these markets, as seen during the 2008 financial crisis, can break the securitization chain and significantly impact credit availability to businesses and households.

# Week 2: The Federal Reserve

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

# Week 3: Monetary Policy and the Real Economy

1. **Fed's Dual Mandate and Economic Impact**: The Federal Reserve aims to achieve maximum employment and stable prices, known as its dual mandate. This module explores how the Fed's monetary policy actions, particularly changes in the target interest rate, influence key macroeconomic outcomes like GDP, unemployment, and inflation.

2. **Trade-Off Between Unemployment and Inflation**: The module highlights the inherent trade-off between unemployment and inflation in monetary policy. It discusses how easing monetary policy can reduce unemployment in the short term but may lead to higher inflation. This trade-off is crucial in the Fed's decision-making process and is reflected in rules like the Taylor rule, which guides interest rate adjustments based on economic conditions.

3. **Mechanics and Limitations of Monetary Policy**: The course delves into the channels through which monetary policy affects economic growth, inflation, and unemployment, including its impact on credit and money supply, and investment and consumption decisions. It also covers the role of monetary policy in stabilizing economic cycles and discusses its limitations, particularly in addressing supply-side shocks and structural changes in industries.

## The Link between Inflation and Unemployment

### The Natural Rate of Unemployment and Okun’s Law

1. **Okun's Law Essence**: Okun's Law reveals that a 1% increase in unemployment correlates with about a 2% decrease in Real GDP, indicating a strong negative correlation between economic growth and unemployment rates.

2. **Natural Unemployment Rate**: The natural rate of unemployment is the baseline level in a fully employed economy, factoring in frictional and cyclical unemployment. Over time, it fluctuates due to labor market structure and policy changes.

3. **Monetary Policy Limitations**: Monetary policy effectively targets cyclical but not natural unemployment. Recent unemployment trends, especially after 2000, reflect structural changes in the labor market and the evolving impact of technology.

### Phillips Curve

1. **[Phillips Curve Concept](https://en.wikipedia.org/wiki/Phillips_curve)**: Illustrates an inverse relationship between unemployment and inflation. Initially stable, this relationship varies over time, impacting wage growth and inflation rates. 
 
The Phillips Curve formula is:

```
pi = pi^e - beta(u - u^*)
```

Where:
- `pi` represents the actual rate of inflation.
- `pi^e` is the expected rate of inflation.
- `u` is the actual unemployment rate.
- `u^*` is the natural rate of unemployment (the rate when the economy is at full employment).
- `beta` is a coefficient indicating the sensitivity of inflation to the unemployment gap (`u - u^*`).


2. **Curve Shift Factors**: Shifts in the Phillips Curve are influenced by changes in inflation expectations and external factors like supply shocks, affecting the trade-off between inflation and unemployment.

3. **Monetary Policy Impact**: The curve informs monetary policy, guiding decisions on managing inflation and responding to economic conditions, emphasizing the importance of inflation expectations.

### Discretionary and Rule-Based Monetary Policy

1. **Rule-based vs. Discretionary Policy**: Examines the choice between constant, predictable rule-based monetary policy (advocated by Milton Friedman) and flexible, adaptive discretionary policy that responds to economic changes.

  **Milton Friedman's Approach**: Friedman advocated for a rule-based monetary policy, specifically proposing a constant and predictable growth in the money supply. His approach, often referred to as the "k-percent rule," suggests that the central bank should increase the money supply by a fixed percentage rate annually, typically between 2% and 5%, regardless of business cycle fluctuations. 

   - **Objective**: Aimed at promoting economic stability by avoiding sharp inflations or deflations.
   - **Key Feature**: This rule disregards current economic conditions, meaning the central bank follows a pre-set algorithm without considering cyclical economic changes.
   - **Advantage**: Provides financial markets and businesses with perfect predictability of monetary policy actions, allowing for stable long-term planning and decision-making.


2. **Activist Policy Rationale**: Highlights the need for discretionary monetary policy, especially in mitigating the individual and economic impacts of recessions and extreme events like financial crises or pandemics.

3. **Discretionary Policy Challenges**: Focuses on the central challenge of discretionary policy - balancing short-term actions with long-term stability, requiring central bank credibility and a careful approach to policy adjustments.

### The Taylor Rule

1. **Taylor Rule Basics**: The Taylor rule is a formula central bankers use to set nominal interest rates, balancing the trade-off between inflation and unemployment. It considers the real interest rate, target inflation rate, and deviations in actual inflation and output from their targets.

i = r* + π + α(π−π*) + β(Y−Y*))

- i is the nominal interest rate.
- r* is the real equilibrium interest rate.
- π is the current rate of inflation.
- π* is the target rate of inflation.
- Y is the logarithm of current real GDP.
- Y* is the logarithm of potential output.
- α and β are weights given to the inflation gap (π − π*) and the output gap (Y − Y*), respectively.

2. **Application of the Rule**: The rule, proposed by John Taylor, incorporates weights for inflation rate (\( \alpha \)) and output gap rate (\( \beta \)). Historically, \( \alpha \) is set at 1.5, and \( \beta \) varies between 0.5 and 1. This rule has closely tracked the actual federal funds rate, indicating its effectiveness in monetary policy.

3. **Federal Reserve's Use of the Rule**: The Federal Reserve includes the Taylor rule in its internal forecasts and decision-making processes, even considering modified versions to account for constraints like the zero lower bound on interest rates.

## Transmission of Monetary Policy

### How Do Changes in Monetary Policy Affect the Economy?

1. **Transmission of Monetary Policy**: Explains how the Federal Open Market Committee's (FOMC) adjustments in the federal funds rate impact the economy. Changes in this rate lead to shifts in other interest rates, altering financial conditions. This affects households' and businesses' spending decisions, influencing economic growth, employment, and inflation.

2. **Effects on Interest Rates and Economic Activities**: Demonstrates that a change in the federal funds rate directly impacts short-term interest rates, like the three-month US Treasury bill rate, and indirectly affects medium and long-term rates, such as the yield on a 10-year Treasury note. These shifts influence borrowing costs for firms and consumers, impacting investment and consumption. Additionally, changes in long-term interest rates affect stock prices, personal wealth, and spending decisions.

3. **Empirical Outcomes of Federal Funds Rate Changes**: Utilizing a vector autoregression model, the lecture shows that an increase in the federal funds rate typically results in a contraction of the money supply (measured by M2), a decrease in industrial production after about six months, a rise in unemployment, and initially puzzling behaviors in consumer prices. The lecture highlights that monetary policy affects the economy with a lag and that its impacts are multifaceted.

### The Bank Lending Channel

1. **Net Interest Margin Impact**: Explores how the net interest margin (the difference between interest income from loans and interest expenses to depositors) affects bank profitability. Monetary policy influences this margin, as seen when the Federal Reserve adjusts the federal funds rate, impacting short-term interest rates. A higher federal funds rate can reduce the net interest margin, lowering bank profits and consequently their ability to extend new loans.

Banks Net Interest Margin: https://fred.stlouisfed.org/series/DDEI01USA156NWDB

2. **Reserves and Credit Supply**: Details how monetary policy affects bank reserves. When the Federal Reserve raises the federal funds rate through open market operations (selling securities to banks), it reduces the reserves in the banking system. This diminishes banks' short-term funding availability for lending, thereby tightening the credit supply.

3. **Deposits and Bank Funding**: Discusses the effect of federal funds rate increases on bank deposits. Higher rates can lead to a withdrawal of deposits, particularly among large depositors, as they seek better returns elsewhere. This reduction in deposits means banks have less funding to offer as credit. The lecture notes that banks are strategic in setting deposit rates, responding more quickly in competitive banking environments.

### The Balance Sheet and Refinancing Channels of Monetary Policy

1. **Impact on Firm Finances**: Monetary policy directly influences firms' borrowing costs. Most firms rely on bank loans with floating interest rates tied to benchmarks like LIBOR. For instance, a Federal Reserve rate cut reduces the interest rate on a firm's loans, decreasing their interest expenses and freeing up funds for investment. This effect is more pronounced in smaller, financially constrained firms, impacting their production and employment decisions.

2. **Consumer Mortgage Refinancing**: Changes in the federal funds rate affect mortgage rates, influencing consumer behavior, especially in refinancing decisions. When rates drop, consumers can refinance existing higher-rate mortgages to lower-rate ones, leading to significant savings in mortgage payments. This extra cash flow typically boosts consumer spending in various sectors, like automobile purchases or home renovations.

30-Year Fixed Rate Mortgage Average in the United States: https://fred.stlouisfed.org/series/MORTGAGE30US

3. **Aggregate Economic Effects**: The combined effect of reduced financing costs for firms and increased disposable income for households due to lower mortgage payments leads to increased consumption and investment. This uplifts overall demand for goods and services, benefiting the broader economy. The magnitude of these effects depends on the level of indebtedness and the balance sheet conditions of both firms and households.

## Case Studies

### Supply Shock: Stagflation

1. **Stagflation in the 1970s**: The 1970s experienced stagflation, characterized by low growth, high inflation, and high unemployment. This period was marked by two major oil shocks: the OPEC embargo in 1973, which saw oil prices rise from $3 to $11 per barrel, and the Iranian Revolution and Iran-Iraq war in the late 1970s, leading to oil prices reaching $39.50 per barrel. These supply shocks significantly impacted the economy, including industries like U.S. car manufacturing, and led to high inflation and unemployment.

2. **Responses to Oil Shocks**: The Federal Reserve faced challenges in addressing stagflation since traditional monetary policy tools are less effective against supply shocks. Responses included non-monetary measures like gas rationing, imposing a national maximum speed limit of 50 miles / hour, introducing fuel economy standards, and developing the Strategic Petroleum Reserve. These measures, along with increased oil production, eventually led to reduced oil prices and inflation in the 1980s.

3. **Monetary Policy and Inflation Expectations**: Paul Volcker's tenure as Federal Reserve Chairman saw a decisive move to combat high inflation and inflation expectations by significantly raising the federal funds rate, reaching 19% in 1981. This approach caused short-term increases in unemployment but was crucial in establishing a credible commitment to low inflation, which helped to shift inflation expectations and establish a low inflation regime.

### Jobless Recovery and Consequences of Accommodative Monetary Policy

1. **Jobless Recovery in Early 2000s**: The early 2000s experienced a 'jobless recovery', where despite accommodative monetary policy (low interest rates), the labor market recovered slowly. This phenomenon first appeared after the 1990 recession, but was more pronounced after the 2001 recession. Factors contributing to this included high uncertainty due to events like the September 11th attacks, wars in Afghanistan and Iraq, and corporate scandals like Enron.

2. **Impact of Structural Changes**: The slow labor market recovery was also attributed to structural changes in the economy, particularly in manufacturing. The decline in manufacturing jobs, accelerated by increased international competition and significant policy changes like China's entry into the World Trade Organization, led to job losses that were not quickly offset by gains in growing industries like technology.

3. **Unintended Consequences of Monetary Policy**: Accommodative monetary policy in the early 2000s, characterized by extremely low federal funds rates, inadvertently fueled a housing boom. This led to increased consumer spending through mortgage refinancing and home equity lines of credit, but also heightened risk-taking in the financial system. These conditions contributed to the build-up of risks that precipitated the 2008 financial crisis, highlighting the limitations of monetary policy in addressing structural unemployment and its potential to create financial instability.

# Week 4: Financial Crises

1. **Central Banks as Lenders of Last Resort**: The module discusses the role of central banks in responding to financial crises, primarily as lenders of last resort. It examines historical financial crises like the Panic of 1907 and the Great Depression to illustrate the need for central banks in stabilizing financial systems. These examples demonstrate how central banks can intervene effectively but also highlight the limits of their actions.

2. **Causes of Financial Crises**: The module identifies common themes in various financial crises, emphasizing the role of credit booms, often financed with short-term or foreign funding, and combined with long-term investments or unsustainable government policies. It notes that while not all credit booms lead to crises, certain sectors like manufacturing have historically been more resilient to such booms.

3. **Policy Responses to Crises**: Focuses on how central banks can mitigate the effects of financial crises. Examples include the Federal Reserve's response to the 2008 financial crisis and the COVID-19 pandemic, showcasing its role in providing liquidity when other sources dry up. Additionally, the module discusses the role of fiscal policy, involving government transfers and spending, as an alternative or complementary response to crises.

### Bank Runs and the Panic of 1907

1. **Bank Runs and Liquidity Transformation**: The lecture delves into the Panic of 1907, highlighting the inherent risks in banks' business models. Banks perform liquidity transformation by borrowing short-term (through deposits) and lending long-term. This creates a maturity mismatch, making banks susceptible to runs if many depositors simultaneously withdraw funds, leading to a liquidity crisis even if the bank's investments are profitable.

2. **The Panic of 1907**: This crisis serves as a classic example of a bank run, exacerbated by the absence of a central bank for emergency liquidity and lack of deposit insurance. The panic was triggered by multiple factors, including the San Francisco earthquake's financial ripple effects, stock market declines, tight credit conditions, and speculative activities in the copper market. The situation escalated with the collapse of United Copper Company's stock, leading to a run on Knickerbocker Trust and subsequent bank failures.

3. **Resolution and Lessons Learned**: J.P. Morgan's intervention as a private lender of last resort helped stabilize the crisis temporarily. However, this episode underscored the limitations of relying on private entities for such roles and the need for systematic solutions like deposit insurance and a central bank. The Panic of 1907 thus played a crucial role in the establishment of the Federal Reserve System and highlighted the importance of government-backed support in maintaining financial stability.

### The Great Depression

1. **Financial Developments During the Great Depression**: The Great Depression, beginning with the stock market crash of 1929, led to a massive economic downturn. Contributing factors included a lack of central bank support and deposit insurance, leading to widespread bank failures. These bank closures drastically reduced the money supply and lending, exacerbating the economic crisis.

2. **Bank Failures and Economic Consequences**: The lecture highlights the severe consequences of large-scale bank failures during the Great Depression. Approximately 9,000 banks closed between 1929 and 1933, resulting in a sharp decrease in deposits and credit availability. The Federal Reserve's limited intervention, constrained by the gold standard, failed to prevent a severe deflationary spiral, leading to widespread bankruptcies and investment reductions.

3. **Policy Responses and Institutional Changes**: The response to the Great Depression included significant political and institutional changes. The Emergency Banking Act of 1933 and the Banking Act (Glass-Steagall Act) of 1933 reformed the banking system, establishing the Federal Deposit Insurance Corporation (FDIC) and separating commercial and investment banking. The New Deal programs aimed to alleviate unemployment and establish a social safety net. However, the recession of 1937 demonstrated the risks of withdrawing economic support prematurely. The recovery was ultimately aided by increased government spending due to the defense build-up in Europe.

### An International Perspective of Financial Crises

1. **Global Financial Crises Overview**: This lecture examines five major global financial crises: the Panic of 1873, the Baring Crisis of 1890, the Panic of 1907, the Great Depression of 1930/31, and the 2008 Financial Crisis. These crises share common themes of financial market stress, with each originating from different vulnerabilities like speculative investments, government debt, or housing markets, and spreading globally due to interconnected financial systems.

2. **Idiosyncratic Financial Crises**: The lecture contrasts global crises with more localized, idiosyncratic financial crises, using examples like Turkey's crises in 2001 and 2018, and the 1997 Asian Financial Crisis. These crises highlight vulnerabilities specific to emerging markets, such as reliance on foreign loans, political instability, and pegged exchange rates, leading to credit crunches and economic slowdowns when foreign investors withdraw their support.

3. **Common Themes and Lessons Learned**: Across all these crises, common factors include reliance on short-term funding, high leverage, and investments in long-term projects or unsustainable policies. These elements contribute to the severity and spread of financial crises, underscoring the need for robust financial systems and regulatory oversight to manage risks and prevent widespread economic downturns.

### Auto Loans During the 2008 Financial Crisis

1. **Auto Loans and Non-Bank Lenders in the 2008 Crisis**: This lecture focuses on the impact of the 2008 financial crisis on the auto loan market, highlighting the significant role of non-bank lenders, particularly captive finance companies owned by automakers. These companies, major players in auto financing, relied heavily on short-term funding through asset-backed commercial paper and securities.

2. **Crisis Impact on Captive Finance Companies**: As the crisis unfolded, investors became wary of the quality of loan pools backing asset-backed commercial papers, particularly questioning the inclusion of subprime auto loans. This skepticism led to a funding crunch as investors refused to roll over these papers, similar to a bank run, causing a dramatic tightening of credit standards by companies like General Motors Acceptance Corporation.

3. **Consequences on Auto Sales and Credit Supply**: The crisis in the asset-backed commercial paper market led to a significant drop in auto loan originations and a consequent plunge in auto sales. This drop was uneven across the country, with the most significant declines in regions where captive finance lenders had the largest market shares. The tightening of credit by these companies contributed to about one-third of the drop in auto sales during the financial crisis.

4. **Broader Implications of Non-Bank Financial Runs**: The case of captive finance companies during the 2008 crisis underscores that financial institutions engaging in maturity transformation, even outside the banking sector, are susceptible to runs. These non-bank institutions lacked access to emergency liquidity from the Federal Reserve, demonstrating a regulatory oversight in addressing risks in non-bank financial sectors.

### Credit Booms and Busts

1. **Credit Booms and Their Impact**: This lecture explores different types of credit booms and their varying outcomes. It highlights that not all credit booms lead to financial crises or severe recessions. The discussion includes international examples to understand which credit booms are most likely to have adverse effects.

2. **Global Increase in Private Credit**: Over the last five decades, there has been a significant rise in the private credit to GDP ratio globally, with household debt being a major driver. The lecture notes the shift in corporate credit from tradable sectors like manufacturing to non-tradable sectors such as construction and real estate. This shift is crucial in understanding the impact of credit booms.

3. **Case Studies of Credit Booms and Busts**: Various examples illustrate how credit booms in different sectors lead to different outcomes. Credit booms in tradable sectors, like manufacturing, are usually driven by international demand and can be sustainable. In contrast, booms in non-tradable sectors, especially real estate, are often supported only by local demand and are more likely to result in busts. The lecture examines specific cases, including the Japanese real estate boom and bust in the 1980s, the Nordic crisis in the late 1980s and early 1990s, and the Mexican Tequila Crisis, to illustrate these points.

4. **Sustainability of Credit Booms**: The lecture concludes that credit booms in the tradable sector can be sustainable due to global demand supporting additional debt. However, booms in household and construction credit, particularly when following deregulation, often lead to busts with severe negative consequences, a pattern observed in both advanced and emerging economies.

### Liquidity Provision of the Federal Reserve's Response to the 2008 Financial Crisis

1. **Federal Reserve's Response to 2008 Crisis**: This lecture examines the Federal Reserve's various programs and interventions during the 2008 financial crisis. These measures were aimed at providing short-term liquidity to banks and directly to borrowers and investors in key financial markets, illustrating the Fed's role as the lender of last resort.

2. **Short-Term Liquidity Programs**: The Fed introduced several programs to address funding pressures, especially in term lending markets. This included the Term Auction Facility (TAF) for banks, extending credit through auctions to address the stigma associated with borrowing from the Fed's discount window. The Primary Dealer Credit Facility (PDCF) provided overnight loans to primary dealers, using a wide range of collateral, and the Term Securities Lending Facility (TSLF) offered Treasury securities loans against less liquid securities.

3. **Commercial Paper and Asset-Backed Securities Support**: The Commercial Paper Funding Facility (CPFF) directly purchased high-quality commercial paper from issuers to support short-term funding markets. The Asset-Backed Commercial Paper Money Market Mutual Fund Liquidity Facility (AMLF) assisted money funds in selling asset-backed commercial paper. These facilities aimed to stabilize key financial markets outside the traditional banking system.

4. **Term Asset-Backed Securities Loan Facility (TALF)**: Established to revive the securitization markets for consumer and business loans, TALF provided loans for purchasing highly rated asset-backed securities, playing a significant role in reducing borrowing costs and restarting credit flow to consumers and businesses.

5. **Design and Impact of Federal Reserve Programs**: The Fed's programs were designed to provide necessary financing while ensuring the safety of the funds lent out. Borrowers were required to post high-quality collateral and pay interest rates above normal market rates to discourage reliance on these facilities under normal market conditions. These measures effectively supported financial markets during the crisis and were phased out as conditions normalized, fulfilling the Fed's lender of last resort function.

### Liquidity Provision of the Federal Reserve's Response to the Covid-19 Pandemic

1. **Broad Market Interventions by the Federal Reserve**: During the COVID-19 pandemic, the Federal Reserve implemented extensive measures, including purchasing treasury and mortgage-backed securities, and establishing new facilities like the Primary and Secondary Market Corporate Credit Facilities (PMCCF and SMCCF). These interventions targeted various financial markets, including corporate bonds, to ensure liquidity and stability.

2. **Innovative Programs for Diverse Economic Sectors**: The Fed introduced novel programs such as the Main Street Lending Program and the Municipal Liquidity Facility to support small and medium-sized businesses, and state and local governments. Additionally, the Payment Protection Program Liquidity Facility (PPPLF) was crucial for funding loans under the Paycheck Protection Program, aiding businesses during the pandemic's economic downturn.

3. **Effective Stabilization of Financial Markets**: The Federal Reserve's interventions were successful in stabilizing financial markets, as indicated by the rapid improvement in market conditions, like the decrease in corporate bond yields following the announcement of these measures. Despite the low usage of some facilities, the Fed's actions were effective in preventing a financial meltdown and fostering a quicker economic recovery.

### Fiscal Responses to Financial Crises

1. **Government Transfers and Support Measures**: To mitigate the effects of financial crises, governments implement direct transfers to consumers, like stimulus checks, and targeted interventions like increased unemployment benefits. Programs like the Paycheck Protection Program during COVID-19, designed to help businesses retain employees, effectively maintain consumption levels by ensuring continuous income for workers.

2. **Business Investment and Government Intervention**: Government options to stimulate business investment directly are limited. However, tax incentives or accelerated depreciation schedules can encourage business investment indirectly. The key driver for business investment remains the demand for goods.

3. **Government Spending and Fiscal Stimulus**: Government spending, especially in times of recession, can substitute for lost private demand. The effectiveness of this spending, often debated, hinges on the government spending multiplier's value. If it's greater than one, government spending effectively boosts GDP. The success of such fiscal stimulus also depends on the speed and efficiency of the expenditure and its alignment with the skills and needs of the workforce.
