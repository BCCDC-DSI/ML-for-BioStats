# Key concepts

## Models: Mathematical/ statistical vs machine learning (ML) vs Deep learning

> In a product development (PD) or project management (PM) context, we build a mathematical model (e.g., formulate an optimization problem or a DSM model) to calculate how long the PD project would take (or cost) given the various activity durations and rework probabilities. If we want to use a machine learning (ML) approach to address the same problem, we would consider available historical PD project data (e.g., number of activities, nominal activity duration, rework probabilities, etc.) and feed it into the selected ML algorithm and also tell the algorithm the project duration. Then, the ML algorithm would gradually develop the ability to predict how long the project will take given a particular set of inputs."

https://sites.aub.edu.lb/aliyassine/2020/12/16/math-models-versus-machine-learning-techniques-in-pd/

<hr>

## Taxonomy

- Mathematical / statistical models
  - regression
  - exponential growth model 
  - Auto-Regressive Integrated Moving Average 
  - GAM
  - Facebook Prophet
  - SIR Model (Susceptible, Infectious, Recovered), and its variatns:
    - SEIR (Susceptible, Exposed, Infectious, Recovered)
    - SIRF (Susceptible, Infectious, Recovered, Fatalities)
    - SIMLR (Susceptible, Infected, Machine Learning, Recovered)  
        > A basic epidemiological SIR model that is integrated with the ML approach, applied to track the changes in policies and guidelines applied by governmental authorities   

- ML models:
  - Random forest
  - Random survival forest
  - Support vector machine
  - ...
    
- Deep learning models
  - CNN
  - Transformers
    - Large-language models
    - ...

### Hybrid
- LSTM + (ARIMA) to forecast next 60 days 

References:
[Saleem et al. 2022](https://www.mdpi.com/1660-4601/19/9/5099#B35-ijerph-19-05099)


## Semi-supervised methods

[coming soon]

## Objective functions vs evaluation metrics 

- Regression: R0, R2, MAPE, MAE, MSE, and RMSE 
- ...

