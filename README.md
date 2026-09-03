# EURJPY 1w OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_904_rows-blue)](https://getdata.finance/datasets/eurjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurjpy)

### -> [**Download the full EURJPY dataset on getdata.finance**](https://getdata.finance/datasets/eurjpy)

**EURJPY 1w OHLCV forex historical data** — ultra high-quality 1w OHLCV for **Euro / Japanese Yen**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **Euro / Japanese Yen** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurjpy) · **2,904** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `EURJPY_1w.csv` (7 rows, `2026-07-16` -> `2026-08-27`, 0.65 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurjpy)** — **2,904** `1w` rows (full `1m`: 9,228,234), **11 timeframes**, `1970-12-31` -> `2026-08-27`.

## Download sample

**[EURJPY_1w.csv](https://github.com/getdata-finance/eurjpy-1w-ohlcv-forex-historical-data/blob/main/EURJPY_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurjpy-1w-ohlcv-forex-historical-data/main/EURJPY_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurjpy-1w-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurjpy-1w-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurjpy-1w-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurjpy](https://getdata.finance/datasets/eurjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurjpy))** |
|---|--:|---|
| Instrument | Euro / Japanese Yen · Forex | Euro / Japanese Yen · Forex |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 7 | **2,904** |
| Size | 0.65 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurjpy) |
| Period | `2026-07-16` -> `2026-08-27` | `1970-12-31` -> `2026-08-27` |
| File | `EURJPY_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurjpy) |
| Coverage report | — | [EURJPY coverage](https://getdata.finance/coverage/eurjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurjpy)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/eurjpy) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURJPY_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-16T00:00:00+00:00 | 185.777 | 186.664 | 185.344 | 186.358 | 2496148 |
| 2026-07-23T00:00:00+00:00 | 186.358 | 187.472 | 182.099 | 183.878 | 3254239 |
| 2026-07-30T00:00:00+00:00 | 183.878 | 185.168 | 179.357 | 182.547 | 3284337 |
| 2026-08-06T00:00:00+00:00 | 182.547 | 183.966 | 181.297 | 183.847 | 2296583 |
| 2026-08-13T00:00:00+00:00 | 183.847 | 185.833 | 183.598 | 185.724 | 2200123 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-30T00:00:00+00:00 | 183.878 | 185.168 | 179.357 | 182.547 | 3284337 |
| 2026-08-06T00:00:00+00:00 | 182.547 | 183.966 | 181.297 | 183.847 | 2296583 |
| 2026-08-13T00:00:00+00:00 | 183.847 | 185.833 | 183.598 | 185.724 | 2200123 |
| 2026-08-20T00:00:00+00:00 | 185.724 | 186.022 | 185.148 | 185.73 | 1156276 |
| 2026-08-27T00:00:00+00:00 | 185.73 | 185.993 | 184.921 | 185.677 | 1389204 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EURJPY_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURJPY_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('EURJPY_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **EURJPY** archive on **[getdata.finance](https://getdata.finance/datasets/eurjpy)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,904** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full EURJPY dataset on getdata.finance](https://getdata.finance/datasets/eurjpy)**

---
*GetData · EURJPY 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurjpy)*
