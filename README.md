# MODFLOW 6 Transport Test Models
This repository provides a controlled environment for building and evaluating MODFLOW 6 groundwater transport (GWT) models. It supports testing of multi‑layer hydrostratigraphic configurations, transport behavior, and scenario analysis relevant to contaminant migration and mine‑related groundwater systems.

# Purpose
To develop, run, and analyze reproducible transport test cases using MODFLOW 6, with a focus on:

Multi‑layer transport behavior

Advection–dispersion processes

Boundary‑condition sensitivity

Scenario benchmarking and diagnostics

# Features
MODFLOW 6 GWT test models

Automated model‑building scripts using FloPy

Structured data folders for raw, processed, and GIS‑ready inputs

Jupyter notebooks for visualization and analysis

Documentation of model setup, assumptions, and layer configurations

# Structure

```
modeltransport/
├── models/        # Transport model runs and scenarios
├── scripts/       # FloPy build/run utilities
├── data/          # Raw and processed inputs
├── notebooks/     # Analysis and visualization
└── docs/          # Model descriptions and notes
```

