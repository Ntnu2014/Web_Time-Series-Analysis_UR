### PLEASE CHECK MY WEBPAGE 
<span style="color: #181c36; font-size: 1.8em;">**https://mfy.netlify.com**</span>

# PROJECT PROPOSAL
**PROJECT DEFINITION:** Weekly initial claims for unemployment in the US and google search data.

**OBJECTIVE:** The objective is to predict the rate of weekly initial claims for unemployment by google search keywords.

**METHODOLOGY:** For this project I used Bayesian structural time series to TOFIT THE MODEL. structural time series models WAS USED to show how Google search data can be used to improve short term forecasts of economic time series.

**DATA:** The federal reserve economic data set was obtained from economic research division of [Federal Reserve Bank of St Louis](https://fred.stlouisfed.org). 
The data consist of the weekly initial claims for unemployment insurance in the US, as reported by the US Federal Reserve. For economic decisions based on these and similar numbers, it would help to have an early forecast of the current week's number as of the close of the week. 

**ANALYSIS:** Bayesian structural time series METHOD WAS USED to fit time series models. Structural time series models are useful because they are flexible and modular.
For economic decisions based on these and similar numbers, it would help to have an early forecast of the current week's number as of the close of the week.

**METHODOLOGY:** The data was divided in to two parts (train, test). In the first model (Model 1), I tried to fit a bsts model with just the trend and seasonal components on the weekly claims without other components. Subsequently, I used to predict method to predict future the next 52 time points. 
After that, test data was used for validation of the prediction. Finally, regression components (michigan unemployment, military bah, pennsylvania unemployment, unemployment offices, unemployment filing, pay chart) were added to the model to observe whether Google search data to improve the forecast.
