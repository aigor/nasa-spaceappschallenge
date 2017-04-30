# Radioactive Wildfires: Wildfire Impact on Radiation Distribution

Team research project for [NASA Space Apps Challenge 2017](https://2017.spaceappschallenge.org)

**Team: Triastsia materi**

### Project idea

Convenient information on the threat of the spread of radioactive particles due to fires in areas contaminated with radionuclides.
---

Needed solutions:
 - data
  - [+/-] radiation data (chornobyl)
    ![alt text](https://raw.githubusercontent.com/aigor/nasa-spaceappschallenge/slides/chornobyl-with-fiers.png)

  - [+] wildfire data (historical)
    - https://www.nasa.gov/press-release/battling-wildfires-from-space-nasa-adds-to-firefighters-toolkit
  - model of wildfire movement (based on wind)
  - model of wildfire creating dust (dust movement model)
  - dust movement dependence on weather
  - algorythms:
    - radiation-data + fire + wind -> heat map (model)

- visualization solution for:
  - [+] heat-map over map
  - [+] heat-map of wildfire (last 24 hours)
  ![alt text](https://raw.githubusercontent.com/aigor/nasa-spaceappschallenge/slides/jupyther.png)
  
  - heat-map of radiation
  - heat-map of radiation + wildfire based on model model

Improvement notes:
  - Model for forest fire & meadow fire are different!
  - Model is dynamic and depends on time for: fire, wind, humidity, temperature, type of plants, etc.

Issues to fix:
  - Warning in Jupyter: The installed widget Javascript is the wrong version.
  - Script to download latest wildfire data.

Data & Useful information:
 - [Radiation data in Ukraine](http://chornobyl.in.ua/uk/karty-radiacia-ukraina.html)
 - https://allegedlyapparent.wordpress.com/2011/05/19/fukushima-2011-versus-chernobyl-1986-a-fallout-map-comparison/


 Installation guide:
  - Install Anaconda & Jupyter notebook
  - Instal Gmaps https://github.com/pbugnion/gmaps
  - Run notebook: ```wildfire-impact-on-radiation.ipynb```
