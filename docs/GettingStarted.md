# Getting Started with Azullian Indicators

## Introduction

Welcome to the Azullian indicators! This guide will introduce you to the unique modular system of chaining indicators, the role of the Signal Filter as a central hub, and the strategic focus on risk mitigation. We will also explain the crucial role of `azLibConnector` in facilitating this ecosystem.

## The Concept of Indicator Chaining

In the Azullian system, indicators are daisy-chained or directly chained, culminating in a Signal Filter. This modular approach allows for dynamic combinations of indicators, each contributing to a collective analysis for robust trade signaling.

### Indicator Chaining Components:

- **Individual Indicators**: Each serves a specific analytical purpose (trend, momentum, volume, etc.).
- **Signal Filter**: Functions as a central connection hub and a visual monitoring point. It also acts as a conditional funnel leading towards the strategy, focusing on risk mitigation.
- **Strategy Module**: Solely focused on managing risk, taking into account the collective input from the chained indicators.

## Using the azLibConnector

The `azLibConnector` is a key component in this architecture. It allows every connectable indicator to communicate seamlessly, ensuring modularity and compatibility. This tool enables indicators, whether developed by us or the community, to interact effectively for position signals (long or short) with varying signal weights.

### Benefits of azLibConnector:

- **Modularity**: Indicators remain independent units that can be easily combined.
- **Community Development**: Encourages community contributions while maintaining compatibility and standardization.
- **Dynamic Signal Weighting**: Each indicator contributes to the final signal with a certain weight, allowing for a nuanced decision-making process.

## Chaining Example

Consider a chain that includes a Moving Average (MA) indicator, a Relative Strength Index (RSI), and a MACD, all connected through the Signal Filter to a risk-focused strategy module:

1. **MA Indicator**: Provides trend direction.
2. **RSI**: Indicates overbought or oversold conditions.
3. **MACD**: Offers insight into momentum and potential reversals.

These indicators feed into the Signal Filter, which evaluates and balances these inputs, forwarding a consolidated signal to the strategy module focused on risk mitigation.

## Next Steps

- For individual indicator guides, refer to our [Indicator Guides](/docs/IndicatorGuides) section.
- Explore advanced chaining techniques and risk management strategies in [AdvancedUsage.md](/docs/AdvancedUsage.md).

We encourage you to experiment with different combinations and find the chain that best suits your trading style and objectives. Happy trading!

