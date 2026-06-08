# Geothermal Heating & Cooling System Assessment

## Team PrecisePredictors

### Team Members

1. Chinonso Athanasius
2. Muhammed Balogun
3. Abdullahi Aadam

---

## Project Overview

This repository contains the code, analysis, and supporting documentation developed for the **SPE Africa Geothermal Datathon 2026**. The project evaluates the geothermal potential of the Rotliegend (Slochteren) Formation in the Utrecht Region of the Netherlands and proposes a hybrid geothermal heating and cooling system.

The workflow integrates well-log analysis, reservoir characterization, probabilistic resource assessment, geothermal system design, and economic evaluation to determine the technical and commercial feasibility of geothermal energy development.

---

## Problem Statement

The challenge is to identify viable geothermal reservoirs from available well data and design a sustainable heating and cooling system capable of delivering reliable thermal energy at a competitive cost.

Specifically, the project aims to:

* Evaluate geothermal resource potential from exploration well data.
* Estimate reservoir quality using petrophysical properties.
* Quantify thermal energy production under uncertainty.
* Select viable production and injection wells.
* Design a hybrid geothermal heating and cooling system.
* Assess project economics using Levelized Cost of Energy (LCOE).

---

## Methodology Summary

### 1. Data Acquisition

* LAS well log files (GR, RHOB, NPHI, RT).
* Lithostratigraphic data.
* ThermoGIS reservoir statistics.
* Well deviation/path data.
* Economic model inputs.

### 2. Petrophysical Analysis

* Gamma Ray shale-volume estimation.
* Net-to-Gross (NTG) calculation.
* Total porosity estimation from density logs.
* Effective porosity calculation.
* Permeability estimation using the Timur-Coates relationship.
* Reservoir interval identification from formation tops.

### 3. Resource Assessment

* Reservoir screening and quality evaluation.
* Heat-in-place estimation.
* Thermal power calculations.
* P90, P50, and P10 probabilistic scenarios.

### 4. Well Selection

* Evaluation of:

  * BLT-01
  * JUT-01
  * EVD-01
  * PKP-01

### 5. System Design

* Geothermal doublet configuration.
* Heat pump integration.
* Absorption chiller design.
* Thermal Energy Storage (TES).

### 6. Economic Analysis

* CAPEX and OPEX estimation.
* LCOE calculations.
* Sensitivity analysis.

---

## Repository Structure

```text
├── data/
│   ├── LAS_files/
│   ├── ThermoGIS_data/
│   └── lithology_data/
│
├── notebooks/
│   └── Team_PrecisePredictors_Code_V1.ipynb
│
├── reports/
│   └── Technical_Report.pdf
│
├── figures/
│
├── README.md
│
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Presidor/Geothermal-Heating-Cooling-System-Assessment.git
cd Geothermal-Heating-&-Cooling-System-Assessment
```

## How to Reproduce Results

### Step 1: Prepare Data

Place all LAS files and supporting datasets inside the `data/` directory.

### Step 2: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Team_PrecisePredictors_Code_V1.ipynb
```

### Step 3: Run the Notebook

Execute all cells sequentially:

```bash
Kernel → Restart & Run All
```

### Step 4: Review Outputs

The notebook generates:

* Well log visualizations.
* Petrophysical calculations.
* Reservoir screening results.
* Thermal power estimates.
* Resource ranking.
* Economic performance metrics.

### Step 5: Validate Results

Expected outcomes include:

* BLT-01 and JUT-01 identified as viable geothermal wells.
* Probabilistic resource estimates (P90/P50/P10).
* Hybrid geothermal system sizing.
* LCOE assessment and sensitivity analysis.

---

## Key Results

* Viable wells: BLT-01 and JUT-01.
* Combined geothermal resource supports district heating and cooling.
* Hybrid system design integrates:

  * Geothermal doublet
  * Heat pump
  * Absorption chiller
  * Thermal energy storage
* Competitive LCOE compared with conventional district heating systems.

---

## License

This project was developed for the SPE Africa Geothermal Datathon 2026 and is intended for academic and competition purposes.
