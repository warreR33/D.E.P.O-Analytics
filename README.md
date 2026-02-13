# D.E.P.O Analytics — Multiplayer Game Telemetry Analysis

## Overview

**D.E.P.O Analytics** is a data analysis project focused on extracting, processing, and visualizing gameplay telemetry from an asymmetrical multiplayer game. The objective was to collect player behavior metrics and transform them into actionable insights to support game balance decisions.

This project demonstrates an end-to-end analytics workflow: raw data collection → data structuring → analysis → dashboard visualization → gameplay tuning insights.

---

## Objective

The main goal was to analyze real player actions to evaluate gameplay balance between roles and mechanics. By studying in-game metrics, the system enables identification of imbalance patterns, behavioral trends, and performance inconsistencies across matches.

---

## Data Sources

Data was exported from **Unity Cloud Analytics / Data Explorer** as CSV datasets, each representing a specific gameplay metric:

* **Average Win Ratio Ghost vs Movers** — Role win rate comparison
* **Total Players Captured by Ghost per Game** — Capture efficiency
* **Object Delivered by Players** — Delivery performance tracking
* **Total Drops of Object Before Being Delivered** — Player difficulty indicators
* **Total Rescues of Movers per Game** — Team coordination metric
* **AFK Timer of The Ghost** — Idle behavior detection
* **Total Time per Game** — Match duration distribution

---

## Data Processing

The datasets were structured and prepared for analysis using standard data preparation techniques:

* Dataset organization and consolidation
* Data validation and consistency checks
* Removal of incomplete or invalid records
* Standardization of metric formats
* Preparation for visualization tools

---

## Dashboard & Visualization

The processed data was used to build analytical dashboards displaying:

* Performance comparisons between roles
* Player behavior trends
* Match efficiency indicators
* Balance-critical metrics

Visualizations include:

* Pie charts for distribution analysis
* Line charts for trend tracking
* Bar charts for comparative metrics

These dashboards allow quick interpretation of gameplay patterns and facilitate balancing decisions.

---

## Analytical Insights Use Cases

The metrics produced by this project can be used to:

* Detect overpowered or underpowered roles
* Identify mechanics causing player friction
* Monitor engagement and inactivity behavior
* Evaluate match pacing
* Support balancing patches with real data

---

## Tools & Technologies

* Unity Analytics / Data Explorer
* CSV data processing
* Data visualization dashboards
* Spreadsheet tools for preprocessing

---

## Skills Demonstrated

Game Analytics • Data Cleaning • Data Structuring • Behavioral Analysis • Dashboard Design • KPI Interpretation • Telemetry Analysis • Balance Evaluation

---

## Project Value

This project showcases the application of data analytics within game development. Instead of relying on subjective testing alone, balancing decisions are supported by measurable player behavior and statistical evidence, enabling more accurate and scalable design improvements.
