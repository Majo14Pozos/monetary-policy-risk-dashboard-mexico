# monetary-policy-risk-dashboard-mexico
Independent macroeconomic analytics case using public data.

## Overview
This repository presents an independent analytical case study focused on monitoring macroeconomic and financial risks relevant for monetary policy decision-making in Mexico.

The project consolidates multiple publicly available time series into a structured dashboard designed to support scenario analysis and policy interpretation.

## Data
Time series are seasonally adjusted where applicable and standardized using Z-scores to allow comparability across variables with different units.
All data used in this project comes from official public sources (Banco de México):

  - [INPC (general y subyacente) ](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?sector=8&accion=consultarCuadro&idCuadro=CP154&locale=es)
  - [IGAE (serie total desestacionalizada)](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?sector=2&accion=consultarCuadro&idCuadro=CR376&locale=es)
  - [Tasa objetivo de política monetaria](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?sector=18&accion=consultarCuadro&idCuadro=CF101&locale=es)
  - [Mediana de las expectativas de inflación general a 12 meses de las empresas](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?accion=consultarCuadro&idCuadro=CR382&locale=es)
  - [Tipos de cambio diarios (FIX)](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?sector=6&accion=consultarCuadro&idCuadro=CF102&locale=es)
  
  - [TIIE a 28 días](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?sector=18&accion=consultarCuadro&idCuadro=CF101&locale=es)
  - [Media de expectativas de la Tasa de Interés de los Bonos M a 10 años al Cierre del Año Indicado (año t)](https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?accion=consultarCuadro&idCuadro=CR189&locale=es)


## Analytical Framework
The dashboard is structured around three core pillars:

- Inflation dynamics: headline and core inflation, including short- and medium-term momentum indicators.
- Economic activity: IGAE as a proxy for the output gap and growth momentum.
- Financial conditions: exchange rate, interest rates, and yield curve signals to assess systemic stress.

## Methodology
- Data cleaning and transformation
- Seasonal adjustment and normalization
- Rolling averages and momentum indicators
- Composite interpretation through visual dashboards

## Outputs
- Risk monitoring dashboard
- Scenario-based interpretation for monetary policy decisions
- Visual tools to support structured discussion rather than point forecasts

## Disclaimer
This project was developed independently using publicly available data.
It does not represent proprietary work, confidential information, or the views of any institution.
