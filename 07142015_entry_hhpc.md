# July 14, 2015

To do today: 
* Trend anaysis for mld metrics
* Use salinity and temperature to calculate density using equation of 
state. 
* Calculate 200m surface density difference over entire Southern 
Hemisphere. 
* Focus on zonally average mid-latitude and polar band and create 
stratification timeseries. 
* Trend analysis on stratification metric. 

### Mixed Layer Depth defined using mixing scheme
aredi = 400    |  aredi = 2400 
:-------------------------:|:-------------------------:
![](files/cntrl_mld_400_djf_timeseries_07082015.png)  |  ![](files/cntrl_mld_2400_djf_timeseries_07082015.png)

Mid-Latitude (30-50S)     |  Polar Region (50-70S)
:-------------------------:|:-------------------------:
![](files/cntrl_mld_mixing_midlatitude_pdf_07142015.png)  |  ![](files/cntrl_mld_mixing_polar_pdf_07142015.png)

### Mixed Layer Depth defined using sigma-t
aredi = 400    |  aredi = 2400
:-------------------------:|:-------------------------:
![](files/cntrl_mld_sigma_400_djf_timeseries_07132015.png)  |  ![](files/cntrl_mld_sigma_2400_djf_timeseries_07132015.png)

Mid-Latitude (30-50S)     |  Polar Region (50-70S)
:-------------------------:|:-------------------------:
![](files/cntrl_mld_sigma_midlatitude_pdf_07142015.png)  |  ![](files/cntrl_mld_sigma_polar_pdf_07142015.png)

## Density Stratification
* Following Capotondi et al., 2012, calculated the density stratification as the density difference between 200 m and the surface. 
* Since density is on a pressure grid in the model output, used the 210 dbar level instead of 200m. 

DJF Density stratification averaged over the last 100 years: 
![](files/cntrl_density_difference_400_djf_pcolormap_07152015.png)

![](files/cntrl_density_difference_2400_djf_pcolormap_07152015.png)

aredi = 400    |  aredi = 2400
:-------------------------:|:-------------------------:
![](files/cntrl_density_diff_400_djf_timeseries_07152015.png)  |  ![](files/cntrl_density_diff_2400_djf_timeseries_07152015.png)

Mid-Latitude (30-50S)     |  Polar Region (50-70S)
:-------------------------:|:-------------------------:
![](files/cntrl_density_diff_midlatitude_pdf_07152015.png)  |  ![](files/cntrl_density_diff_polar_pdf_07152015.png)
