# EDS 223: Homework 1 - Geospatial Analysis of Environmental Injustice in Warren County, NC


## Purpose of this Repository
This repository is for Homework 1 for EDS 223: Geospatial Analysis & Remote Sensing. It uses data from EJScreen, EPA's environmental justice screening and mapping tool, that uses Census block groups as the basic geographic unit. Because it contains data across the entire United States, it was filtered to specifically look at Warren County, NC. The goal was to build a geospatial maps in `R` using the `tmap` package to showcase the environmental injustice relationship between the percentage of POC and toxic releases to air in Warren County, NC.


## Package Dependencies
* `tidyverse`
* `sf`
* `here`
* `tmap`


## File Structure
run `tree`

```
.
├── data
│   └── ejscreen
│       ├── EJSCREEN_2023_BG_Columns.xlsx
│       ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb/
│       └── ejscreen-tech-doc-version-2-2.pdf
├── homework_1.qmd
└── README.md
```

## Data Information & Access
This analysis uses data from the EPA's previous [EJScreen: Environmental Justice Screening and Mapping Tool](https://www.epa.gov/ejscreen), accessed on October 1, 2026. The tool, when it existed, used national data to highlight places that had higher environmental burdens and vulnerable populations. 

An unofficial version of the EJScreen tool can be found [here](https://pedp-ejscreen.azurewebsites.net/).



## Authors
Author: [Karolina Sienko](https://github.com/karolinasienko)


## Citations
U.S. Environmental Protection Agency (EPA), 2023. EJScreen Technical Documentation.

United States Environmental Protection Agency. 2023 version. EJSCREEN. Retrieved: October 1, 2026.
