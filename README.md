# Modelling Pluvial flooding at Heathrow using LISFLOOD  
For my Geography BSc dissertation, I chose to look at how imperviable surfaces affect pluvial (surface water) flood risk, using Heathrow Airport as an example (as it has lots of imperviable surfaces). Here, I used LISFLOOD and a compute cluster to run over 120 individual simulations looking at present day and future rainfall scenarios. The raster outputs from LISFLOOD were analysed using R and QGIS/ArcGIS, and are presented in the report [here](https://github.com/aeroniemi/modelling-pluvial-flooding/blob/f9d03e6b813eb2f64b2b9d1f3f5cc1c081d51a51/report.pdf).

My main findings were:
* Future (2070) extreme rainfall scenarios are quite scary (>120mm of rain in 1 hour!) although recent events have shown these to likely be on the low end of realistic
* The airport itself isn't very vulnerable to flooding due to well designed drainage (runways/taxiways are sloped slightly to allow runoff)
* Very high resolution (<1m) accurate LiDAR elevation models are very cool - in many cases you can even pick out cars on the motorway
* LISFLOOD's surface water model was not quite up to scratch - a few bugs were encountered, although we worked through them with the developers


