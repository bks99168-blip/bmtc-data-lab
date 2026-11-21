# BMTC Data Lab

An independent student dashboard for exploring Bengaluru Metropolitan Transport Corporation (BMTC) operating trends, divisional fleet utilization, and stop-level recorded activity.

## Open the dashboard

Open `index.html` in a web browser. The dashboard is self-contained and embeds the source data used for its current analysis.

To publish it free with GitHub Pages, upload `index.html` and this README to the root of a **public** GitHub repository, then enable Pages in **Settings → Pages** with deployment from the `main` branch and `/ (root)` folder.

## Data sources and attribution

- **BMTC Stops with Location and Routes**, published by OpenCity and attributed to BMTC. OpenCity lists this dataset under **Creative Commons Attribution Share-Alike 2.0 (CC BY-SA 2.0)**. This dashboard embeds data derived from that dataset. Please retain this attribution and share-alike notice when redistributing the data-derived material. [Dataset page](https://data.opencity.in/dataset/bus-stops-and-routes-map-by-ward)
- **BMTC Operational Performance Data, 2012–13 to 2025–26**, published by OpenCity; the dataset page lists its license as **Other (Public Domain)**. [Dataset page](https://data.opencity.in/dataset/bmtc-operation-performance-data)
- **BMTC Fleet Utilization, 2016–20**, published by OpenCity from BMTC annual-report data; its resource metadata lists an open license. [Resource page](https://data.opencity.in/dataset/bmtc-operation-performance-data/resource/a7cd64ac-dada-4c3c-93d3-8880e0e6965e)

The source files are credited in the dashboard under **Method & sources**. Verify license wording on the source pages before redistributing updated versions.

## Scope and limitations

This is a descriptive student analysis, not an official BMTC assessment or a feasibility study. The stop dataset does not define the period or method for its `Num trips in stop` field, so the dashboard does not interpret those counts as daily frequency, ridership, passenger demand, or proof that a stop is underserved. The annual performance file does not state whether 2025–26 is complete. The three datasets cover different measures and time spans and are shown separately.

## Contents

- `index.html` — dashboard interface, styles, scripts, and embedded source data.
