# Model calculations of the contribution of tropospheric SO2 to the stratospheric aerosol layer

## Overview:
This research project aims to quantify the amount of sulfur dioxide (SO2) entering the stratosphere during volcanically quiescent periods and its associated uncertainties. The study focuses on understanding the contribution of SO2 to the stratospheric aerosol layer, which has significant implications for stratospheric chemistry, Earth's radiative balance, and geo-engineering. 

To achieve this goal, a comprehensive modeling approach was employed using the ATLAS chemistry and transport model. The study involved numerous sensitivity runs to assess the impact of limited knowledge of the underlying processes on the results. The main source regions contributing SO2 to the stratosphere were identified, as well as the types of emissions sources at the surface, including both natural and anthropogenic sources. 

The project also aimed to compare the model results with other existing models and observational data sets, such as the POSIDON flight mission. This comparison will provide a more comprehensive understanding of the uncertainties associated with estimating stratospheric SO2 input. 

## Objectives:
- What are the source regions near the surface which contribute SO2 to the stratospheric aerosol layer?
- What is the contribution of tropospheric SO2 to the stratospheric aerosol layer?
- How do the results from the ATLAS model compare to results of other observational and model data?
- What are the uncertainties in the parameters and parameterizations of the ATLAS model?
- What is the effect of ENSO on the transport of SO2? 

## Data Used:
1. **ERA-5 ans ERA Interm Reanalysis data:**
   - Variables: Pressure, temperature, relative humidity, vertical wind velocity.
   - Spatial resolution: 0.75° x 0.75°; temporal resolution 1 hour.

2. **CAMS Reanalysis Data:**
   - Copernicus Atmosphere Monitoring Service (CAMS).
   - Spatial resolution: 0.75° x 0.75°; temporal resolution 3 hour.

## Study Region:
- 30°N – 30°S, 0°–360° E
- Tropical troposphere

**RQ1: Source Regions of SO2**

* The main source regions identified by the ATLAS model are over Eastern China, India, Southern Mexico, South East Asia, and Papa New Guinea.
* Primary anthropogenic (human-related), biogenic (natural), and degassing volcanoes contribute to SO2 emissions in these regions.
* High-density emission sources, such as factories and power plants in India and Eastern China, are significant contributors to SO2 transport.
* Cloud water plays a role in the transport of SO2, with sensitivity to its values varying between 7-23%.

**RQ2: Contribution of Tropospheric SO2**

* The ATLAS model results show that tropospheric SO2 contributes significantly to the stratospheric aerosol layer.
* Comparison with other observational and model data shows that the mass flux values are comparable to some aircraft measurements, but higher than others.
* Mixing ratios near the tropopause at 17 km are higher in the ATLAS model results compared to most other measurements.
* The differences in measurement datasets may be due to regional variability, time periods, and vertical resolution.

**RQ3: Uncertainties in Model Parameters**

* The pH value is the most sensitive parameter in the ATLAS model, with an uncertainty of 28-52% when changed by ±1 unit.
* The OH value is the second most sensitive parameter, with an uncertainty of 10-28% when changed by ±50%.
* The DMS (dimethylsulfide) value has a moderate sensitivity to changes in its values, with an uncertainty of 24-42%.
* Cloud water is the least sensitive parameter, with an uncertainty of 0-10% when changed by ±50%.

**RQ4: Effect of ENSO on SO2 Transport**

* The ATLAS model shows that ENSO events (El Niño and La Niña) affect the transport of SO2.
* During El Niño years, the main sources are Eastern China and the South China Sea, with lower SO2 burden compared to La Niña years.
* La Niña years show the highest SO2 mass flux, followed by normal years, which have a moderate increase in SO2 burden.
* ENSO events alter the sensitivity of DMS values, with the largest effect observed during El Niño years.

[Slide Deck with results](https://github.com/nalapalu/PhD_research/blob/main/Thesis_Defence_Presntaion_Chiran.pdf)

## Methodology:
- Used ATLAS Lagrangian chemistry and transport model for analysis
- Developed a numerical model in MATLAB where I developed parameterizations to improve model accuracy 
- Collected, preprocessed and explored data from diverse sources and file formats, multiple GBs large.
- Created a range of high quality visualizations using different packages
- Presented results in national and international conferences to technical and non-technical audiences.
- Collaborated with world leading scientists to produce scientific reports
  
## References:
- Nalapalu et al. (2025): Model calculations of the contribution of tropospheric SO2 to the stratospheric aerosol layer
- Wohltmann et al. (2019): A lagrangian convective transport scheme including a simulation of the time air parcels spend in updrafts 

## Authors:
Chirajeevi Nalapalu

## Contact:
For additional information or questions, please reach out to:
chiran.nalapalu@gmail.com
