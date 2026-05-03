# README for precip_spatial_organization repository. 

Radar-based metrics for precipitation properties and spatial organization. 

## 💡 About 

This repository contains data, scripts, and figures for Kennison, Wing, Bell, Hsiao, and Ruppert (in prep): 'Radar-observed relationships between properties of precipitation and its spatial organization in the tropical Atlantic during ORCESTRA/PICCOLO.' It contains three folders:  **(1)** Notebooks, **(2)** Figures, and **(3)** Files. Data for ORCESTRA/PICCOLO is available through IPFS. See https://browser.orcestra-campaign.org/#/?s=. 


### **📓 Notebooks 📓**

Jupyter notebooks written in Python to compute metrics and reproduce plots and analysis from Kennison et al.. 

<div style="background-color: #FADADD; padding: 15px; border: 1px solid #0d0d0d; border-radius: 3px;">
  <b>📐💧 precip_properties_geom.ipynb 💧📐</b>: Calculate precipitation properties: area mean precipitation rate (P), conditional mean precipitation rate (I), and precipitation area fraction (<i>f<sub>A</sub></i>). Identify precipitating entities and calculate basic geometries: entity number (N) and average entity area (<i>Ā</i>).
</div>

<br>
<div style="background-color: #E4E8F4; padding: 15px; border: 1px solid #0d0d0d; border-radius: 3px;">
  <b>🗂️ 🌧️ org_metrics.ipynb 🌧️ 🗂️</b>: Identify precipitating entities and compute metrics of organization to describe their spatial structure. Calculate the average edge-to-edge distance between all possible entity pairs (D̄), the Radar Organization Metric (ROME)[1], the Simple Convective Aggregation Index (SCAI)[2],  (<i>L<sub>org</sub></i>)[4], and the index of organization (<i>I<sub>org</sub></i>)[4]. 
</div>
<br>

<div style="background-color: #FFDBBB; padding: 15px; border: 1px solid #0d0d0d; border-radius: 3px;">
  <b>📈 🔎 analysis_plotting.ipynb 🔎 📈</b> Reproduce analysis and figures from Kennison et al. (in prep). 
</div>
<br>


### **📊 Figures 📊**

Figures from Kennison et al. (in prep) as .png files. 

### **📁 Files 📁**

Files (NetCDF) needed to reproduce figures and analysis. The code used to generate the data stored in the files can be found within the notebooks. 


<div style="background-color: #FAE6FA; padding: 15px; border: 1px solid #ccc; border-radius: 5px;">

<span style="color: #341539; font-size: 25px;"><b><i>📚 References 📚</i></b></span><br>

[1] Retsch MH, Jakob C, Singh M. 2020. <i>Assessing Convective Organization in Tropical Radar Observations.</i> Journal of Geophysical Research: Atmospheres 125(7), doi:10.1029/2019jd031801, URL http://dx.doi.org/10.1029/2019JD031801.<br>

[2] Tobin I, Bony S, Roca R. 2012. <i>Observational Evidence for Relationships between the Degree of Aggregation of Deep Convection, Water Vapor, Surface Fluxes, and Radiation.</i> Journal of Climate 25(20), doi:10.1175/jcli-d-11-00258.1, URL http://dx.doi.org/10.1175/JCLI-D-11-00258.1.<br>

[3] Biagioli G, Tompkins AM. 2023. <i>Measuring Convective Organization.</i> Journal of the Atmospheric Sciences 80(12), doi:10.1175/jas-d-23-0103.1, URL http://dx.doi.org/10.1175/JAS-D-23-0103.1.<br>

[4] Tompkins AM, Semie AG. 2017. <i>Organization of tropical convection in low vertical wind shears: Role of updraft entrainment.</i> Journal of Advances in Modeling Earth Systems 9(2), doi:10.1002/2016ms000802, URL http://dx.doi.org/10.1002/2016MS000802.

</div>
