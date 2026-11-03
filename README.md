# Indian-Catchment-Flood-Risk-Priority-Index
Flood risk assessment and prioritisation across Indian catchments using data analytics and geospatial methods

## Project Overview

This project develops a catchment-level flood risk priority index for India using flood events, rainfall variables, catchment characteristics and gauge metadata.

The objective is to identify and prioritise Indian catchments based on their historical flood hazard, exposure and vulnerability.

## Data Sources

The analysis uses the INDOFLOODS dataset:

- Kuntla & Saharia (2025)
- [INDOFLOODS – Zenodo](https://doi.org/10.5281/zenodo.14584654)

Required datasets:
- Flood events
- Precipitation variables
- Catchment characteristics
- Gauge metadata
- Catchment shapefiles

## Methodology

The project follows these stages:

1. Data cleaning and quality checks.
2. Exploratory data analysis.
3. Construction of catchment-level flood hazard indicators.
4. Integration of hazard, exposure and vulnerability indicators.
5. Development of a composite risk-priority index.
6. Hazard-versus-exposure quadrant analysis.
7. K-means clustering for catchment typology.
8. Alternative ranking and sensitivity analysis.
9. Monte Carlo simulation to assess ranking stability.
10. Geospatial visualisation and mapping.

## Risk-Priority Index

The composite index uses the geometric mean of hazard and exposure scores:

Rᵢ = √(Hᵢ × Eᵢ)

Where:
- Hᵢ = Hazard score
- Eᵢ = Exposure score

## Technologies Used

- Python
- Pandas and NumPy
- GeoPandas
- Scikit-learn
- Matplotlib and Seaborn

## Outputs

The analysis is designed to produce:

- Catchment-level flood risk rankings.
- Hazard and exposure classifications.
- Catchment typologies.
- Sensitivity analysis results.
- Monte Carlo simulation results.
- Static and interactive maps of India.

## Limitations

The index is based on available historical flood records and catchment-level indicators. The Monte Carlo simulation assesses the stability of priorities under simulated futures; it should not be interpreted as a deterministic flood forecast.

District-level DFSI comparisons are contextual rather than direct validation because district and catchment boundaries differ.
