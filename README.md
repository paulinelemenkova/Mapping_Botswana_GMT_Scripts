# GMT Scripts — Climate Mapping of Botswana from TerraClimate Data

GMT (Generic Mapping Tools) shell scripts used to produce the figures in the peer-reviewed article by Polina Lemenkova. The scripts map climatic variables over Botswana from the TerraClimate NetCDF dataset: minimum and maximum temperature, precipitation, soil moisture, potential and actual evapotranspiration (PET/AET), downward surface shortwave radiation (SRAD), vapour pressure (VAP), vapour pressure deficit (VPD), wind speed and the Palmer Drought Severity Index (PDSI), alongside a topographic base map.

**Published in:** *ISPRS International Journal of Geo-Information* **2022**, *11*(9), 473
**DOI:** https://doi.org/10.3390/ijgi11090473
**Journal (open access):** https://www.mdpi.com/2220-9964/11/9/473
**HAL:** https://hal.science/hal-03765979
**Zenodo:** https://doi.org/10.5281/zenodo.7038295
**SSRN:** https://ssrn.com/abstract=4205689

## Contents
Shell scripts calling GMT modules for grid subsetting (grdcut), colour palettes (makecpt), raster rendering (grdimage), contouring (grdcontour), coastlines/borders and DCW country masking (pscoast, psclip), colour scales (psscale), cartographic grid and layout (psbasemap), annotations (pstext) and export (psconvert). One base topographic map (GMT-01) plus one map per climate variable (GMT-02 to GMT-12).

## LaTeX source
The LaTeX source (prose) of this article is in a separate repository: https://github.com/paulinelemenkova/gmt-terraclimate-mapping-botswana

## Citation
Lemenkova, P. Mapping Climate Parameters over the Territory of Botswana Using GMT and Gridded Surface Data from TerraClimate. *ISPRS International Journal of Geo-Information* **2022**, *11*(9), 473. https://doi.org/10.3390/ijgi11090473
