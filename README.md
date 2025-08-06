# Rupee Volume Indicator in Currency (₹) (Pine Script)

This indicator calculates **volume in currency value (₹)** instead of just quantity. Useful for spotting smart money participation using price × volume turnover logic. It helps detect **institutional activity**, large trades, or smart money flow — especially useful in **Indian markets**.

##  Alert Logic

You can create alerts when **rupee volume spikes** when vol > avg vol (e.g. large institutions buying/selling):

##  Features

-  **Rupee Volume**: Uses price volume to show turnover in actual money.
-  **Custom Units**: Choose from ₹ / K / Lakhs / Crores.
-  **Bar Coloring**: Based on either candle direction or volume increase.
-  **Moving Average Line**: SMA or EMA of rupee volume.
-  **Info Table**: Volume and average on latest bar (shown on left).
-  **Hover Support**: Shows rupee volume in TradingView's **Data Window**.
-  **Alert Ready**: Get alerts when a big volume spike happens (`> 1.1x avg`).
-  Fully configurable and beginner-friendly.

## Preview
<img width="1767" height="305" alt="image" src="https://github.com/user-attachments/assets/5e3c9a35-3643-4428-b87b-dcc299b2d29d" />

##  Input Settings

| Setting              | Description |
| **Price Source**     | `close`, `hlc3`, `ohlc4`, etc. |
| **Unit**             | ₹, K, Lakhs, Crores |
| **MA Type**          | `SMA` or `EMA` |
| **Bar Color Method** | `Price Based` or `Volume Based` |
| **Colors**           | Custom for up/down bars and avg line |

---

##  Installation

1. Open TradingView
2. Open **Pine Script Editor**
3. Paste the content from `VolumeInRupees.pine`
4. Click **Add to Chart**
5. Customize from the settings icon





