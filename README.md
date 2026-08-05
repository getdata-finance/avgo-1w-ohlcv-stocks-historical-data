# AVGO 1w OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-866_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 1w OHLCV us stocks historical data** — ultra high-quality 1w OHLCV for **AVGO**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **AVGO** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **8 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **866** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `AVGO_1w.csv` (10 rows, `2026-05-28` -> `2026-07-30`). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **866** `1m` rows (~0.08 MB), **8 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 3D · 1W), `2009-12-31` -> `2026-07-30`.

## Download sample

**[AVGO_1w.csv](https://github.com/getdata-finance/avgo-1w-ohlcv-stocks-historical-data/blob/main/AVGO_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-1w-ohlcv-stocks-historical-data/main/AVGO_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/avgo-1w-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/avgo-1w-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/avgo-1w-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/avgo](https://getdata.finance/datasets/avgo)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | AVGO · US stocks | AVGO · US stocks |
| Timeframes | `1w` (sample) | **8** — 1m · 3m · 5m · 15m · 30m · 1H · 3D · 1W |
| 1m rows | 10 | **866** |
| Size | 0.00 MB | ~0.08 MB |
| Period | `2026-05-28` -> `2026-07-30` | `2009-12-31` -> `2026-07-30` |
| File | `AVGO_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **8 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **3D** · **1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/avgo) = all **8** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AVGO_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-05-28T00:00:00+00:00 | 476.47 | 548.9 | 468.22 | 531.28 | 134001 |
| 2026-06-04T00:00:00+00:00 | 531.28 | 531.28 | 424.52 | 426.37 | 183278 |
| 2026-06-11T00:00:00+00:00 | 426.37 | 454.76 | 425.1 | 447.18 | 211953 |
| 2026-06-18T00:00:00+00:00 | 447.18 | 468.46 | 431.17 | 436.16 | 175939 |
| 2026-06-25T00:00:00+00:00 | 436.16 | 442.11 | 414.68 | 423.43 | 202608 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-02T00:00:00+00:00 | 423.43 | 449.17 | 410.61 | 442.67 | 201466 |
| 2026-07-09T00:00:00+00:00 | 442.67 | 461.72 | 437.71 | 448.52 | 179896 |
| 2026-07-16T00:00:00+00:00 | 448.52 | 452.75 | 411.97 | 450.98 | 124265 |
| 2026-07-23T00:00:00+00:00 | 450.98 | 451.8 | 423.71 | 424.29 | 92162 |
| 2026-07-30T00:00:00+00:00 | 424.29 | 453.89 | 424.29 | 443.18 | 35901 |

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

df = pd.read_csv('AVGO_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AVGO_1w.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AVGO_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AVGO** archive on **[getdata.finance](https://getdata.finance/datasets/avgo)** includes **8 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 3D · 1W) — **866** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**

---
*GetData · AVGO 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/avgo) · 2026-08-05 UTC*
