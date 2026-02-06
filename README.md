# investment-data-control-tower
End-to-end investment data workflow with reconciliation, data quality controls, and reporting using Python and SQL.
## Overview
This project demonstrates an end-to-end investment data workflow commonly found in asset management environments. It simulates data ingestion, normalization, reconciliation, and reporting across front-, middle-, and back-office systems.

The goal is to showcase business analysis, data quality, and platform support capabilities using Python and SQL.

## Problem Statement
Investment firms rely on multiple upstream systems to manage trades, positions, and cash. Discrepancies across these systems create operational risk, delayed reporting, and reconciliation breaks.

This project builds a simplified control framework to:
- Normalize investment data
- Identify and classify reconciliation breaks
- Improve transparency and data quality

## Tech Stack
- Python
- SQL
- SQLite (demo warehouse)
- GitHub Actions (CI)
- CSV-based sample data

## Repository Structure
- docs/: business context, requirements, and testing artifacts
- data/sample/: safe-to-share example data
- sql/: staging, core models, and reporting marts
- src/: ingestion, transformation, and control logic
- tests/: validation and reconciliation tests
- outputs/: example reports and dashboards

## How to Run
Instructions will be added as the pipeline is implemented.

## Status
Project scaffold created. Data ingestion, reconciliation, and reporting logic in progress.
