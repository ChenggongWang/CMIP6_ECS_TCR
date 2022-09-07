# CMIP6_ECS_TCR

Use the abrupt_4xCO2 experiment to calculate the
1. effective climate sensitivity (`EffCS`, use year 1-150) 
2. equilibrum climate senstivity (`ECS`, use year 25-150).

The method used to calculate the EffCS follows Gregory et al. (2004). Given most of the climate models have non-constant feedback, a more reasonale way to estimate the equilibrium climate senstivity is using later years (here we use year 25 and after). 

Use the 1pctCO2 experiment to calcualte the transient climate senstivity (TCR):
1. `TCR` (temperature change around year 70)
2. `TCR140` (... around year 140)

The results for different cmip6 model are listed in json file: `ECS_EffCS_TCR_TCR140.json`
