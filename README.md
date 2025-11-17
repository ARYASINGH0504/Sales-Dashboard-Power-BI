# AdventureWorks — Power BI Sales & Returns Dashboard

**Author:** Arya Singh  
**Project:** Executive dashboard for AdventureWorks — Sales + Returns (2020–2022)

## Overview
This repository contains:
- Power BI report file (`pbix/AdventureWorksReport.pbix`)
- Raw lookup and fact CSVs (`data/`)
- Model diagram and documentation (`docs/`)
- DAX measures and explanations (`dax/`)

## Repo structure
(briefly list structure or link to the project root)

## How to open the report
1. Download `pbix/AdventureWorksReport.pbix` (large file — stored with Git LFS).
2. Open in Power BI Desktop (recommended version: Power BI Desktop >= Feb 2024).
3. The model diagram is in `docs/model-diagram.png`.

## Data model
Star schema with:
- Fact tables: `FactSales`, `FactReturns`
- Dimension tables: `DimDate`, `DimCustomer`, `DimProduct`, `DimSubcategory`, `DimCategory`, `DimTerritory`

## Key DAX measures
See `/dax/measures.md` for definitions: Total Sales, Return Rate, YOY Sales, Average Revenue per Customer, etc.

## How to contribute
1. Fork repo → create a feature branch `feature/xxxx` → commit → open PR.
2. For large .pbix changes, include a short summary of visuals changed in the PR description.

## Privacy & Data
This repo contains sample / anonymised data. Do not commit any PII or production secrets.

## License
[Choose a license: MIT / Apache-2.0 / etc.]. See `LICENSE`.

