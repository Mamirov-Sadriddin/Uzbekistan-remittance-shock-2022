# Replication: Remittance Shocks and Household Welfare in Uzbekistan  

This repository contains the replication code for the Master's thesis  
*Remittance Shocks and Household Welfare in Uzbekistan: Evidence from the 2022 Russia Crisis*.

## Data

The code uses the **Listening to Citizens of Uzbekistan (L2CU)** panel, waves 1–82  
(September 2018 – June 2025).

You can obtain the raw `.sav` files from the World Bank Microdata Library:  
[https://microdata.worldbank.org](https://microdata.worldbank.org)

Place the following two files in `~/Downloads/` (or adjust the `PATH` variable in the script):

- `l2cu_cati_individual_data_82.sav`
- `l2cu_cati_household_data_82.sav`

## Requirements

- R (≥ 4.0)
- Packages: `haven`, `dplyr`, `fixest`

Install them with:

```r
install.packages(c("haven", "dplyr", "fixest"))
