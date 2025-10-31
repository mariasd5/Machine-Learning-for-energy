README FILE

This file is the readme for the Machine Learning project for the course "Machine Learning for Climate and Energy". This project is conducted by Myriam Argaud and Maria Saad.

The data is Observed monthly VRE capacity factors from 2014 to 2021, and was found at the url :
https://data.europa.eu/data/datasets/https-odre-opendatasoft-com-explore-dataset-fc-tc-nationaux-mensuels-eolien-solaire-?locale=en
It comes from the european database data.europa.eu. This file is found under the name energy_france.csv.

The chosenenergy is wind. We also downloadedclimate variables that seemed relevant to correlate with wind power. We chose
-2m temperature
-Surface pressure
-100m u-component of wind
-100m v-component of wind

It is then treated by the file read_data.ipynb to average it over the metropolitan France regions.

The objectives are to first assess the onshore wind hourly production over in metropolitan France regions using climate data and capacity factor observations.
And secondly, to predict the VRE power ahead of time.
