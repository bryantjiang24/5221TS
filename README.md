# 5221TS

## Forecasting Spatial-Temporal Climate Data-Time Series Model Analysis

Forecasting windspeed and solar radiation has become increasingly important in 
fields such as engineering and finance. In the Wind-Energy marketplace, the 
forecasted windspeed becomes highly valued information, especially to the governing 
companies who own the windmills. In short, companies must project how much 
energy output a potential buyer requires before setting up an energy deal. This could 
then lead to the windspeed futures being above or below market expectations.

In this project, we will use the dataset (WindSpeed_Month_Ave.csv), consisting
of monthly spatial-temporal observations for windspeed over the span: from January
1979 to December 2018. The training data is constructed from averaging daily 
measurements, i.e., one case is based on roughly 30 days. Averaging the cases helps to 
smooth the data and reduces the computational burden of fitting the full set of 
observations. The resulting dataset consists of n = 480 months over the timespan and 
916 positions (columns) from X1 to X916. Each case 𝑋𝑡(𝑙1, 𝑙2),𝑡 = 1,2, … ,480 is 
defined as a function of latitude (𝑙1) and longitude (𝑙2), representing the observation
domain of windspeed mainly over Mexico and surrounding states like Texas, New 
Mexico, and Oklahoma.

In this project, we are not going to evaluate the influence of longitude and 
latitude on the windspeed for each position, and we consider each position as an 
independent case. Taking position X1 as an example, we can visualize its average
windspeed for 480 months. 

This project is going to build a Time Series model that could generally fit well and 
forecast windspeed first six months ahead over all 916 positions in the dataset.
