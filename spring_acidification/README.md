# Spring Acidification Regression Model

## Overview
Analyzed water quality data (1991–2014) from five Florida springs — 
Chassahowitzka, Homosassa, Kings Bay, Rainbow, and Weeki Wachee — to 
identify key environmental drivers of long-term acidification trends, 
using regression modeling to quantify relationships between water 
chemistry and pH.

## Methodology
- Sourced and cleaned annual water quality data across five spring sites 
  spanning a 23-year period
- Conducted exploratory data analysis to identify candidate predictor 
  variables (carbon flux, alkalinity, temperature, site location)
- Built and validated a regression model to identify key drivers of 
  acidification
- Authored written analysis of methodology and findings
- Synthesized results into a stakeholder-ready presentation

## Results
- All five spring sites showed a consistent pH decline from 1991 to 2014
- Model achieved strong fit: R² of 0.82 on training data, 0.77 on test 
  data, with an RMSE of 0.09
- Carbon flux, alkalinity, and site location emerged as the primary 
  drivers of acidification trends
- Coastal sites showed higher alkalinity, suggesting greater buffering 
  capacity against acidification compared to inland sites
- Temperature remained stable across all sites despite rising atmospheric 
  carbon concentrations, isolating carbon flux and alkalinity (rather 
  than temperature) as the dominant chemical drivers

## Takeaways
Despite consistent temperatures across sites, rising atmospheric carbon 
was still associated with measurable long-term pH decline — driven 
primarily by shifts in carbon flux and alkalinity rather than 
temperature. Coastal springs' higher alkalinity appears to offer a 
partial buffering effect, a distinction relevant to prioritizing 
conservation and monitoring resources across inland versus coastal 
sites. One limitation: annual (rather than higher-frequency) sampling 
may smooth over shorter-term variability in these drivers.

## Tech Stack
Python · pandas · scikit-learn · Excel · PowerPoint
