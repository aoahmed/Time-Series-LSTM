# Time-Series-LSTM

## Exploratory analysis of “Individual household electric power consumption” Data Set:

The Household Power Consumption dataset is a multivariate time series dataset that describes the electricity consumption for a single household over
four years from December 2006 to November 2010. The observations were collected every minute.

The dataset includes measures about specific energy uses. The documentation identifies the following variables of interest:

- global_active_power: The total active power consumed by the
household (kilowatts).

- global_reactive_power: The total reactive power consumed by the
household (kilowatts). voltage: Average voltage (volts).

- global_intensity: Average current intensity (amps).

- sub_metering_1: Active energy for kitchen (watt-hours of active
energy).

- sub_metering_2: Active energy for laundry (watt-hours of active
energy).

- sub_metering_3: Active energy for climate control systems (watt-
hours of active energy).

the link : https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

## Modeling : 

In our case, we have used LSTM (Long short-term memory) which is an artificial recurrent neural network (RNN) architecture to predict the
household power consumption for 2 years in the future by training on the previous 2 years.

LSTM is now the state-of-the-art for sequential and time-series problems.

![Alt text](images/lstm.png?raw=true "Title")
