# Noise sensor data (mySMARTLife)

NOTE: this project is in end-of-life phase. 
During year 2023 noise sensor data will be cleaned up and stored in CSV and Parquet formats.

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
[iot.fvh.fi/downloads/noise/](https://iot.fvh.fi/downloads/noise/)

## Sensor id and coordinates

```
     devid     |         name         |    lat    |    lon    
---------------+----------------------+-----------+-----------
 TA120-T246177 | Vasikkasaari         | 60.153438 | 25.011627
 TA120-T246182 | Korkeasaari          | 60.174305 | 24.980555
 TA120-T246189 | Korkeasaari          | 60.174305 | 24.980555
 TA120-T246184 | Mäkelänkatu          | 60.196394 | 24.952025
 TA120-T246187 | Lapinlahden sairaala | 60.168094 | 24.911846
 TA120-T246191 | Kalevankatu 39       |  60.16513 | 24.931362
```

# Getting started

You need functional Jupyter notebook Python3 environment. 
Open [Noise-sample.ipynb](Noise-sample.ipynb) within it and run it. 
Notebook should download default sample data file and show some stats
and graphs generated from the data.
