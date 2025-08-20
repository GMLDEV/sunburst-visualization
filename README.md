# Advanced Data Visualization: Sunburst Diagram

This repository contains a publication-ready Sunburst Diagram created with RAWGraphs, visualizing organizational spending breakdown by department and expense type.

- **Author contact (required):** 23f2005402@ds.study.iitm.ac.in

## Files
- `chart.png` — Sunburst Diagram (300–512 px, PNG format)
- `README.md` — This file

## How to reproduce
1. Prepare CSV data with fields: `department`, `expense`, `amount`.
2. Go to [RAWGraphs.io](https://rawgraphs.io/).
3. Import the CSV data.
4. Select **Sunburst Diagram**.
5. Map:
   - Hierarchy → `department`, then `expense`
   - Size → `amount`
   - Color → `department`
6. Export the chart as **PNG (512x512 px)**.
