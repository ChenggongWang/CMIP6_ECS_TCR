# CMIP6_ECS_TCR

Use the abrupt_4xCO2 experiment to calculate the
1. effective climate sensitivity (`EffCS`, use year 1-150) 
2. equilibrium climate sensitivity (`ECS`, use year 25-150).

The method used to calculate the EffCS follows Gregory et al. (2004). Given most of the climate models have non-constant feedback, a more reasonable way to estimate the equilibrium climate sensitivity is using later years (here we use year 25 and after). 

Use the 1pctCO2 experiment to calculate the transient climate sensitivity (TCR):
1. `TCR` (temperature change around year 70)
2. `TCR140` (... around year 140)

The results for different cmip6 models are listed in JSON file: `ECS_EffCS_TCR_TCR140.json`

See CMIP5 and detailed feedback values at Mark Zelinka's Github repo [`cmip56_forcing_feedback_ecs`](https://github.com/mzelinka/cmip56_forcing_feedback_ecs)

# NOTE on detrend
using 200-year piControl run to detrend all variables for each model

`L1` only detrend significant regions


`L2`  detrend all regions

