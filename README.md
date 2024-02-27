# Connectable TradingView Indicators

## Table of Contents

- [Overview](#overview)
- [Installation and Usage](#installation-and-usage)
- [Contributing](#contributing)
- [List of Indicators](#list-of-indicators)
- [Contact and Support](#contact-and-support)
- [License](#license)



## Overview

Welcome to the Connectable TradingView Indicators repository. This collection represents a collaborative effort to create a modular approach to connectable uniform indicators, for trading on spot and futures. These tools are designed to enhance market analysis, improve trading strategies, and offer insights into various financial instruments. Whether you are a seasoned trader or just starting, our indicators aim to be a valuable resource in your trading journey.

### Key Features

- Maximize Indicator Versatility: Build Once, Utilize Everywhere
- Chain indicators both directly and sequentially in a unified system.
- Dispatch weighted signals in a uniform approach.
- Refine signal management.
- Apply advanced techniques for risk and profit mitigation.

### Connectable System Insights

A Closer Look at How the System Operates:

- Weighted signals: Each connectable indicator can send weighted positions for both long and short via the Azullian input source, our signal connector.
- Direct or daisy chain: Link indicators directly or sequentially to the signal filter, monitor, or strategy.
- Signal management: Monitor incoming signals in an easy graphical interface or moderate the signal with the signal filter.
- Customize Signals: Adjust settings, thresholds, and conditions to align with your trading goals.
- Strategize: Add a connectable strategy to complete your chain and start testing instantly with advanced risk mitigation.

### Effortlessly Layer Visual Cues on TradingView

Identify, iterate, and test quicker:

- Replace a cluttered stack of indicators with a signal filter connection for a cleaner, more streamlined view.
- Minimal configurable visual cues enhance chart readability, making it simpler to identify confluence across multiple active indicators.
- Visual cues are strategically placed in relation to candles, reflecting your specific entry or exit conditions. A prominent icon also appears to indicate when key overarching conditions are fulfilled.

## Installation and Usage

To use these indicators on TradingView:

1. Clone or download the repository.
2. Select the indicator script you wish to use (e.g., `adxIndicator.pine`).
3. Copy the Pine Script code.
4. On TradingView, open the Pine Editor.
5. Paste the copied script and save it.
6. Add the saved indicator to your chart.

Detailed instructions for each indicator are available in the [docs](/docs) folder.

## Contributing

We warmly welcome contributions from the community. If you have an idea for a new indicator or improvements to existing ones, please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute.

## Indicator guides

- **[ADX (Average Directional Index)](docs/IndicatorGuides/ADX/ADXIndicator.md)**
- **[BB (Bollinger Bands)](docs/IndicatorGuides/BB/BBIndicator.md)**
- **[CCI (Commodity Channel Index)](docs/IndicatorGuides/CCI/CCIIndicator.md)**
- **[DO (Donchian Channels)](docs/IndicatorGuides/DO/DOIndicator.md)**
- **[KDJ](docs/IndicatorGuides/KDJ/KDJIndicator.md)**
- **[MA (Moving Average)](docs/IndicatorGuides/MA/MAIndicator.md)**
- **[MACD (Moving Average Convergence Divergence)](docs/IndicatorGuides/MACD/MACDIndicator.md)**
- **[Monitor](docs/IndicatorGuides/MONITOR/MONITORIndicator.md)**
- **[RSI (Relative Strength Index)](docs/IndicatorGuides/RSI/RSIIndicator.md)**
- **[Signal Filter](docs/IndicatorGuides/SIGNAL%20FILTER/SignalFilterIndicator.md)**
- **[Stochastic](docs/IndicatorGuides/STO/STOIndicator.md)**
- **[Strategy](docs/IndicatorGuides/Strategy/StrategyIndicator.md)**

## Library guides
- **[azLibConnector(Signal connector)](docs/IndicatorGuides/ADX/ADXIndicator.md)**

## Contact and Support

If you have any questions, suggestions, or need support, feel free to [open an issue](https://github.com/azullian/connectable/issues) or contact us directly.

## License

This project is licensed under the [MIT License](LICENSE.md) - see the LICENSE file for details.
