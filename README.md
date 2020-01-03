# Australia Weather Analysis and Prediction

##### Author: Vincent Yeo

#### Background
Bushfires are [common](https://www.bbc.com/news/world-australia-50951043) in Australia during dry season. However, very low rainfalls can lead to disaster. Started in [November 2019](https://www.theguardian.com/australia-news/2019/nov/22/australia-bushfires-factcheck-are-this-years-fires-unprecedented), Australia has experienced a severe continent-wide bushfires that has resulted in the loss of at least 5 million hectares of land, over 2,500 buildings and 19 people. Such extreme weathers also affects the local biodiversity, the quality of the air and water and the argiculture there. Thus, weather forecasting plays a major role in Australia in predicting potential weather disaster beforehand. 

With the prediction, we can identify the next critical periods whereby the low rainfall level are likely to increase the chance of bushfires occurences happening. This can better assist government decision in allocating resources before potential weather-caused crisis can happen. 


#### Weather dataset
This is a public weather dataset adapted from:
[Ledolter, J. (May 2013). Data Mining and Business Analytics with R. US: Wiley. ISBN: 978-1-118-44714-7](https://www.wiley.com/en-sg/Data+Mining+and+Business+Analytics+with+R-p-9781118447147)

The Dataset contains a one-year weather data by Canberra's weather station from 2007-2008. Canberra is Australia's capital city at the southeast of the continent. Here is an example of the [Weather map of Canberra](https://www.meteoblue.com/en/weather-maps/canberra_australia_2172517?variable=precipitation3h_cloudcover_pressure&level=surface&lines=none&mapcenter=-35.3481N148.9110&zoom=10)


#### Tasks:
Given the variables:

+ To predict whether will it rain tomorrow.
+ To predict how much rainfall the next day.

#### Results and Analysis:

##### Classfier: 
+ Achieve an AUC of 0.75 on unseen test data

##### The regression model:
+ R-squared of 0.242 on unseen test data
+ Mean Square Error of 7.282 on unseen test data
+ RSME of 2.698 on unseen test data

#### Limitations 
+ The dataset used contains only a one-year weather dataset localised at Canberra from 2007-2008 which may not have much data for insights to the weather patterns. 
+ Data is localised to Canberrra so its not comprehensive in forecasting for the whole continent of Australia.
+ Data is only on predicting likelihood of rain and amount of rainfall. 

#### Future Works:
+ I will attempt the similar [Kaggle's 10 years weather dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) in another notebook to improve the model.

+ The classifier achieved a  AUC of 0.75 on unseen test data which can be better.

+ Subsequently, it is possible to futrher expand the model to predict likelihood bushfires, the number and location of occurrences of the bushrfires, given the historical weather and  bushfires data.


#### References:
Australian Meteorological and Oceanographic Society (AMOS)(2017, August 1). 
Statement on Weather Analysis and Prediction in Australia. Retrieved from: https://www.amos.org.au/wp-content/uploads/2018/04/AMOS-Statement-on-Weather-Analysis-and-Prediction.pdf

BBC (2020, Jan 1). Australia fires: A visual guide to the bushfires and extreme heat. Retrieved from https://www.bbc.com/news/world-australia-50951043

Bureau of Meteorology. (2015). Weather and climate forecasting for Australia. Retrieved from https://www.cawcr.gov.au/wp-content/uploads/2015/09/CAWCR_ACCESS_Brochure.pdf

Morton, A., Evershed, N. and Readfearn, Graham. (2019, Nov 22). Australia bushfires factcheck: are this year's fires unprecedented? Retreived from https://www.theguardian.com/australia-news/2019/nov/22/australia-bushfires-factcheck-are-this-years-fires-unprecedented





