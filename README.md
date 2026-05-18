# My Stock Portfolio — Home Assistant Integration

> If you run into a problem, please [open an issue](https://github.com/slvantage007/ha-my-stock/issues) so it can be tracked and fixed.

Track your stock portfolio powered by Yahoo Finance.

**No API key required. Fully configured through the UI — no YAML needed.**


| Field | Description |
|---|---|
| **Symbol** | Yahoo Finance ticker (see examples below) |
| **Name** | Display name shown in the card (optional — falls back to the symbol if left empty) |
| **Qty** | Qty shown in the card (optional — ignored if left empty) |
| **AvgCost** | Average cost shown in the card (optional — ignored if left empty) |
| **Update interval** | How often to poll Yahoo Finance in seconds (60–86400, default 900) |

Repeat for each asset you want to track. Each asset becomes its own sensor entity.

Thanks to https://github.com/derspe/ha-easy-stock