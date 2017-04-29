# Radioactive Wildfires: Wildfire Impact on Radiation Distribution

Team research project for NASA Space Apps Challenge 2017

Team: Triastsia materi

Moto: 0010 1000 1100

### Project idea


MVP:
 - Map of Chornobyl
 - Visualization of radiation (static of Chornobyl)
 - Visualization of wildfire
 - Visualization of data modeled by radiation + wildfire
 - Visualization in dynamics

What we need:
 - Presentation (slides)
 - Some kind of working application
 - data
  - [+/-] radiation data (chornobyl)
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
  - heat-map of radiation
  - heat-map of radiation + wildfire based on model model

Presentation notes:
  - Model for forest fire & meadow fire are different!

Issues to fix:
  - WARNING: The installed widget Javascript is the wrong version.

Data & Useful information:
 - [Radiation data in Ukraine](http://chornobyl.in.ua/uk/karty-radiacia-ukraina.html)
 - https://allegedlyapparent.wordpress.com/2011/05/19/fukushima-2011-versus-chernobyl-1986-a-fallout-map-comparison/


 Installation guide:
  - Install Anaconda & Jupyter notebook
  - Instal Gmaps https://github.com/pbugnion/gmaps
  - Run notebook: wildfire-impact-on-radiation.ipynb
