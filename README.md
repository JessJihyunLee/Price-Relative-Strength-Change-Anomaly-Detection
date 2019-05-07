# Quantitative-Trading-using-One-Class-Support-Vector-Machine-Momentum-RSI-and-DMI
Developed highest profit generating quantitative strategies while having decreased maximum drawdown by implementing One Class Support Vector Machine, Momentum, RSI, and Dynamic Momentum Index (DMI)

# Universe
* SPY : SPDR S&P 500 ETF<br/>
* EWY : iShares MSCI South Korea ETF<br/>
* EWJ : iShares MSCI Japan ETF<br/>
* EWQ : iShares MSCI France ETF<br/>
* EWZ : iShares MSCI Brazil ETF<br/>
* VEIEX : Vanguard Emerging Markets Stock Index Fund<br/>
* EWL : iShares MSCI Switzerland ETF<br/>
* VGSIX : Vanguard Real Estate Index Fund<br/>
* VGPMX : The Vanguard Global Capital Cycles Fund<br/>
* IXC : iShares Global Energy ETF<br/>
* All data read by python yahoo finance data reader from 2002 to 2019<br/>

# Strategies
1. __6 Month Momentum comparing to SHY__<br/>
2. __6 Month Momentum after filtering based on RSI (Relative Strength Index)__<br/>
3. __6 Month Momentum after filtering based on DMI (Dynamic Momentum Index)__<br/>
4. __6 Month Momentum after filtering based on RSI/DMI Outlier Detection - used One-Class SVM__<br/>
Here, compared performance to equal-weighted ETFs and SPY

# Result and Insights
* Performance comparison of strategies<br/>
![](/performance.png)<br/>
* Detailed insights and motive of using each strategy is explained in following [presentation](https://drive.google.com/file/d/1V75Y8by6Uq2ME7aTnFgz5f1aEJbUttWc/view?usp=sharing)
