# Radioactive Wildfires: Wildfire Impact on Radiation Distribution

Team research project for [NASA Space Apps Challenge 2017](https://2017.spaceappschallenge.org)

**Team: Triastsia materi**

### Project idea

Convenient information on the threat of the spread of radioactive particles due to fires in areas contaminated with radionuclides.

---

### Installation guide:
  - Install Anaconda & Jupyter notebook
  - Instal Gmaps https://github.com/pbugnion/gmaps
  - Run notebook: ```wildfire-impact-on-radiation.ipynb```

### Proposed solutions:
 - Available data that allow thread modeling:
  - soil contamination afrer Chornobyl incident
    ![Alt text](/slides/chornobyl-with-fiers.png)

  - wildfire data provided NASA (last 24h, 48h, 7days)
    - https://www.nasa.gov/press-release/battling-wildfires-from-space-nasa-adds-to-firefighters-toolkit
  - model of wildfire movement (based on wind)
  - model of wildfire creating dust (dust movement model)
  - dust movement dependence on weather
  - simplified description of algorythms:
    - detected fire spots + wind speed & direction in contaminated ared -> heat map of potentially dangerous zones (model)

- visualization solution for:
  - heat-map over Google Map API
  - heat-map of wildfire (last 24 hours)
  ![Alt text](/slides/jupyther.png)
  
  - heat-map of radiation distribution
  - heat-map of radiation + wildfire based on model model

### Improvement notes:
  - Model for forest fire & meadow fire are different!
  - Model is dynamic and depends on time for: fire, wind, humidity, temperature, type of plants, etc.


### Data & Useful information:
 - [Radiation data in Ukraine](http://chornobyl.in.ua/uk/karty-radiacia-ukraina.html)
 - [Fukushima 2011 vs Chornobyl 1986](https://allegedlyapparent.wordpress.com/2011/05/19/fukushima-2011-versus-chernobyl-1986-a-fallout-map-comparison/)
 - [Online weather conditions](https://github.com/cambecc/earth)
 - [Active fire data by NASA](https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/active-fire-data)
 - [Weather data by NOAA](http://nomads.ncep.noaa.gov/)
 - [Introduction to Fire Behavior Modeling](https://www.frames.gov/files/8413/4643/5159/Intro_to_Fire_Behavior_Modeling_Guide_2012.06.25.pdf)


### Issues to fix:
  - Warning in Jupyter: The installed widget Javascript is the wrong version.
  - Script to download latest wind flow data.
  - Improve algorythms for spoting dengarous areas.
