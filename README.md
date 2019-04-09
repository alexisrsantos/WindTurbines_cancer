# Cancer Rates are not associated with Wind Energy in the U.S.
Here I provide the data and code to conduct a state-level correlation analysis between Wind Energy indicators and Cancer (Indicence, Prevalence, Mortality).

# Results
Here I provide a visualization of the correlation analysis. 

#Incidence 
![Incidence](Rplot11.png)

## Prevalence Rate
![Prevalence](Rplot10.png)

## Death Rates
![Death Rates](Rplot09.png)

The code includes an section for an analysis that excludes Texas (an outlier). 

# Conclusion 
There is no correlation between Wind Energy indicators and any of the state-level. 

# Future directions
Numerous limitations need to be addressed this is a state-level analysis. Future analyses could study whether this association exists at the county level, or if the association/correlation exists with individual data and distance to the turbines. 

## Data Sources

Data for Incidence, Prevalence, and Mortality come from the **State Cancer Profiles**[https://statecancerprofiles.cancer.gov/].
Data for Wind Energy Indicators come from the **American Wind Energy Association**[https://www.awea.org/].

## Software
All analyses and visualization can be run with [R](https://www.r-project.org/). R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and MacOS.
