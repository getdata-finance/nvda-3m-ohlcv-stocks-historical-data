# NVDA 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-201_583_rows-blue)](https://getdata.finance/datasets/nvda) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nvda)

### -> [**Download the full NVDA dataset on getdata.finance**](https://getdata.finance/datasets/nvda)

**NVDA 3m OHLCV stocks historical data** — ultra high-quality 3m OHLCV for **NVIDIA**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **NVIDIA** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nvda) · **201,583** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `NVDA_3m.csv` (16,510 rows, `2026-03-23` -> `2026-09-22`, 1.47 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/nvda)** — **201,583** `3m` rows (full `1m`: 598,377), **11 timeframes**, `2020-07-14` -> `2026-09-22`.

## Download sample

**[NVDA_3m.csv](https://github.com/getdata-finance/nvda-3m-ohlcv-stocks-historical-data/blob/main/NVDA_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nvda-3m-ohlcv-stocks-historical-data/main/NVDA_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/nvda-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/nvda-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/nvda-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/nvda](https://getdata.finance/datasets/nvda)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nvda))** |
|---|--:|---|
| Instrument | NVIDIA · US stocks | NVIDIA · US stocks |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 16,510 | **201,583** |
| Size | 1.47 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Period | `2026-03-23` -> `2026-09-22` | `2020-07-14` -> `2026-09-22` |
| File | `NVDA_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Coverage report | — | [NVDA coverage](https://getdata.finance/coverage/nvda) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nvda)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/nvda) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NVDA_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T13:30:00+00:00 | 170.97 | 175.32 | 170.97 | 175.04 | 2057 |
| 2026-03-23T13:33:00+00:00 | 175.04 | 175.64 | 174.69 | 174.73 | 2377 |
| 2026-03-23T13:36:00+00:00 | 174.73 | 175.57 | 174.68 | 175.08 | 3321 |
| 2026-03-23T13:39:00+00:00 | 175.08 | 175.46 | 174.71 | 174.98 | 2855 |
| 2026-03-23T13:42:00+00:00 | 174.98 | 175.25 | 174.51 | 174.54 | 2729 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-22T19:45:00+00:00 | 229.01 | 229.23 | 228.93 | 229.23 | 529 |
| 2026-09-22T19:48:00+00:00 | 229.23 | 229.54 | 229.1 | 229.47 | 628 |
| 2026-09-22T19:51:00+00:00 | 229.47 | 229.75 | 229.32 | 229.58 | 673 |
| 2026-09-22T19:54:00+00:00 | 229.58 | 229.62 | 228.52 | 228.78 | 1041 |
| 2026-09-22T19:57:00+00:00 | 228.78 | 228.86 | 228.58 | 228.68 | 1135 |

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

df = pd.read_csv('NVDA_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NVDA_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('NVDA_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **NVDA** archive on **[getdata.finance](https://getdata.finance/datasets/nvda)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **201,583** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full NVDA dataset on getdata.finance](https://getdata.finance/datasets/nvda)**

---
*GetData · NVDA 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/nvda)*
