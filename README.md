# CitiBike
This repo builds a customer-subscriber classfication model based on CitiBike trip data from 2018

## Installation

First, set up virtual environment and install from ```requirements.txt```:

    conda create --name <env> --file requirements.txt

Then activate your virtual envionment:
    
    conda activate <env>

## Instructions

To run the code please create a "data" directory that contains the 2018 trip data that can be downloaded [here](https://s3.amazonaws.com/tripdata/index.html)

The data can be cleaned using ```Preprocessing.ipynb```.

Visualizations from the data can be created using ```Visualization.ipynb```.

Feature can be engineered using ```Feature_construction.ipynb```.

The classfication model can be trained using ```Model_training.ipynb```. 

The notebook ```Bike_time_analysis.ipynb``` contains an analysis of trip times by means of transport.
