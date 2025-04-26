> This directory contains the final project for ECE‑471: Remote Sensing, focusing on forecasting drought conditions up to 12 weeks ahead in California’s Central Valley using remote sensing data and machine learning techniques inspired by the DroughtCast framework.


## Drought Forecasting in California’s Central Valley

All code, notebooks, and metadata for our end-to-end pipeline live here. The project starts with a faithful reproduction of *DroughtCast* and grows into a region-tuned model that ingests additional Earth-observation and hydrological datasets.

### Objective  
Replicate the GRU-based sequence-to-sequence model from *DroughtCast*<sup>[1](#ref1)</sup> and enhance it with GRACE water-storage, Landsat vegetation metrics, SMAP soil-moisture, and gridMET weather fields. Our target is a weekly, 12-week-ahead drought-severity map that outperforms the baseline on spatial and temporal hold-outs, giving growers and water managers a longer-range, higher-confidence early-warning signal.


### Directory Structure

```
```


### Results


<br>

### References  

<a name="ref1" href="https://doi.org/10.3389/fdata.2021.773478">[1]</a> Brust C., Kimball J. S., Maneta M. P., Jencso K., & Reichle R. H. “DroughtCast: A Machine Learning Forecast of the United States Drought Monitor.” *Frontiers in Big Data*, 2021.  
<a name="ref2" href="https://doi.org/10.1175/2009JCLI2909.1">[2]</a> Vicente-Serrano S. M., Beguería S., & López-Moreno J. I. “A Multiscalar Drought Index Sensitive to Global Warming: The Standardized Precipitation Evapotranspiration Index.” *Journal of Climate*, 2010.  
<a name="ref3" href="https://doi.org/10.1016/j.ijforecast.2021.03.012">[3]</a> Lim B., Arık S. Ö., Loeff N., & Pfister T. “Temporal Fusion Transformers for Interpretable Multi-Horizon Time Series Forecasting.” *International Journal of Forecasting*, 2021.  
<a name="ref4" href="https://doi.org/10.1175/jhm-d-16-0182.1">[4]</a> Zhao M., Geruo A., Velicogna I., & Kimball J. S. “A Global Gridded Dataset of GRACE Drought Severity Index for 2002–14.” *Journal of Hydrometeorology*, 2017.  
<a name="ref5" href="https://doi.org/10.1016/j.agwat.2023.108692">[5]</a> Xiao X. *et al.* “Leveraging Multisource Data for Accurate Agricultural Drought Monitoring: A Hybrid Deep Learning Model.” *Agricultural Water Management*, 2024.  
<a name="ref6" href="https://doi.org/10.1016/j.scitotenv.2022.155856">[6]</a> Dikshit A., Pradhan B., Assiri M. E., & Almazroui M. “Solving Transparency in Drought Forecasting Using Attention Models.” *Science of The Total Environment*, 2022.  
<a name="ref7" href="https://doi.org/10.3390/electronics12183956">[7]</a> *A Long Short-Term Memory-Based Prototype Model for Drought Forecasting.* *Electronics*, 2023.  