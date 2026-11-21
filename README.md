# BMTC Data Lab

An independent student project that explores Bengaluru Metropolitan Transport Corporation (BMTC) operations, division-level fleet utilization, and recorded bus-stop activity using public datasets.

## Live dashboard

**[Open the BMTC Data Lab dashboard](https://bks99168-blip.github.io/bmtc-data-lab/)**

The link will work after GitHub Pages is enabled for this repository.

## What it includes

- Annual BMTC operating trends with selectable indicators
- Fleet-utilization comparisons by division and year
- Searchable stop records, route-entry details, and a coordinate plot
- Data-quality summaries and a downloadable summary CSV
- Source notes and interpretation limits alongside the charts

## Data sources and attribution

- **BMTC Stops with Location and Routes**, published by OpenCity and attributed to BMTC. OpenCity lists this dataset under **Creative Commons Attribution Share-Alike 2.0 (CC BY-SA 2.0)**. This dashboard embeds data derived from that dataset; retain the attribution and share-alike notice when redistributing the data-derived material. [Dataset page](https://data.opencity.in/dataset/bus-stops-and-routes-map-by-ward)
- **BMTC Operational Performance Data, 2012–13 to 2025–26**, published by OpenCity; the dataset page lists its license as **Other (Public Domain)**. [Dataset page](https://data.opencity.in/dataset/bmtc-operation-performance-data)
- **BMTC Fleet Utilization, 2016–20**, published by OpenCity from BMTC annual-report data; the resource metadata lists an open license. [Resource page](https://data.opencity.in/dataset/bmtc-operation-performance-data/resource/a7cd64ac-dada-4c3c-93d3-8880e0e6965e)

The dashboard also credits these sources under **Method & sources**. Check the source pages for current license wording before redistributing updated versions.

## Scope and limitations

This is a descriptive student analysis, not an official BMTC assessment or a feasibility study. The stop dataset does not define the period or method for `Num trips in stop`, so the dashboard does not interpret those values as daily frequency, ridership, passenger demand, or proof that a stop is underserved. The annual performance file does not state whether 2025–26 is complete. The datasets cover different measures and time spans and are analyzed separately.

## Run locally

Download or clone the repository, then open `index.html` in a browser. The dashboard is self-contained and embeds the source data used for this version.

## Repository contents

- `index.html` — dashboard markup, styles, scripts, and embedded source data.
- `README.md` — project overview, data attribution, and limitations.
