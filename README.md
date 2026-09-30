# VVT-Sweep-Analyzer

Python-based VVT Sweep Analysis and Calibration Optimization Tool.

## 📌 Project Overview

VVT-Sweep-Analyzer is a Python-based data analysis tool developed to analyze Variable Valve Timing (VVT) sweep data from engine calibration experiments.

The tool helps analyze engine performance parameters across different engine operating conditions such as:

- Engine Speed (RPM)
- VVT Intake Position
- VVT Exhaust Position
- Engine Load / Air Charge
- Torque
- BSFC
- Combustion Stability
- Emissions

The objective is to simplify VVT sweep data analysis and support calibration engineers in identifying suitable VVT operating points.

---

## 🎯 Problem Statement

During engine calibration, VVT sweep testing is performed by varying intake and exhaust valve timing at different engine operating conditions.

A large amount of measurement data is generated during these tests. Manually analyzing this data can be time-consuming because multiple parameters need to be considered simultaneously.

The main challenges are:

- Handling large VVT sweep datasets
- Filtering data based on different operating conditions
- Analyzing multiple engine parameters simultaneously
- Understanding the relationship between VVT positions and engine performance
- Identifying suitable VVT operating regions
- Comparing performance, fuel consumption, combustion stability and emissions

The purpose of this project is to develop a Python-based analysis workflow that makes this process more structured, interactive and easier to interpret.

---

## 🔄 Analysis Workflow

```mermaid
flowchart TD

A[Engine VVT Sweep Measurement Data] --> B[Load Excel Dataset]

B --> C[Data Cleaning & Pre-processing]

C --> D[User Defined Data Filters]

D --> E[Select Parameters for Analysis]

E --> F[Interactive Scatter Plots]

F --> G[Interactive Scatter Matrix]

G --> H[Select Relevant Data Points]

H --> I[Create Selected DataFrame]

I --> J[VVT Performance Analysis]

J --> K[RSM / Response Surface Modeling]

K --> L[VVT Optimization]

L --> M[Final VVT Calibration Map]
