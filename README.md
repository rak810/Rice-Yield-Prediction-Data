# Rice-Yield-Prediction-Data

*Contains necessary data required for a machine learning project*

```
Rice-Yield-Prediction-Data
├── cleaned
├── pickles
└── raw
     ├── rice production
     └── weather                    
```
Here **raw/** folder contains data that are unprocessed. **rice production/** folder contains of rice production data of each district of Bangladesh for each year from 2010 to 2018.
These data was collected from [here](http://www.bbs.gov.bd/site/page/3e838eb6-30a2-4709-be85-40484b0c16c6/%E0%A6%95%E0%A7%83%E0%A6%B7%E0%A6%BF-%E0%A6%AA%E0%A6%B0%E0%A6%BF%E0%A6%B8%E0%A6%82%E0%A6%96%E0%A7%8D%E0%A6%AF%E0%A6%BE%E0%A6%A8-%E0%A6%AC%E0%A6%B0%E0%A7%8D%E0%A6%B7%E0%A6%97%E0%A7%8D%E0%A6%B0%E0%A6%A8%E0%A7%8D%E0%A6%A5). **weather/** folder contain weather data from 35 weather stations in bangladesh spanning 65 years. This data is taken from [Kaggle](https://www.kaggle.com/emonreza/65-years-of-weather-data-bangladesh-preprocessed). Also the same folder contains Normalized Difference Vegetation Index [(NDVI)](https://en.wikipedia.org/wiki/Normalized_difference_vegetation_index) data which was collected from [Google Earth Engine](https://earthengine.google.com/).

**cleaned/** folder contains the processed data that were used for the projects. And the **pickles/** folder contains the pickled model created using these data.

