# FireMind
A Neural Network for Modeling Wildfire

FireMind uses keras to model wildfire growth using historical data, fire perimeters taken at 24 hr intervals, combined with topographic data from LANDSAT images and weather data from a federal database.  This data sources are cleaned to fire progress tensors, identical arrays of 256x256 30m 'pixels', which are used to train a complex neural network.