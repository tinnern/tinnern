<!-- ─── header wave · lipari gradient ─────────────────────────── -->
<p align="center">
  <a href="https://github.com/tinnern">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:03051E,30:19387E,60:A63848,100:DC7F60&height=240&section=header&text=Nils%20Willy%20Tinner&fontSize=58&fontAlignY=38&fontColor=E8D8C0&animation=fadeIn&desc=Climate%20scientist%20%C2%B7%20urban%20heat%20%C2%B7%20deep%20learning%20%C2%B7%20drones&descAlignY=58&descSize=18&descColor=E8D8C0" alt="header"/>
  </a>
</p>

<!-- ─── typing subtitle · lipari salmon ───────────────────────── -->
<p align="center">
  <a href="https://github.com/tinnern">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=800&color=DC7F60&center=true&vCenter=true&width=860&lines=S%C3%A4l%C3%BC%2C+I+bi+dr+Nils+vo+B%C3%A4rn;I+measure+cities+with+sensors%2C+drones+and+neural+networks;Urban+heat+islands%2C+boundary+layers%2C+the+whole+atmosphere;Building+tools+that+make+climate+data+actually+useful" alt="typing"/>
  </a>
</p>

<!-- ─── status bar · split-color badges ───────────────────────── -->
<p align="center">
  <img src="https://img.shields.io/badge/46.9480%C2%B0N-7.4474%C2%B0E-DC7F60?style=for-the-badge&labelColor=03051E" alt="coords"/>
  <img src="https://img.shields.io/badge/MSc-Climate%20Sciences%20%C2%B7%20Unibe-5588B4?style=for-the-badge&labelColor=03051E" alt="msc"/>
  <img src="https://img.shields.io/badge/Drone-EU%20A1%20%C2%B7%20A2%20%C2%B7%20A3-A63848?style=for-the-badge&labelColor=03051E&logo=dji&logoColor=E8D8C0" alt="drones"/>
  <img src="https://img.shields.io/badge/Group-Climatology%20%C2%B7%20Unibe-19387E?style=for-the-badge&labelColor=03051E" alt="group"/>
</p>


<!-- ─── thin gradient divider ─────────────────────────────────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

## About

I'm a climate scientist from Bern, finishing an MSc in Climate Sciences at the University of Bern with a focus on urban heat and deep learning. My master thesis builds encoder–decoder neural networks that predict near-surface air temperature at 20 to 100 metre resolution across more than 800 European cities. In my day job at the Climatology Group I run sensor networks in Bern, Biel and Thun, fly thermal drones through street canyons and build web apps that turn raw measurements into something people can actually read.

<!-- ─── field log · sensor-station style ──────────────────────── -->

## Field log

```text
station BERN · 46.9480°N · 7.4474°E · alt 540 m · sampling 5 min
────────────────────────────────────────────────────────────────
2026-04   thesis sprint · cross-attention fusion · ablations on UBELIX
2026-03   thunometer alpha · ingest pipeline online
2026-02   morlongo v2 · R² 0.98 · deployed
2026-01   pan-european dataset · 800+ cities cached to zarr
2025-Q4   logger network · QC v3 · sensor drift -30 %
────────────────────────────────────────────────────────────────
status    nominal · next sync in 5 min
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

## Selected projects

<table>
<tr>
<td width="33%" valign="top">

### Bernometer

<p>
  <a href="https://bernometer.ch"><img src="https://img.shields.io/badge/live-bernometer.ch-DC7F60?style=for-the-badge&logo=leaflet&logoColor=E8D8C0&labelColor=03051E" alt="bernometer"/></a>
</p>

Real-time temperature map of Bern. Pulls from a custom low-cost sensor network running since 2018 and interpolates with shallow machine learning. Built as a seminar project, refined on my own time and later acquired by the University of Bern. Sister platforms Thunometer and Bielometer in the pipeline.

<p>
  <img src="https://img.shields.io/badge/-R%20%C2%B7%20Shiny-5588B4?style=flat-square&labelColor=03051E" alt="r"/>
  <img src="https://img.shields.io/badge/-LUR%20ML-A63848?style=flat-square&labelColor=03051E" alt="lur"/>
</p>

</td>
<td width="33%" valign="top">

### urbanmeteo

<p>
  <a href="https://urbanmeteo.com"><img src="https://img.shields.io/badge/live-urbanmeteo.com-DC7F60?style=for-the-badge&logo=cloudflare&logoColor=E8D8C0&labelColor=03051E" alt="urbanmeteo"/></a>
</p>

Live urban-climate maps at 20 m resolution. Fuses Open-Meteo forecasts with thousands of Netatmo citizen weather stations and serves multi-variable overlays — temperature, humidity, wind, UHI — with a 3D terrain view. Built to make intra-urban heat legible at a glance.

<p>
  <img src="https://img.shields.io/badge/-MapLibre%20GL-5588B4?style=flat-square&labelColor=03051E" alt="maplibre"/>
  <img src="https://img.shields.io/badge/-Open--Meteo-A63848?style=flat-square&labelColor=03051E" alt="openmeteo"/>
  <img src="https://img.shields.io/badge/-Netatmo-19387E?style=flat-square&labelColor=03051E" alt="netatmo"/>
</p>

</td>
<td width="33%" valign="top">

### Morlongo Forecast

<p>
  <a href="https://tinnern.github.io/morlongo-forecast/"><img src="https://img.shields.io/badge/live-demo-DC7F60?style=for-the-badge&logo=githubpages&logoColor=E8D8C0&labelColor=03051E" alt="morlongo"/></a>
</p>

ML-debiased weather forecast for a single Ticino valley. Takes MeteoSwiss ICON-CH2 output, learns the local bias from a Netatmo station and corrects it. Temperature R² 0.98, humidity 0.85. Hybrid Conv1D + MLP for temp and humidity, XGBoost with lag features for wind.

<p>
  <img src="https://img.shields.io/badge/-Conv1D%20%2B%20MLP-5588B4?style=flat-square&labelColor=03051E" alt="conv1d"/>
  <img src="https://img.shields.io/badge/-XGBoost-A63848?style=flat-square&labelColor=03051E" alt="xgboost"/>
</p>

</td>
</tr>
</table>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

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

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

## More from the repo shelf

|  |  |
|---|---|
| **Master_Thesis** — Pan-European urban temperature deep-learning pipeline. PyTorch, xarray, zarr, SLURM. | **Logger_Network_Bern** — R toolkit behind the Bern low-cost temperature logger network. QC, ingestion, plotting. |
| **netatmo-personal-weather** — Self-hosted PWA dashboard for any Netatmo station. Weekly self-training, fully automated via GitHub Actions. | **forest_drought_forecasting** — Pixel-wise forecasting of drought impact in Swiss forests. With the Geco group. |
| **Morlongo_Reservations** — Small reservation system for a family vacation home in Ticino. Plain JavaScript, no framework bloat. | **SaunaLorrainAuslastung** — Scraper and dashboard tracking how busy the Lorraine sauna in Bern is. |
| **kueng-biotech** — Modern redesign of the Küng Biotech und Umwelt website. | **Bachelor_Thesis** — Thermal drone imagery and R code behind the bachelor work on LST in Bern. |
| **AGDS, AGDS 2, agds_report** — Coursework from Applied Geodata Science at Unibe. | **earthnet-minicuber, les, agds_book** — Contributions and forks around the Geco Bern teaching and data-cube stack. |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,r,js,html,css,postgres,git,github,linux,bash,latex,qgis&perline=13&theme=dark" alt="tools"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-xarray-DC7F60?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-zarr-5588B4?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-rasterio-A63848?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-tidyverse-19387E?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-terra-DC7F60?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-sf-5588B4?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-SLURM-A63848?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-Agisoft%20Metashape-19387E?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-ArcGIS-DC7F60?style=flat-square&labelColor=03051E"/>
  <img src="https://img.shields.io/badge/-DJI-5588B4?style=flat-square&labelColor=03051E&logo=dji&logoColor=E8D8C0"/>
</p>

## What I'm into

Urban boundary-layer processes. Thermal drone flights at three in the morning when the street is finally empty. Deep learning on sparse, messy sensor data. Palaeoecology and Alpine vegetation history. Building open, maintainable data products that outlast the project they came from. Bicycles. Mountains. Ticino.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

## At a glance

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=tinnern&show_icons=true&count_private=true&hide_border=true&title_color=DC7F60&icon_color=5588B4&text_color=E8D8C0&bg_color=03051E" alt="stats"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tinnern&layout=compact&hide_border=true&title_color=DC7F60&text_color=E8D8C0&bg_color=03051E" alt="languages"/>
</p>

<p align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=tinnern&bg_color=03051E&color=DC7F60&line=DC7F60&point=A63848&area=true&area_color=A63848&title_color=E8D8C0&hide_border=true" alt="activity graph"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:03051E,50:A63848,100:DC7F60&height=2" alt=""/>
</p>

## Get in touch

<p align="center">
  <a href="mailto:nils.tinner@unibe.ch"><img src="https://img.shields.io/badge/email-nils.tinner%40unibe.ch-DC7F60?style=for-the-badge&logo=maildotru&logoColor=E8D8C0&labelColor=03051E" alt="email"/></a>
  <a href="https://bernometer.ch"><img src="https://img.shields.io/badge/web-bernometer.ch-A63848?style=for-the-badge&logo=leaflet&logoColor=E8D8C0&labelColor=03051E" alt="bernometer"/></a>
  <a href="https://urbanmeteo.com"><img src="https://img.shields.io/badge/web-urbanmeteo.com-19387E?style=for-the-badge&logo=cloudflare&logoColor=E8D8C0&labelColor=03051E" alt="urbanmeteo"/></a>
</p>

<!-- ─── footer wave · lipari reversed ─────────────────────────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:DC7F60,40:A63848,70:19387E,100:03051E&height=140&section=footer&animation=fadeIn" alt="footer"/>
</p>

<p align="center"><sub>Built with R, Python, a lot of ERA5 and the occasional thermos of coffee.</sub></p>
