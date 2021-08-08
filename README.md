# Proptech Data Vizualization (module_6_challenge)

A Jupyter notebook that vizualizes San Francisco housing data from 2010 to 2016 by neighborhood.

The data sets used in this notebook can be found in the [`Resources`](Resources/) folder:

- [sfo_neighborhoods_census_data.csv](Resources/sfo_neighborhoods_census_data.csv) - contains the sales price per square foot, gross rents, and housing supply data for San Francisco neighborhoods between 2010 and 2016
- [neighborhoods_coordinates.csv](Resources/neighborhoods_coordinates.csv) - contains Latitude and Longitude coordinates for San Francisco neighborhoods.

This notebook uses the Mapbox API to plot data onto a map. To run the notebook, first create a [Mapbox](https://www.mapbox.com/) account and create a .env file with your `MAPBOX_API_ACCESS_TOKEN`. Use the [sample.env](sample.env) file as a reference.

---

## Technologies

- python 3.7.10
- jupyterlab 3.0.14
- pandas 1.2.4
- python-dotenv 0.18.0
- hvplot 0.7.3
- plotly 4.13.0


---

## Contributors

[![](https://github.com/woodedlawn.png?size=50)](https://github.com/woodedlawn)

---

## License

GNU GPLv3
