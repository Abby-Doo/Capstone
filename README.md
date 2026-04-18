# A Machine-Learning Framework for Predicting Blacklegged Tick Range Expansion and Disease Risk in Minnesota Under Future Climate Change Scenarios
## Environment
- Python 3.12.7 (Anaconda, Windows 64-bit)
- See 'requirements.txt' for package versions
# Installation
```bash
pip install -r requirements.txt
```

## Data Sources
- **NOAA Climate Data**: Historical county-level climate data available from NOAA Climate Data Online (https://www.ncdc.noaa.gov/cdo-web/)
- **CMIP6 Climate Projections**: Downloaded from NASA NEX-GDDP-CMIP6 dataset (https://www.nccs.nasa.gov/services/data-collections/land-based-products/nex-gddp-cmip6)
- **CDC Tick-Borne Disease Data**: Available from CDC surveillance reports, see "ManuscriptSupportingInformation.docx" Table S1
- **Tick Surveillance**: CDC blacklegged tick surveillence (2024, https://www.cdc.gov/ticks/data-research/facts-stats/blacklegged-tick-surveillance.html)
  - QGIS used to extract data from maps published by 24.	Eisen RJ, Eisen L, and Beard CB. County-scale distribution of Ixodes scapularis and Ixodes pacificus (Acari: Ixodidae) in the continental United States (doi:10.1093/jme/tjv237)
