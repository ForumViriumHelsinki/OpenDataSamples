# Noise sensor data (mySMARTLife)

NOTE: this way to share open data with Jupyter notebooks 
is still looking for shape, so take this as an experiment.

NOTE: work in progress

## Briefly

[Forum Virium Helsinki](https://forumvirium.fi/) has been measuring noise levels
in Helsinki in [mySMARTLife](https://www.mysmartlife.eu/mysmartlife/) 
project using several
[CESVA TA-120](https://www.cesva.com/en/products/sensors-terminals/TA120/) noise sensors.

## Recent data

The data of last 4 months is visualised in 
[Grafana UI](https://iot.fvh.fi/grafana/d/mnWQ_DOiz/melumittarit-noise-sensors?orgId=6&refresh=30s)
which uses InfluxDB database as a data source.

## Static data sets

Data is dumped regularly to static files and current temporary place for the data is here:  
https://iot.fvh.fi/opendata/noise/

# Getting started

You need functional Jupyter notebook Python3 environment. 
Open [Noise-sample.ipynb](Noise-sample.ipynb) within it and run it. 
Notebook should download default sample data file and show some stats
and graphs generated from the data.
