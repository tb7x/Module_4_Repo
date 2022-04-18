# Module_4_Repo

# This project uses algorithms to alalyze the performance, volatility, and risk-return, of each of the four portfolios. Then the variance will be calculated for the two best recommended portfolios in order to diversify them.
---

## Technologies

# This project is written with the programming language python. It also uses the libraries Pandas, numpy, and matplot. The project was written on the macOS operating system.
---

## Installation Guide

```
whale_navs = pd.read_csv(Path("./Resources/whale_navs.csv"), index_col = "date", parse_dates = True, infer_datetime_format = True)
```

## Usage

```
fund_daily_returns = daily_returns.drop(columns = ["S&P 500"])
fund_daily_returns.plot.box(figsize=(20,10), title = "Portfolio Volatility")

---

## Contributors


# Creator of this project is Thomas Burns
# Email is burns235577@gmail.com
---









