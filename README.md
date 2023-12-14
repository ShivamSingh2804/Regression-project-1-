# Bike Rental Prediction

## Project Overview

This project aims to predict the number of bikes rented in a given hour based on environmental and seasonal settings. The prediction model can help bike rental companies manage their resources more efficiently and meet customer demand.

## Dataset

The dataset used in this project is publicly available and contains the hourly count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.

## Features

The dataset contains the following features:
- `instant`: Record index
- `dteday` : Date
- `season` : Season (1:spring, 2:summer, 3:fall, 4:winter)
- `yr` : Year (0: 2011, 1:2012)
- `mnth` : Month (1 to 12)
- `hr` : Hour (0 to 23)
- `holiday` : Whether day is holiday or not
- `weekday` : Day of the week
- `workingday` : If day is neither weekend nor holiday
- `weathersit` : Weather situation
- `temp` : Normalized temperature in Celsius
- `atemp` : Normalized feeling temperature in Celsius
- `hum` : Normalized humidity
- `windspeed` : Normalized wind speed

## Target Variable

- `cnt` : Count of total rental bikes including both casual and registered

## Requirements

- Python 3.7+
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn

## Files

- `bike_rental.py`: Main Python script for the project
- `data.csv`: Dataset file
- `requirements.txt`: Required Python libraries


## Results

The results of the project, including model performance and insights, are discussed in detail in the `results.md` file.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgements

Thanks to Capital Bikeshare for providing the dataset.
