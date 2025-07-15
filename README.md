# E-HDT Charging Infrastructure Visualization Dashboard

**PHASE 1: VISUALIZATION OF E-HDT COMPATIBLE EXISTING CHARGING SITES IN NORTH-SEA BALTIC CORRIDOR**

## Project Overview
This interactive dashboard provides comprehensive visualization and analysis of existing E-HDT (Electric Heavy Duty Transport) compatible charging infrastructure along the North Sea-Baltic corridor. The tool enables stakeholders to assess current charging site distribution, power capacity, and charger types across key European regions.

## Geographic Coverage
### Core Regions (Primary Focus)
- Netherlands
- Germany
- Luxembourg
- Belgium

### Expanded Coverage
- Denmark
- Norway
- Sweden
- Poland
- United Kingdom
- Baltic States (Lithuania, Latvia, Estonia)

## Technical Criteria
| Region | Minimum Power Threshold | Compatible Charger Types |
|--------|-------------------------|--------------------------|
| Netherlands, Germany | ≥100 kW | CCS (Type 2 Combo), CHAdeMO, Tesla Supercharger, Type 2 |
| All Other Regions | ≥50 kW | CCS (Type 2 Combo), CHAdeMO, Tesla Supercharger, Type 2 |

## Dashboard Features
- **Interactive Map Visualization**: Geographic distribution of charging sites
- **Country Comparison**: Charger counts, power levels, and type distribution
- **Operator Analysis**: Market share of different charging network operators
- **Access Type Breakdown**: Public vs private charging availability
- **Data Explorer**: Filterable table with detailed station information

## Data Sources
Charging station data is sourced from OpenStreetMap and processed from country-specific JSON files covering:
- Baltic_states.json
- Belgium.json
- Denmark.json
- France.json
- Germany.json
- Luxem.json (Luxembourg)
- Netherland.json
- POLAND.json
- UK.json
- Norway_sweden.json

## Technical Implementation
- Dashboard integrated at https://colab.research.google.com/drive/1rV1WJFergPW4zYVgFPRxaij3NeseNt4y?usp=sharing
---
