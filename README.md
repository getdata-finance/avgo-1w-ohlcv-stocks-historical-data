# AVGO 1w OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-370_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 1w OHLCV stocks historical data** — ultra high-quality 1w OHLCV for **Broadcom**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **Broadcom** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **370** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `AVGO_1w.csv` (106 rows, `2016-05-26` -> `2026-09-10`, 9.13 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **370** `1w` rows (full `1m`: 111,138), **11 timeframes**, `2011-05-05` -> `2026-09-10`.

## Download sample

**[AVGO_1w.csv](https://github.com/getdata-finance/avgo-1w-ohlcv-stocks-historical-data/blob/main/AVGO_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-1w-ohlcv-stocks-historical-data/main/AVGO_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/avgo-1w-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/avgo-1w-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/avgo-1w-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/avgo](https://getdata.finance/datasets/avgo)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | Broadcom · US stocks | Broadcom · US stocks |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 106 | **370** |
| Size | 9.13 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Period | `2016-05-26` -> `2026-09-10` | `2011-05-05` -> `2026-09-10` |
| File | `AVGO_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/avgo) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AVGO_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2016-05-26T00:00:00+00:00 | 153.51 | 155.27 | 151.8 | 154.78 | 17081 |
| 2016-06-02T00:00:00+00:00 | 154.78 | 165.91 | 153.34 | 163.73 | 23646 |
| 2016-06-09T00:00:00+00:00 | 163.73 | 165 | 158.13 | 158.45 | 22715 |
| 2016-06-16T00:00:00+00:00 | 158.45 | 159.53 | 154.8 | 155.09 | 23003 |
| 2016-06-23T00:00:00+00:00 | 155.09 | 158.56 | 142.17 | 155.03 | 31782 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-13T00:00:00+00:00 | 415.93 | 424.95 | 357.53 | 362.29 | 131254.14913 |
| 2026-08-20T00:00:00+00:00 | 362.29 | 374.93 | 349.98 | 355.44 | 113682 |
| 2026-08-27T00:00:00+00:00 | 355.44 | 376.38 | 355.44 | 367.52 | 117085 |
| 2026-09-03T00:00:00+00:00 | 367.52 | 372.57 | 342.26 | 364.47 | 147000 |
| 2026-09-10T00:00:00+00:00 | 364.47 | 366.52 | 357.53 | 361.9 | 45201 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **AVGO** archive on **[getdata.finance](https://getdata.finance/datasets/avgo)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **370** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**

---
*GetData · AVGO 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/avgo)*
