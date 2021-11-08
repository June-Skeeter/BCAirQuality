This repository contains a script that downloads and aggregates hourly air quality data from DataBC.

The dataset includes: "O3" and "PM25" which are both harmful pollutants.  Data are aggregated by month (Timeseries) over 2009-2020.  This could be at specific event/fire season.  Data are also aggregated by year (Yearly_Averages) which could be used for looking at trend. Not all years/months are available at all stations.  The script has included all stations that have >50% data coverage.  It's up to you to decide how to handle missing data beyond that.

This repo also includes MonitoringStations.csv, a text file with the coordinates of each station.  The "EMS_ID" column is the index that matches the stations to the data.

For metadata see: https://catalogue.data.gov.bc.ca/dataset/air-quality-monitoring-verified-hourly-data


