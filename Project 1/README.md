# Project Title: Investor Advisor Application

This project includes a Jupyter notebook that contains the code for an analysis of investment in both cryptocurrency and stocks using the Monte Carlo simulation.

Additionally, a command line application is included to take an initial monthly investment and determine the current portfolio's worth based on the last 3 years.

Demo:
---
https://user-images.githubusercontent.com/34729547/186523361-342275ee-9775-4b3e-b75f-ee1e5d6464d7.mp4


Dataset:
---
SAMPLE.env

Final Analysis:
---

When analyzing the initial monthly investment of $1800, we split the investment 50/50 across both Bitcoin and S&P 500 ETF. 

Based on the last 3 years to today, a $900 BTC investment would produce a total current BTC coins of 2.08038. As of 8/24/2022 (4:43 PM EST), the price of BTC is $21711.49. The total current Bitcoin wallet would be worth $45,168.14 (USD).

Based on the last 3 years to today, a $900 SPY investment would produce a total current SPY shares of 93.73168. As of 8/24/2022 (4:43 PM EST), the price of SPY is $413.67. The total current S&P 500 ETF wallet would be worth $38,773.98 (USD).

![image](https://user-images.githubusercontent.com/34729547/186520835-eec419fd-aad5-4ed8-a276-604d86f11f17.png)

With a combined portfolio of both cryptocurrency and stock, the total value of the portfolio would be worth $83,942.13 (USD). Although the initial investment was a 50/50 split, Bitcoin outperformed the S&P 500 ETF by 7.6%.

![image](https://user-images.githubusercontent.com/34729547/186520932-4cecb670-3d28-40d6-89a6-f15b6485c350.png)

When analyzing the performance of the 10-year aggressive investment, the cryptocurrency was weighted by 80%, and the stock was weighted by 20%. There is a 95% chance that an initial investment of $1800 in the portfolio over the next 10 years will end within the range of $1187.45 and $1,666,283.18.

![image](https://user-images.githubusercontent.com/34729547/186521815-95ef8f58-a839-42a2-9d86-24eecaeed047.png)

![image](https://user-images.githubusercontent.com/34729547/186521891-89eccbad-d0cd-49f7-947c-1f456eb63640.png)

We can conclude that weighting the portfolio more heavily to Bitcoin over the S&P 500 ETF will allow the investor to retire after only 10 years if the volatility of cryptocurrency stays low.

---

## Technologies: Python 3, Jupyter Notebook, Alpaca SDK, YFinance

Python 3 or later.

Jupyter Notebook for IDE.

Alpaca API 

YFinance API

---

## Usage: python investor_advisor.py
---

Ensure the proper libraries and dependencies have been imported.

![image](https://user-images.githubusercontent.com/34729547/186522557-e14ee3fa-13bd-4a9e-bfcb-4737d3b866a6.png)

---

## Contributors: Nia Robinson, Isaiah Robinson

LinkedIn: https://www.linkedin.com/in/niaelanrobinson/, https://www.linkedin.com/in/isaiah-robinson-275399178/

---

## License

MIT License.
