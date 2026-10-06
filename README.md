# Eurozone Debt vs. Yield

An interactive scatter of government debt-to-GDP against long-term government bond yields for 18 eurozone (and future-eurozone) countries, 1995 to 2026. Drag the year slider or press play to watch the relationship move. Each year shows a linear fit and a quadratic fit with live r and R².

Open `index.html` in a browser, or view it on GitHub Pages once enabled.

## Data

- **Debt:** IMF World Economic Outlook database, general government gross debt (% of GDP). 2025 and 2026 are IMF estimates, not final actuals.
- **Yields:** OECD Main Economic Indicators, long-term interest rates (year-end or latest available month).
- Cyprus and Malta are excluded because they are not OECD members and have no comparable yield series.
- Countries enter the sample in the year their series begins, so the number of points grows over time.

`data.json` holds the same dataset the page embeds.

## Notes

Correlation between debt and yield across countries is not proof of causation. High yields also raise interest costs and push debt up. Within a currency union, the monetary system is held fixed, so the remaining variation in yields is mostly fiscal, but ECB programs and safe-haven or scarcity premia also shape the spreads.
