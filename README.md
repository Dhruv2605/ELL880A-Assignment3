# ELL880A Assignment 3 — Vega-Lite Visualizations

**Course:** ELL880A - Visualization  
**Assignment:** 3 — Visualizing Tables using Vega-Lite  
**Data:** HW_III.xlsx (Sales Orders dataset)

## Visualizations

The `assignment3.html` file contains **7 interactive Vega-Lite visualizations**, all concatenated in a single **multiview** (`vconcat`):

| # | Chart Type | Description | Interaction |
|---|------------|-------------|-------------|
| 1 | **Donut Chart** | Total Sales by Rep | Tooltip on hover |
| 2 | **Streamgraph** | Total Sales over time, colored by Item | Tooltip on hover |
| 3 | **Trellis Histogram** | Units distribution faceted by Item | Red dashed mean overlay line |
| 4 | **Heatmap** | Total Sales by Rep × Item | Click cell to highlight Rep's row |
| 5 | **Linked Bar Charts** | Monthly sales by Region | Drag to brush a date range → filters Rep breakdown |
| 6 | **Stacked Bar Chart** | Sales by Item per Region | Click legend to filter by Region |
| 7 | **Line Chart** | Monthly sales trend per Rep | Hover a line to highlight it |

## Live Demo

👉 **[View the Visualizations](https://Dhruv2605.github.io/ELL880A-Assignment3/assignment3.html)**

## Dataset

The data (`HW_III.xlsx`) contains 43 sales order records (Jan 2021 – Dec 2022) with columns:
- **OrderDate** — Date of the order
- **Region** — East, Central, or West
- **Rep** — Sales representative name
- **Item** — Product (Binder, Desk, Pen, Pen Set, Pencil)
- **Units** — Quantity sold
- **Unit Cost** — Price per unit
- **Total** — Total sale amount

## Tech Stack

- [Vega-Lite v5](https://vega.github.io/vega-lite/)
- [Vega v5](https://vega.github.io/vega/)
- [Vega-Embed v6](https://github.com/vega/vega-embed)
