# MUSA550-Final-Noise_on_health
cleaned_code.ipynb is the code
https://jasonfan28.github.io/MUSA550-Final-Noise_on_health/
## Noise, Neighborhoods, and Health: The "Paradox of Place"

### Project Overview

This project explores the relationship between environmental noise pollution and public health outcomes (specifically depression and cholesterol) across the Northeast United States. By integrating geospatial acoustic data with CDC health indicators, this study challenges the assumption that environmental quality impacts mental and physical health in a synchronized manner.

The analysis identifies a "decoupling" of psychological perception and physiological reality, revealing that while wealthy urbanites may feel psychologically resilient to noise ("The Cosmopolitan Buffer"), their bodies suffer significant physiological stress.

### Key Findings
    The "Expectation of Quiet": High-income/education populations show the steepest increase in reported depression as noise levels rise, suggesting a lower threshold for annoyance.
    The "Cosmopolitan Buffer": Residents in dense, noisy urban cores report the lowest rates of depression (~15%) yet suffer the highest rates of high cholesterol (~36%).
    Physiological Toll: Lower-income populations show a classic Environmental Justice pattern where noise correlates strongly with high cholesterol (biomarker for stress), even if they do not report high rates of depression.

### Methodology
Data Sources:
    Noise Data: Geospatial acoustic data (US Dept. of Transportation / National Transportation Noise Map).
    Health Outcomes: CDC PLACES Data (Depression and Cholesterol prevalence).
    Demographics: US Census Bureau (ACS 5-Year Estimates).

Techniques:
    Geospatial Analysis: Processed using geopandas and rasterio to map noise exposure at the tract level.
    Machine Learning: K-Means Clustering to identify four distinct neighborhood typologies.
    Statistical Analysis: Ridge Regression and interaction effects to isolate the impact of education and income on health outcomes.

### Visualizations
1. The Disconnect: Psychological vs. Physiological Stress
  Comparison of how noise impacts depression vs. cholesterol by education level.
2. Neighborhood Typologies
  K-Means clustering showing the geographic distribution of the 4 archetypes.

### Policy Implications
This study suggests that "annoyance" is a flawed proxy for public health risk. Complaint-driven noise mitigation disproportionately prioritizes the "Quiet Elite" (who complain more but suffer less physically) while neglecting the "Vulnerable Periphery" and "Cosmopolitan Core" populations who are physically deteriorating but less likely to report distress.

### Author
Jason Fan Master of City Planning Candidate | University of Pennsylvania Focus: Climate Resilience, Equity, & Spatial Analysis

This project was completed as part of the CPLN 6920: Geospatial Data Science course at the University of Pennsylvania.
