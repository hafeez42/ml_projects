#  Google Stock Prices Forecasting with Facebook Prophet & LSTM
In this notebook I'll perform statistical modeling and machine learning to predict the Google stock prices for the next 5 years using Facebook Prophet package. 


## Goal:

I'll try to understand the limitations of my data and answer the potential questions which might arise.
* Forecast future rate of Google stock prices for the next 5 year.

**Data:** We have daily stock closing pric from 12 years.

**Units:**  USD

## Methods:
### Statistical Models:
*   **Ignoring the time-series aspect completely, I'll model using traditional statistical modeling toolbox.** 
  *    Regression-based model.  
*   **Univariate statistical time-series modeling.**
  *    Averaging and smoothing models, ARIMA model.
*   **Slight modifications to univariate statistical time-series modeling.**
  *    External regressors, multi-variate model.
*   **Additive or component models.**
  *    Facebook Prophet package.
*   **Structural time series modeling.**
  *    Bayesian structural time series modeling, hierarchical time series modeling.

### Machine Learning Models:

*   **Ignoring the time-series aspect completely, I'll model using traditional machine learning modeling toolbox.** 
  *   Support Vector Machines (SVMs), Random Forest Regression, Gradient-Boosted Decision Trees (GBDTs), XGBoost.
*   **Hidden Markov Models (HMMs).**
*   **Other Sequence-based Models.**
*   **Gaussian Processes (GPs).**
*   **Recurrent Neural Networks (RNNs).**
