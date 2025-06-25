# Webull Scripting Functions Reference

This document lists the available functions in the Webull scripting environment, categorized for easy reference, based on the screenshots provided.

---

## Global Functions

* `bar_check.highest_offset`
* `bar_check.lowest_offset`
* `define`
* `fill_none`
* `hline`
* `iff`
* `none`
* `plt`
    * **Parameters for `plt`:**
        * `data (series)`: The series of data to be plotted. This can be any numerical data such as close price, moving average, etc.
        * `name (string, optional)`: The title or label for the plot. It will be displayed on the chart as the series name.
        * `color (color, optional)`: The color of the plot line. You can use built-in color constants or create your own color like "color=#0057FF".
        * `line_width (string, optional)`: The width of the plot line in pixels. A higher value makes the line thicker.
        * `type (integer, optional)`: The style of the plot line. Options include `plt.type_line`, `plt.type_linebr`, `plt.type_stepline`, `plt.type_area`, `plt.type_circles`, `plt.type_columns`, `plt.type_cross`, `plt.type_histogram`.
* `plt.fill_between`

---

## `ind.` (Indicator) Functions

* `ind.alma`
* `ind.atr`
* `ind.bb` (Bollinger Bands)
* `ind.cci` (Commodity Channel Index)
* `ind.cmo` (Chande Momentum Oscillator)
* `ind.cog` (Center of Gravity)
* `ind.correlation`
* `ind.dmi` (Directional Movement Index)
* `ind.down_trend`
* `ind.ema` (Exponential Moving Average)
* `ind.hma` (Hull Moving Average)
* `ind.kc` (Keltner Channels)
* `ind.macd` (Moving Average Convergence Divergence)
* `ind.mfi` (Money Flow Index)
* `ind.rma` (Relative Moving Average)
* `ind.rsi` (Relative Strength Index)
* `ind.sma` (Simple Moving Average)
* `ind.swma` (Smoothed Weighted Moving Average)
* `ind.tsi` (True Strength Index)
* `ind.up_trend`
* `ind.vwma` (Volume Weighted Moving Average)
* `ind.wma` (Weighted Moving Average)

---

## `math.` (Mathematical) Functions

* `math.abs` (Absolute Value)
* `math.acos` (Arc Cosine)
* `math.asin` (Arc Sine)
* `math.atan` (Arc Tangent)
* `math.avg` (Average)
* `math.ceil` (Ceiling)
* `math.cos` (Cosine)
* `math.cumsum` (Cumulative Sum)
* `math.dev` (Standard Deviation) - *Likely an alias for `std` or related.*
* `math.diff` (Difference)
* `math.exp` (Exponential)
* `math.floor` (Floor)
* `math.highest`
* `math.log` (Natural Logarithm)
* `math.log10` (Base 10 Logarithm)
* `math.lowest`
* `math.max` (Maximum)
* `math.min` (Minimum)
* `math.pow` (Power)
* `math.round` (Round)
* `math.sign` (Sign)
* `math.sin` (Sine)
* `math.sqrt` (Square Root)
* `math.std` (Standard Deviation)
* `math.stoch` (Stochastic Oscillator)
* `math.sum` (Sum)
* `math.tan` (Tangent)
* `math.variance`

---

## `time.` (Time-related) Functions

* `time.current`
* `time.current_bar`
* `time.friday`
* `time.get_day`
* `time.get_hour`
* `time.get_minute`
* `time.get_month`
* `time.get_week`
* `time.get_weekday`
* `time.get_year`
* `time.monday`
* `time.saturday`
* `time.sunday`
* `time.thursday`
* `time.tuesday`
* `time.utc`
* `time.wednesday`

---

## Variables

* `bar_check.is_first`
* `bar_check.is_historical`
* `bar_check.is_last`
* `bar_check.is_last_update`
* `bar_check.is_new`
* `bar_check.is_real_time`
* `close`
* `high`
* `hl2` (High + Low / 2)
* `hlc3` (High + Low + Close / 3)
* `hlcc4` (High + Low + Close + Close / 4)
* `low`
* `ohlc4` (Open + High + Low + Close / 4)
* `open`
* `volume`

---

## Color Constants (`color.`)

* `color.aqua`
* `color.black`
* `color.blue`
* `color.fuchsia`
* `color.gray`
* `color.green`
* `color.lime`
* `color.maroon`
* `color.navy`
* `color.olive`
* `color.orange`
* `color.purple`
* `color.red`
* `color.silver`
* `color.sys_down`
* `color.sys_up`
* `color.teal`
* `color.white`
* `color.yellow`

---

## `define.` (Input Type) Constants

* `define.bool`
* `define.float`
* `define.integer`
* `define.source`
* `define.string`

---

## `display.` (Display Mode) Constants

* `display.all`
* `display.none`

---

## `hline.type_` (Horizontal Line Type) Constants

* `hline.type_dashed`
* `hline.type_dotted`
* `hline.type_solid`

---

## `plt.type_` (Plot Type) Constants

* `plt.type_area`
* `plt.type_circles`
* `plt.type_columns`
* `plt.type_cross`
* `plt.type_histogram`
* `plt.type_line`
* `plt.type_linebr`
* `plt.type_stepline`

---
