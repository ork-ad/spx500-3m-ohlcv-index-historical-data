# SPX500 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_941_929_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full SPX500 dataset on ork.ad**](https://ork.ad/)

**SPX500 3m OHLCV Stock index historical data** — ultra high-quality 3m OHLCV for **S&P 500**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **S&P 500** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **1,941,929** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `SPX500_3m.csv` (59,143 rows, `2026-01-04` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **1,941,929** `3m` rows (~104.48 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-08-19` → `2026-07-03`.

## Download sample

**[SPX500_3m.csv](https://github.com/ork-ad/spx500-3m-ohlcv-index-historical-data/blob/main/SPX500_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/spx500-3m-ohlcv-index-historical-data/main/SPX500_3m.csv)) · [GitHub Releases](https://github.com/ork-ad/spx500-3m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/spx500-3m-ohlcv-index-historical-data/](https://ork-ad.github.io/spx500-3m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | S&P 500 · Stock index | S&P 500 · Stock index |
| Timeframes | `3m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 3m rows | 59,143 | **1,941,929** |
| Size | 3.29 MB | ~104.48 MB |
| Period | `2026-01-04` → `2026-07-03` | `2008-08-19` → `2026-07-03` |
| File | `SPX500_3m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`3m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `3m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`SPX500_3m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T23:00:00Z | 6855.43 | 6866.27 | 6855.43 | 6863.65 | 1273.0 |
| 2026-01-04T23:03:00Z | 6863.65 | 6863.78 | 6860.4 | 6861.02 | 415.0 |
| 2026-01-04T23:06:00Z | 6861.02 | 6861.41 | 6855.64 | 6858.15 | 434.0 |
| 2026-01-04T23:09:00Z | 6858.15 | 6860.77 | 6857.4 | 6857.64 | 209.0 |
| 2026-01-04T23:12:00Z | 6857.64 | 6858.65 | 6854.65 | 6857.65 | 223.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T16:45:00Z | 7501.63 | 7502.13 | 7499.61 | 7499.86 | 127.0 |
| 2026-07-03T16:48:00Z | 7499.86 | 7499.86 | 7497.98 | 7499.12 | 109.0 |
| 2026-07-03T16:51:00Z | 7499.12 | 7499.62 | 7498.61 | 7499.61 | 120.0 |
| 2026-07-03T16:54:00Z | 7499.61 | 7501.12 | 7498.99 | 7501.12 | 70.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('SPX500_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('SPX500_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('SPX500_3m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **SPX500** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **1,941,929** rows at `3m`, plus all other timeframes in the same ZIP.

**[→ Get the full SPX500 dataset on ork.ad](https://ork.ad/)**

---
*GetData · SPX500 3m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*