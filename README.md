# drifting_snow 🐧
Drifting snow and its impact on surface mass balance of the Antarctica Ice Sheet. Future climate projections. Penguins. 

Here I tried to organise some scripts that I used during my research time at Institut des Géosciences de l'Environnement (IGE) under the supervision of Charles Amory and Vincent Favier. In our research we focused on many cool (in my opinion) things such as: drifting snow (sometimes referred to as snow transport, wind-driven snow or blowing snow); melt-over-accumulation warming thresholds that we used to asses the risk exposure to hydrofracturing; surface ablation regime change under the warming climate; surface mass balance of the Antarctic Ice Sheet; and penguins.

### Script sources 
Scripts created by others are marked in the notebooks referring to the author. 

### MAR simulations
MAR v3.11 at 35 km over the AIS, run with DS scheme switched on and off. 
Forced by CNRM-CM6-1, IPSL-CM6A-LR, MPI-ESM1-2-HR and UKESM1-0-LL (under SSP5-8.5).
Outputs are Not in this repository.  

Model description and more on drifting snow: Amory et al. 2021 
https://doi.org/10.5194/gmd-14-3487-2021

### CMIP6
Near-surface air temperature and sea surface temperatures are downloaded from ESGF node 
Scenarios: SSP1-2.6, SSP2-4.5, SSP3-7.0, SSP5-8.5. 
Outputs are not in this repository.

### Drainage basins
IMBIE2 basin definitions v1.6 (`ANT_Basins_IMBIE2_v1.6`).
https://imbie.org/

### MAR grid
`MARcst-AN35km-176x148.cdf2`

## Slides
https://canva.link/g6ij53qmdaqdbpe 

## Scripts

- `plot_multiproj` — defines dictionaries, open files, and plot different time series (SMB, SU, relative ablation, surface ablation components, ablation area, runoff area, melt area, erosion area, net deposition 
- `cmip6_tos_scenario` — check tas and tos data
- `plot3_M2` — runoff–snow transport, drainage basins, masks, and elevation bins
- `statistics_M2` — statistical significance tests and spatial maps of near-surface wind speed, surface density, threshold friction velocity, surface melt, and near-surface air temperature
- `sst_anomaly` — plots time series of tas and tos for the members of CMIP6 ensemble
- `curv` — mean surface curvature, gaussian, elevation to investigate surface properties
- `plot_M2` — future anomalies, drifting snow effect, spatial maps shown in 3 different ways for all available SMB components, summary table

