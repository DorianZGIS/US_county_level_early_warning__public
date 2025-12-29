# Geosocial-Media-Early-Warning-Political-Clusters

This repository implements the main preprocessing, analysis, and evaluation steps required to reproduce the results of the study:

**Arifi, D., et al. (2025)**  
*Geosocial Media’s Early Warning Capabilities Across US County-Level Political Clusters: Observational Study*  

---

## Overview

This project investigates the **early warning capabilities of geo-social media signals** for COVID-19 case dynamics at the **U.S. county level**, with a specific focus on how these capabilities differ across **county-level political clusters**.

By combining epidemiological time series with geo-social media activity, the study examines whether and how online behavioral signals precede reported COVID-19 cases, and how these lead–lag relationships vary across politically distinct county groupings.

The repository provides:
- Preprocessed county-level COVID-19 case data
- Geo-social media signals aggregated at the county level
- Political clustering and auxiliary county metadata
- Statistical analysis and evaluation code
- Materials needed to reproduce the main figures and results reported in the paper

The focus is on **spatio-temporal early warning patterns**, **lead–lag correlations**, and **heterogeneity across political clusters**.

---

---

## Methodological Summary

- Geo-social media posts are filtered using COVID-19–related keyword sets
- Signals are aggregated at the **U.S. county level**
- Time series are smoothed, normalized, and detrended
- Counties are grouped into **political clusters** based on voting patterns
- Early warning capability is assessed using **lead–lag correlation analysis**
- Results are compared across political clusters and spatial contexts

---

## Reproducibility

All scripts are designed to reproduce the published results using the data provided in this repository.  
Where raw data cannot be redistributed due to platform, privacy, or licensing constraints, **aggregated or derived datasets** are included.

Random seeds are fixed where applicable to ensure reproducibility.

---

## Citation

If you use this repository or build upon this work, please cite:

Arifi, D., et al. (2025).  
*Geosocial Media’s Early Warning Capabilities Across US County-Level Political Clusters: Observational Study.*
doi: 10.2196/58539
---

## License

This project is licensed under the MIT License.  

---

## Contact

For questions or feedback, please contact:

**Dorian Arifi**  
Email: dorian.arifi@it-u.at


