# Natural Ventilation Potential- Predicting Passive Thermal Comfort Potential for Indian Buildings

**MATLAB · Building Thermal Analysis · ASHRAE Comfort Models · Weather Data · Energy Analysis**


## Overview
How much of a building’s cooling demand can be reduced simply by using natural ventilation?

This project developed a MATLAB-based computational tool to evaluate the Natural Ventilation Potential (NVP) of buildings across different Indian climatic conditions. The objective was to identify the hours during which outdoor conditions could provide acceptable indoor thermal comfort without relying on active thermal energy strategies.
The tool combines building characteristics, local weather conditions, and thermal comfort criteria to estimate the passive thermal capability of a building.
Rather than treating natural ventilation as a qualitative design strategy, the project turned it into a quantifiable, location-dependent metric that can support early-stage building and climate-responsive design decisions.

---

## My role
I developed the computational framework for predicting Natural Ventilation Potential and was responsible for:
- Developing the MATLAB-based NVP prediction tool from the underlying thermal and comfort models.
- Implementing ASHRAE thermal comfort criteria to determine acceptable indoor conditions.
- Integrating hourly meteorological data with building and environmental parameters.
- Developing the thermal calculations required to estimate indoor temperature response under passive conditions.
- Accounting for parameters such as building characteristics, outdoor temperature, solar radiation, and wind conditions.
- Processing and analysing weather data for 34 Indian cities representing different climatic conditions.
- Designing the computational workflow so that users could modify building and location parameters and evaluate the resulting passive cooling potential.
- Post-processing the results to identify periods where natural ventilation could maintain thermally acceptable conditions.

  ---

## Methodology
The workflow was designed around four major inputs:

Location & Weather → Building Parameters → Thermal Comfort Model → NVP Prediction

01 — Weather Data
Hourly meteorological data was used to characterize the external environment, including parameters such as:
Outdoor temperature
Solar radiation
Wind velocity
Wind direction

02 — Building Characteristics
The model incorporates building-specific information to represent the thermal response of the building under naturally ventilated conditions.

03 — Thermal Comfort
ASHRAE-based comfort models were incorporated to determine whether the predicted indoor conditions fall within an acceptable thermal comfort range.

04 — NVP Calculation
For every time step, the model evaluates whether passive ventilation can provide acceptable thermal conditions.

The resulting analysis identifies the potential number and distribution of naturally ventilated hours, allowing different buildings and locations to be compared.

---

## Results and Impact

The developed tool provided a systematic way to evaluate the passive thermal capability of buildings under different Indian climatic conditions.
The analysis demonstrated that Natural Ventilation Potential is strongly dependent on:
Climate and location
Outdoor temperature variation
Solar gains
Wind availability
Building thermal characteristics
Thermal comfort requirements

The project connects building physics, environmental data, and thermal comfort modelling into a practical computational tool.

The framework can support:

Climate-responsive design
Identify locations and periods where passive ventilation strategies are most effective.

Early-stage building design
Evaluate passive cooling potential before committing to extensive mechanical systems.

Energy-efficiency analysis
Estimate opportunities for reducing dependence on conventional air conditioning.

Climate comparison
Compare natural ventilation potential across different Indian climatic regions.

---

## Technical Stack

- MATLAB — Numerical modelling, computational framework & data processing
- ASHRAE Comfort Models — Thermal comfort evaluation
- Meteorological Data — Hourly environmental conditions
- Thermal Modelling — Building temperature and passive response analysis
- Data Visualization — Temporal and location-based NVP analysis

  ---

## Project Takeaway

This project transformed Natural Ventilation Potential from a qualitative concept into a data-driven engineering metric, providing a computational approach to evaluate when and where buildings can exploit outdoor conditions for passive thermal comfort.
