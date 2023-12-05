
# Forecasting the energy output of a Combined Cycle Power Plant(CCPP)

Chase demand (for seasonality, forecasting the energy output, capacity management) and predicting the energy output in the future of this CCPP


## Dataset Details

[Link for info about the dataset - https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant](https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant)


## Features

Features consist of hourly average ambient variables 
- Temperature (T) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
- Net hourly electrical energy output (EP) 420.26-495.76 MW
The averages are taken from various sensors located around the plant that record the ambient variables every second. The variables are given without normalization. 


## Used Algos for Regression
- Linear Regression
- Decision Trees
- Random Forest
- SARIMAX





## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```
Create a virtualenv for your Python
```bash
    python -m venv /path/to/new/virtual/environment
-project
```
Activate your newly created venv to install the packages in requirements.txt
```
    source /path/to/new/virtual/environment
-project
```

Install dependencies

```bash
  pip install -r requirements.txt
```
