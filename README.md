<h1 align="center">Nils Willy Tinner</h1>

<p align="center"><em>Climate scientist · Urban heat · Deep learning · Drones</em></p>

<p align="center">Bern, Switzerland</p>

<p align="center">
  <img src="https://img.shields.io/badge/MSc%20Climate%20Sciences-University%20of%20Bern-2D5C9E?style=flat-square" alt="MSc Climate Sciences"/>
  <img src="https://img.shields.io/badge/Drone%20pilot-EU%20A1%20A2%20A3-DC7F60?style=flat-square" alt="Drone pilot"/>
  <img src="https://img.shields.io/badge/Climatology%20Group-Unibe-A63848?style=flat-square" alt="Climatology Group"/>
</p>

---

## About

I'm a climate scientist from Bern, finishing an MSc in Climate Sciences at the University of Bern with a focus on urban heat and deep learning. My master thesis builds encoder–decoder neural networks that predict near-surface air temperature at 20 to 100 metre resolution across more than 800 European cities. In my day job at the Climatology Group I run sensor networks in Bern, Biel and Thun, fly thermal drones through street canyons and build web apps that turn raw measurements into something people can actually read.

I like code that runs, maps that load fast and field days that end with working sensors.

---

## Selected projects

<table>
<tr>
<td width="33%" valign="top">

### Bernometer

[![Live](https://img.shields.io/badge/live-bernometer.ch-2D5C9E?style=flat-square)](https://bernometer.ch)

Real-time temperature map of Bern. Pulls from a custom low-cost sensor network running since 2018 and interpolates with shallow machine learning. Built as a seminar project, refined on my own time and later acquired by the University of Bern. Sister platforms Thunometer and Bielometer are in the pipeline.

<sub>`R` · `Shiny` · `Land-use regression`</sub>

</td>
<td width="33%" valign="top">

### urbanmeteo

[![Live](https://img.shields.io/badge/live-urbanmeteo.com-2D5C9E?style=flat-square)](https://urbanmeteo.com)

Live urban-climate maps at 20 m resolution. Fuses Open-Meteo forecasts with thousands of Netatmo citizen weather stations and serves multi-variable overlays — temperature, humidity, wind, UHI — with a 3D terrain view. Built to make intra-urban heat legible at a glance.

<sub>`MapLibre GL` · `Open-Meteo` · `Netatmo`</sub>

</td>
<td width="33%" valign="top">

### Morlongo Forecast

[![Live](https://img.shields.io/badge/live-demo-2D5C9E?style=flat-square)](https://tinnern.github.io/morlongo-forecast/)

ML-debiased weather forecast for a single Ticino valley. Takes MeteoSwiss ICON-CH2 output, learns the local bias from a Netatmo station and corrects it. Temperature R² 0.98, humidity 0.85. Hybrid Conv1D + MLP for temperature and humidity, XGBoost with lag features for wind.

<sub>`Conv1D + MLP` · `XGBoost`</sub>

</td>
</tr>
</table>

---

## Research

<table>
<tr>
<td width="50%" valign="top">

### Master thesis

*Deep Learning Models for Pan-European Urban Air Temperature Prediction*  
University of Bern · 2025–2026 · 60 ECTS · graded 6.0

U-Net-style encoder–decoder architectures that predict hourly near-surface urban air temperature at 20 to 100 m across 800+ European cities. Compares early-, mid- and cross-attention fusion strategies for combining spatial Copernicus predictors with ERA5-Land reanalysis and quality-controlled Netatmo observations. Preliminary RMSE 1.46–1.66 K, R² 0.89–0.95 across diverse climate zones.

</td>
<td width="50%" valign="top">

### Bachelor thesis

*Diurnal Cycle of Land Surface Temperatures in Bern*  
University of Bern · 2023 · graded 6.0

A 24-hour thermal drone campaign over an urban street canyon. Flew a DJI Mavic Pro with a FLIR Vue Pro R 640, processed imagery through Agisoft Metashape and R, quantified diurnal differences between asphalt, grass, gravel and ruderal surfaces. Inputs to urban heat-island mitigation planning in the city of Bern.

</td>
</tr>
</table>

#### Publication

Burger, M., Suter, I., Anet, J., Gubler, M., **Tinner, N.**, Brönnimann, S. (2024). *Erfassung von Stadtklima-Massnahmen. Methodische Erkenntnisse aus Bern und Zürich.* Geographica Bernensia, G106.

---

## More from the repo shelf

|  |  |
|---|---|
| **Master_Thesis** — Pan-European urban temperature deep-learning pipeline. PyTorch, xarray, zarr, SLURM. | **Logger_Network_Bern** — R toolkit behind the Bern low-cost temperature logger network. QC, ingestion, plotting. |
| **netatmo-personal-weather** — Self-hosted PWA dashboard for any Netatmo station. Weekly self-training, fully automated via GitHub Actions. | **forest_drought_forecasting** — Pixel-wise forecasting of drought impact in Swiss forests from satellite, reanalysis and remote-sensing data. With the Geco group. |
| **Morlongo_Reservations** — Small reservation system for a family vacation home in Ticino. Plain JavaScript, no framework bloat. | **SaunaLorrainAuslastung** — Scraper and dashboard tracking how busy the Lorraine sauna in Bern is. Because queues are not fun. |
| **kueng-biotech** — Modern redesign of the Küng Biotech und Umwelt website. | **Bachelor_Thesis** — Thermal drone imagery and R code behind the bachelor work on LST in Bern. |
| **AGDS, AGDS 2, agds_report** — Coursework from Applied Geodata Science at Unibe. Statistical modelling, random forests, spatial ML in R. | **earthnet-minicuber, les, agds_book** — Contributions and forks around the Geco Bern teaching and data-cube stack. |

---

## Toolbox

**Languages** — Python · R · JavaScript · Bash · LaTeX  
**ML & data** — PyTorch · XGBoost · xarray · zarr · rasterio · tidyverse · terra · sf  
**Geo & field** — QGIS · ArcGIS · Agisoft Metashape · MapLibre GL · DJI thermal drones  
**Infra** — Postgres · SLURM · Linux · Git · GitHub Actions

---

## What I'm into

Urban boundary-layer processes. Thermal drone flights at three in the morning when the street is finally empty. Deep learning on sparse, messy sensor data. Palaeoecology and Alpine vegetation history. Building open, maintainable data products that outlast the project they came from. Bicycles. Mountains. Ticino.

---

## At a glance

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=tinnern&show_icons=true&count_private=true&hide_border=true&title_color=DC7F60&icon_color=5588B4&text_color=E8D8C0&bg_color=03051E" alt="GitHub stats"/>
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tinnern&layout=compact&hide_border=true&title_color=DC7F60&text_color=E8D8C0&bg_color=03051E" alt="Top languages"/>
</p>

---

## Contact

<p align="center">
  <a href="mailto:nils.tinner@unibe.ch"><img src="https://img.shields.io/badge/email-nils.tinner%40unibe.ch-2D5C9E?style=flat-square&logo=maildotru&logoColor=white" alt="Email"/></a>
  <a href="https://bernometer.ch"><img src="https://img.shields.io/badge/bernometer.ch-DC7F60?style=flat-square" alt="Bernometer"/></a>
  <a href="https://urbanmeteo.com"><img src="https://img.shields.io/badge/urbanmeteo.com-A63848?style=flat-square" alt="urbanmeteo"/></a>
</p>

<p align="center"><sub>Built with R, Python, a lot of ERA5 and the occasional thermos of coffee.</sub></p>
