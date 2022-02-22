---
title: Introduction
linktitle: Introduction
type: book
date: "2019-05-05T00:00:00+01:00"
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# The objective of this analysis is to create indicators of risk from sea level rise for the whole world. 

weight: 1
---

This paper measures the risk from sea level rise at the global level. It identifies low-elevation coastal zones in every country and measures the population living in these areas.  

Our goal is to update two indicators from the World Development Indicators: 
* `AG.LND.EL5M.ZS` Land area where elevation is below 5 meters (% of total land area) 
* `EN.POP.EL5M.ZS` Population living in areas where elevation is below 5 meters (% of total population) 

A threshold of 5 meters from sea level is used as the standard, but alternate thresholds are evaluated.  

The obtained results may be previewed in the scatter plot below:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8615308"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Current inventory

The current indicators available in the World Development Indicators are:

| Indicator                                                                                                                                            |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Rural land area where elevation is below 5 meters (sq. km)](https://data.worldbank.org/indicator/AG.LND.EL5M.RU.K2)                                 |
| [Urban land area where elevation is below 5 meters (sq. km)](https://data.worldbank.org/indicator/AG.LND.EL5M.UR.K2)                                 |
| [Land area where elevation is below 5 meters (% of total land area)](https://data.worldbank.org/indicator/AG.LND.EL5M.ZS)                            |
| [Rural land area where elevation is below 5 meters (% of total land area)](https://data.worldbank.org/indicator/AG.LND.EL5M.RU.ZS)                   |
| [Urban land area where elevation is below 5 meters (% of total land area)](https://data.worldbank.org/indicator/AG.LND.EL5M.UR.ZS)                   |
| [Population living in areas where elevation is below 5 meters (% of total population)](https://data.worldbank.org/indicator/EN.POP.EL5M.ZS)          |
| [Rural population living in areas where elevation is below 5 meters (% of total population)](https://data.worldbank.org/indicator/EN.POP.EL5M.RU.ZS) |
| [Urban population living in areas where elevation is below 5 meters (% of total population)](https://data.worldbank.org/indicator/EN.POP.EL5M.UR.ZS) |

These eight indicators have recently been updated for 2015 using the Low Elevation Coastal Zone (LECZ) Urban-Rural Population and Land Area Estimates, Version 3 data set published by [CIESIN](https://sedac.ciesin.columbia.edu/data/set/lecz-urban-rural-population-land-area-estimates-v3). This study provides estimates of urban and rural populations and land areas for the years 1990, 2000, 2015 for 234 countries and statistical areas with contiguous coastal elevations of less than or equal to 5m above sea level, 5-10m above sea level, and national totals using multiple updated data sources for comparative analysis.


