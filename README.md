# UK Regional Carbon Intensity Explorer

Interactive web visualisation of carbon intensity across 14 GB electricity regions, using data from the [National Grid ESO Carbon Intensity API](https://carbonintensity.org.uk/).

## Features

- **Live Dashboard** — Real-time carbon intensity for all regions with colour-coded severity indicators
- **Regional Map** — Interactive SVG map of GB regions with click-for-details
- **Historical Trends** — Monthly time series with selectable regions (2018–2026)
- **Heatmap** — Intensity patterns by hour of day, month, or day of week
- **Daily Patterns** — Average hourly profiles showing when intensity peaks and troughs
- **Seasonal Analysis** — Month-by-month breakdown revealing winter/summer variation
- **Regional Comparison** — Ranked bar charts of average intensity and variability
- **Statistics** — Summary stats (mean, min, max, std dev) for each region

## Data

- **Live data**: Fetched from the [Carbon Intensity API](https://api.carbonintensity.org.uk/regional) in real time
- **Historical data**: Pre-processed from 130,000+ half-hourly observations (Sep 2018 – Mar 2026) into aggregated JSON files

## Tech Stack

Pure HTML/CSS/JS with [Chart.js](https://www.chartjs.org/) for charts. No build step required — works as a static site on GitHub Pages.

## License

Data provided by National Grid ESO under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
