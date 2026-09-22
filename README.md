# Hospital BI Dashboard

A professional reference architecture for hospital Business Intelligence using synthetic healthcare data.

## Goals

- Executive hospital overview
- Operational monitoring
- Clinical and financial KPIs
- Trend analysis
- Department performance
- Data quality monitoring

## Architecture

Source Systems → Staging → Data Warehouse → Semantic Model → BI Dashboard

## Structure

- `docs/` — architecture and KPI definitions
- `sql/` — source and warehouse SQL
- `data/` — synthetic datasets
- `data-model/` — dimensional model
- `kpi/` — KPI definitions
- `dashboard/` — dashboard design and implementation

## Important

No real patient, hospital or production data is published.