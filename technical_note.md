# Technical Note
## Monetary Policy Risk Dashboard – Mexico

### Objective
This technical note documents the analytical approach, data sources,
and assumptions used to construct the monetary policy risk dashboard
for Mexico.

### Data Sources
- Inflation data (headline and core): INEGI
- Policy rate: Banco de México
- Macroeconomic indicators: public statistical sources

### Methodology
The analysis focuses on:
- Evolution of headline vs. core inflation
- Monetary policy stance and real interest rates
- Risk signals derived from inflation persistence and policy tightness

Visualizations are designed to support exploratory analysis rather than
causal inference.

### Dashboard Interpretation Guide
The dashboard should be read as a risk indicator for the February 2026 meeting:

- Moving Average Charts (Inflation): Look for the “Control Crossover.” If the 
short-term line (3 months) is below the long-term line (6 months), inflation is easing. 
If both are flat near 4%, we are in a “sideways phase” (resistance).

- Stress Monitor (Heat Map): Blue indicates loose conditions (favorable for cuts), 
while red indicates systemic stress (requires caution or a pause).

- Scatterplot (Decision Quadrants):

  - Upper Left Quadrant (Ideal Zone): Low stress and stable growth. Allows for cuts of 
  25-50 basis points.
  
  - Center Axis (Current Situation): Low stress but 0% growth. This is the “fine-tuning” 
  signal: cutting rates to prevent the economy from contracting, but with caution due to persistent inflation.

  - Real Rate vs. Neutral Zone: If the Real Rate line is above the shaded range (1.8%—3.4%), 
  the policy remains restrictive, regardless of whether the nominal rate has fallen.

### Strategic Conclusion
The dashboard suggests that, by the end of 2025, the main risk has shifted from financial 
instability (exchange rate) to economic stagnation. The tool concludes that there is technical 
room for a 25 basis point rate cut, based on the easing of financial stress and the need to relax 
monetary tightening given a lack of momentum in the IGAE (Global Indicator of Economicomic Activity).

### Limitations
- The analysis is descriptive and does not estimate causal effects.
- Results depend on publicly available macroeconomic data and revisions.

### Use Case
This project is intended as a portfolio example of applied economic
analysis and data visualization using Python and public data.
