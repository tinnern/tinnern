<!-- Header banner with animated capsule gradient -->
<p align="center">
  <a href="https://github.com/tinnern">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,10,20,30&height=220&section=header&text=Nils%20Willy%20Tinner&fontSize=60&fontAlignY=38&fontColor=ffffff&animation=fadeIn&desc=Climate%20Scientist%20%C2%B7%20Urban%20Heat%20%C2%B7%20Deep%20Learning%20%C2%B7%20Drones&descAlignY=58&descSize=18" alt="header"/>
  </a>
</p>

<!-- Typing subtitle -->
<p align="center">
  <a href="https://github.com/tinnern">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=700&color=38BDF8&center=true&vCenter=true&width=820&lines=S%C3%A4l%C3%BC%2C+I+bi+dr+Nils+vo+B%C3%A4rn+%F0%9F%87%A8%F0%9F%87%AD;I+measure+cities+with+sensors%2C+drones+and+neural+networks;Urban+heat+islands%2C+boundary+layers%2C+the+whole+lot;Building+tools+that+make+climate+data+actually+useful" alt="typing"/>
  </a>
</p>

<!-- Profile stats row -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=tinnern&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
  <img src="https://img.shields.io/badge/Based%20in-Bern%2C%20CH-red?style=flat&logo=googlemaps&logoColor=white" alt="location"/>
  <img src="https://img.shields.io/badge/MSc%20Climate%20Sciences-University%20of%20Bern-0057A7?style=flat" alt="uni"/>
  <img src="https://img.shields.io/badge/Drone%20Pilot-EU%20A1%2FA2%2FA3-orange?style=flat&logo=dji&logoColor=white" alt="drones"/>
</p>

<br/>

## About me

I'm a climate scientist from Bern, finishing an MSc in Climate Sciences at the University of Bern with a focus on urban heat and deep learning. My master thesis builds encoder decoder neural networks that predict near surface air temperature at 20 to 100 metre resolution across more than 800 European cities. In my day job at the Climatology Group I run sensor networks in Bern, Biel and Thun, fly thermal drones through street canyons and build web apps that turn all of that raw data into something people can actually read.

I like code that runs, maps that load fast and field days that end with working sensors.

<br/>

## Flagship projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3 align="center">Bernometer</h3>
      <p align="center">
        <a href="https://bernometer.ch">
          <img src="https://img.shields.io/badge/live-bernometer.ch-E11D48?style=for-the-badge&logo=leaflet&logoColor=white" alt="bernometer"/>
        </a>
      </p>
      <p align="center">
        <img src="https://img.shields.io/badge/R-Shiny-276DC3?logo=r&logoColor=white"/>
        <img src="https://img.shields.io/badge/ML-Land%20Use%20Regression-10B981"/>
      </p>
      <p>Real time temperature map of Bern. Pulls from a custom low cost sensor network running since 2018 and interpolates with shallow machine learning. Built as a seminar project, refined on my own time and later acquired by the University of Bern. Sister platforms Thunometer and Bielometer are in the pipeline.</p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">urbanmeteo</h3>
      <p align="center">
        <a href="https://urbanmeteo.com">
          <img src="https://img.shields.io/badge/live-urbanmeteo.com-0EA5E9?style=for-the-badge&logo=cloudflare&logoColor=white" alt="urbanmeteo"/>
        </a>
      </p>
      <p align="center">
        <img src="https://img.shields.io/badge/MapLibre-GL-396CB1?logo=maplibre&logoColor=white"/>
        <img src="https://img.shields.io/badge/Open--Meteo-orange"/>
        <img src="https://img.shields.io/badge/Netatmo-009FE3"/>
      </p>
      <p>Live urban climate maps at 20 m resolution. Fuses Open Meteo forecasts with thousands of Netatmo citizen weather stations and serves multi variable overlays (temperature, humidity, wind, UHI) with a 3D terrain view. Built to make intra urban heat legible at a glance.</p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">Morlongo Forecast</h3>
      <p align="center">
        <a href="https://tinnern.github.io/morlongo-forecast/">
          <img src="https://img.shields.io/badge/live-demo-8B5CF6?style=for-the-badge&logo=githubpages&logoColor=white" alt="morlongo"/>
        </a>
      </p>
      <p align="center">
        <img src="https://img.shields.io/badge/ML-Conv1D%20%2B%20MLP-F59E0B"/>
        <img src="https://img.shields.io/badge/XGBoost-ef4444?logo=xgboost&logoColor=white"/>
      </p>
      <p>ML debiased weather forecast for a single Ticino valley. Takes MeteoSwiss ICON CH2 output, learns the local bias from a Netatmo station and corrects it. Temperature R² of 0.98, humidity 0.85. Hybrid architecture with Conv1D plus MLP for temp and humidity, XGBoost with lag features for wind.</p>
    </td>
  </tr>
</table>

<br/>

## Research

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Master thesis</h3>
      <p><em>Deep Learning Models for Pan European Urban Air Temperature Prediction</em><br/>
      University of Bern, 2025 to 2026. 60 ECTS, graded 6.0.</p>
      <p>U Net style encoder decoder architectures that predict hourly near surface urban air temperature at 20 to 100 m across 800 plus European cities. Compares early fusion, mid fusion and cross attention fusion strategies for combining spatial Copernicus predictors with ERA5 Land reanalysis and quality controlled Netatmo observations. Preliminary RMSE of 1.46 to 1.66 K, R² of 0.89 to 0.95 across diverse climate zones.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Bachelor thesis</h3>
      <p><em>Diurnal Cycle of Land Surface Temperatures in Bern</em><br/>
      University of Bern, 2023. Graded 6.0.</p>
      <p>24 hour thermal drone campaign over an urban street canyon. Flew a DJI Mavic Pro with a FLIR Vue Pro R 640, processed imagery through Agisoft Metashape and R, quantified diurnal differences between asphalt, grass, gravel and ruderal surfaces. Inputs to urban heat island mitigation planning in the city of Bern.</p>
    </td>
  </tr>
</table>

### Publication
Burger, M., Suter, I., Anet, J., Gubler, M., **Tinner, N.**, Brönnimann, S. (2024). *Erfassung von Stadtklima Massnahmen. Methodische Erkenntnisse aus Bern und Zürich.* Geographica Bernensia, G106.

<br/>

## More from the repo shelf

<table>
  <tr>
    <td valign="top"><b>netatmo personal weather</b><br/><sub>Self hosted PWA dashboard for any Netatmo station. Weekly self training. Fully automated via GitHub Actions.</sub></td>
    <td valign="top"><b>Master_Thesis</b><br/><sub>Pan European urban temperature deep learning pipeline. PyTorch, xarray, zarr, SLURM.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Logger_Network_Bern</b><br/><sub>R toolkit behind the Bern low cost temperature logger network. Quality control, ingestion, plotting.</sub></td>
    <td valign="top"><b>Morlongo_Reservations</b><br/><sub>Small reservation system for a family vacation home in Ticino. Plain JavaScript, no framework bloat.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>SaunaLorrainAuslastung</b><br/><sub>Scraper and dashboard that tracks how busy the Lorraine sauna in Bern is. Because queues are not fun.</sub></td>
    <td valign="top"><b>kueng-biotech</b><br/><sub>Modern redesign of the Küng Biotech und Umwelt website.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>forest_drought_forecasting</b><br/><sub>Pixel wise forecasting of drought impact in Swiss forests from satellite, reanalysis and remote sensing data. With the Geco group.</sub></td>
    <td valign="top"><b>Bachelor_Thesis</b><br/><sub>Thermal drone imagery and R code behind my bachelor work on the diurnal cycle of LST in Bern.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>AGDS, AGDS 2, agds_report</b><br/><sub>Coursework from Applied Geodata Science at Unibe. Statistical modelling, random forests, spatial ML in R.</sub></td>
    <td valign="top"><b>earthnet minicuber, les, agds_book</b><br/><sub>Contributions and forks around the Geco Bern teaching and data cube stack.</sub></td>
  </tr>
</table>

<br/>

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,r,js,html,css,postgres,git,github,linux,bash,latex,qgis&perline=13" alt="tools"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/xarray-013243?logo=xarray&logoColor=white"/>
  <img src="https://img.shields.io/badge/zarr-4B8BBE"/>
  <img src="https://img.shields.io/badge/rasterio-1a7f37"/>
  <img src="https://img.shields.io/badge/tidyverse-1F77B4"/>
  <img src="https://img.shields.io/badge/terra-2E8B57"/>
  <img src="https://img.shields.io/badge/sf-4B0082"/>
  <img src="https://img.shields.io/badge/SLURM-F2A900"/>
  <img src="https://img.shields.io/badge/Agisoft%20Metashape-5A5A5A"/>
  <img src="https://img.shields.io/badge/ArcGIS-0079C1"/>
  <img src="https://img.shields.io/badge/DJI-131313?logo=dji&logoColor=white"/>
</p>

<br/>

## What I'm into

Urban boundary layer processes. Thermal drone flights at 3 in the morning when the street is finally empty. Deep learning on sparse, messy sensor data. Palaeoecology and Alpine vegetation history. Building open, maintainable data products that outlast the project they came from. Bicycles. Mountains. Ticino.

<br/>

## GitHub stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=tinnern&show_icons=true&count_private=true&hide_border=true&title_color=38BDF8&icon_color=10B981&text_color=cbd5e1&bg_color=0f172a" alt="stats"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=tinnern&hide_border=true&background=0f172a&stroke=0f172a&ring=38BDF8&fire=F59E0B&currStreakLabel=38BDF8&sideLabels=cbd5e1&currStreakNum=cbd5e1&dates=94a3b8&sideNums=cbd5e1" alt="streak"/>
</p>

<p align="center">
  <img width="70%" src="https://github-readme-activity-graph.vercel.app/graph?username=tinnern&theme=react-dark&bg_color=0f172a&color=38BDF8&line=10B981&point=F59E0B&hide_border=true" alt="activity graph"/>
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tinnern&layout=compact&hide_border=true&title_color=38BDF8&text_color=cbd5e1&bg_color=0f172a" alt="langs"/>
  <img width="49%" src="https://github-profile-trophy.vercel.app/?username=tinnern&theme=nord&no-frame=true&column=4&margin-w=10" alt="trophies"/>
</p>

<br/>

## Get in touch

<p align="center">
  <a href="mailto:nils.tinner@unibe.ch">
    <img src="https://img.shields.io/badge/email-nils.tinner%40unibe.ch-0EA5E9?style=for-the-badge&logo=maildotru&logoColor=white"/>
  </a>
  <a href="https://bernometer.ch">
    <img src="https://img.shields.io/badge/bernometer.ch-E11D48?style=for-the-badge&logo=leaflet&logoColor=white"/>
  </a>
  <a href="https://urbanmeteo.com">
    <img src="https://img.shields.io/badge/urbanmeteo.com-0EA5E9?style=for-the-badge&logo=cloudflare&logoColor=white"/>
  </a>
</p>

<!-- Footer wave -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,10,20,30&height=120&section=footer&animation=fadeIn" alt="footer"/>
</p>

<p align="center"><sub>Built with R, Python, a lot of ERA5 and the occasional thermos of coffee.</sub></p>
