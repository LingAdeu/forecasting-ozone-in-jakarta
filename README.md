![header](header.png)
# Long-Term Forecasting of Ozone Pollution in Jakarta: A Time Series Model Comparison

## About
Ground-level ozone is a critical air pollutant in Jakarta, frequently exceeding safe levels. It reaches 'critical status' nearly twice as often as other pollutants, posing significant public health risks, especially respiratory problems such as asthma and bronchitis. This project seeks to build a time series model to forecast ozone levels for the next year, enabling policymakers to better understand long-term trends and implement timely measures to mitigate health risks. To achieve this, I developed and compared four time series models—ARIMA, AutoARIMA, Prophet, and LSTM—trained on historical ground-level ozone data from 2010 to 2022. The models were evaluated based on forecasting accuracy using RMSE and their ability to capture long-term trends. The Prophet model yielded the best forecasting accuracy, with an RMSE of 13.05, outperforming even the more complex LSTM neural network. With more accurate forecasts, the Environmental Management Agency can better anticipate critical ozone levels, enabling them to issue early warnings, implement temporary traffic restrictions, and adjust industrial emissions regulations to protect public health

## Content
    .
    ├── README.md               <- The top-level README for using this project
    ├── data
    │   └── ispu_dki_all.csv    <- The dataset used to train and test the models
    ├── model
    │   └── final_model.pkl     <- The final model (Prophet)
    ├── notebook
    │   └── notebook.ipynb      <- The Jupyter notebook to build the models
    └── requirements.txt        <- The requirements file for reproducing the environment

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>
