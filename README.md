# Cab-Booking-System
Mid Term Project

# Objective 
In this repository we are trying to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city. 

# Dataset
We are provided with hourly renting data span of two years. Data is randomly divided into train and test set. WE need to predict the total count of cabs booked in each hour covered by the testset, using the information available prior to the booking period.
**Description of the data**
* datetime-hourly date +timestamp 
* season-spring, summer, autumn, winter
* holiday-whether the day is considered a holiday
* workingday-whether the day is neither a weekend nor holiday
* weather-Clear , Cloudy,  Light Rain, Heavy 
* temp-temperature in Celsius
* atemp-"feels like" temperature in Celsius
* humidity-relative humidity
* windspeed-wind speed
* Total_booking-number of total booking

# What are we trying to achieve?
* Visualize data using different visualizations to generate interesting insights.
* Outlier Analysis
* Missing value analysis
* Visualizing Total_booking Vs other features to generate insights
* Correlation Analysis
* Feature Engineering
* Grid search
* Regression Analysis
* Ensemble Model


#### Launching Jupyter Locally

All demos in the project may be run directly in your browser without installing Jupyter locally. But if you want to launch [Jupyter Notebook](http://jupyter.org/) locally you may do it by running the following command from the root folder of the project:

```bash
jupyter notebook
```
After this Jupyter Notebook will be accessible by `http://localhost:8888`.

#### Launching Jupyter Remotely

Each algorithm section contains demo links to [Jupyter NBViewer](http://nbviewer.jupyter.org/). This is fast online previewer for Jupyter notebooks where you may see demo code, charts and data right in your browser without installing anything locally. In case if you want to _change_ the code and _experiment_ with demo notebook you need to launch the notebook in [Binder](https://mybinder.org/). You may do it by simply clicking the _"Execute on Binder"_ link in top right corner of the NBViewer.

![](./images/binder-button-place.png)

## Datasets

The list of datasets that is being used for Jupyter Notebook demos may be found as train.csv,test.csv,train_label.csv,test_label.csv.
