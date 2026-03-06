# 254Market 🇰🇪
### Kenya Economic Intelligence Dashboard

> Real-time economic intelligence for Kenyans — tracking currency, commodities, threats, and global market forces that affect everyday life.

---

## What is 254Market?

**254Market** is a free, open-source economic intelligence dashboard built specifically for Kenya. The name is a nod to Kenya's international dialing code (+254) — this is intel *by* Kenyans, *for* Kenyans.

It tracks the economic signals that matter most to ordinary Kenyans: the shilling's strength against the dollar, food prices, fuel costs, global threats to supply chains, and how major shifts in US and global markets trickle down to Nairobi, Mombasa, Kisumu, and every county in between.

No paywalls. No signup. No ads. Just data.

---

## Features

### 📡 Live Data (Free APIs, No Key Required)
- **KES/USD live rate** — updated every 5 minutes via Frankfurter API
- **9 currency crosses** — USD, EUR, GBP, AED, CNY, ZAR, UGX, TZS, ETB against KES
- **Gold price (XAU/USD)** — safe haven indicator
- **Auto-refresh** every 5 minutes with manual refresh button
- **East Africa Time (EAT) clock** — live

### 🚨 Threat Intelligence
- Active threat matrix with severity scoring (1–10)
- Visual threat bars with Kenya-specific data points
- Timeline to impact for each threat
- Alert ticker with live risk signals

### 💱 Currency Forecast
- 21-day KES/USD scenario forecasts (Bull / Base / Bear)
- Probability-weighted outlook
- Central forecast updated with each analysis cycle

### 🇺🇸 US Market → Kenya Transmission Monitor
- Tracks how US economic shifts trickle down to Kenya
- Covers: tariffs, AI layoffs, Fed rates, fintech, real asset rotations

### 📅 21-Day Impact Timeline
- Week-by-week projection of economic pain for Kenyan households
- Covers fuel prices, food prices, FX rate, and logistics disruption

### 📰 Intelligence Feed
- Critical alerts, market movements, and opportunity signals
- Curated from Business Daily, Nation Africa, Reuters Africa, Al Jazeera, CNBC

### 📊 Kenya Macro Indicators
- Grain reserve fill rate
- Petrol price (KSh/L)
- Maize price (KSh/90kg bag)
- Unga price (KSh/2kg)
- CBK base rate
- FX reserve import cover
- Gulf flight status
- Hormuz oil flow %

---

## Data Sources

| Data Point | Source | Update Frequency |
|---|---|---|
| KES/USD, currency crosses | [Frankfurter API](https://www.frankfurter.app/) | Real-time (5min refresh) |
| Gold price (XAU) | Frankfurter API | Real-time |
| Fuel prices | EPRA Kenya monthly gazette | Monthly |
| Grain reserves | NCPB / Ministry of Agriculture | When published |
| Macro indicators | CBK, Kenya National Bureau of Statistics | Quarterly / Monthly |
| Threat intelligence | Business Daily, Nation, Reuters Africa, Al Jazeera | Curated manually |
| US market analysis | Financial Times, CNBC, Bloomberg | Curated manually |

---

## Contributing

254Market is built for the people of Kenya. Contributions are welcome from developers, economists, journalists, and data analysts.

```
1. Fork the repo
2. Create your feature branch: git checkout -b feature/nse-tracker
3. Commit your changes: git commit -m 'Add NSE live tracker'
4. Push to the branch: git push origin feature/nse-tracker
5. Open a Pull Request
```

Areas where help is most needed:
- **Data journalists** — curating and verifying intel feed stories
- **Backend developers** — building a lightweight API layer for cached data
- **Mobile developers** — PWA / Android wrapper
- **Economists** — validating forecasting models and scenario logic
- **Translators** — Swahili, Kikuyu, Luo, Kalenjin interfaces

---

## Why 254Market?

Kenya is one of the most economically dynamic countries in Africa — yet most economic intelligence tools are built for institutional investors in New York or London. The average Kenyan importer, farmer, small business owner, or salaried worker has no easy way to see:

- Why the price of unga went up this week
- Whether the shilling is about to weaken further
- How a war in the Middle East affects their fuel bill next month
- What US trade policy means for their job in Kisumu's EPZ

254Market bridges that gap. Economic intelligence should be a public good.

---

## License

MIT License — free to use, modify, and distribute. Attribution appreciated.

---

*254Market is not a financial advisor. All data is for informational purposes only. Do your own research before making financial decisions.*

*Built with 🇰🇪 for Kenya — March 2026*
