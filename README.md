# Covid-19

A novel approach to study COVID-19 is done by defining velocity and acceleration of disease and using them in conjunction with well known epidemic models. An universal behaviour of this disease is observed for most of the countries from the v-a graphs. Infection rate as a function of time helps the models to fit the data better in v-a plane. Akaike criterion is further used to compare among different models and find the best performing model for each country.

- Models:<br>
Class for the handling of the automatic loading of time series and lockdown dates, simulation of epidemiological models and optimization of their parameters with minimization algorithms.

- Training/ tryhard_train - original_tryhard_train:<br>
Optimization of each model wrt va and F time series.

- Data visualization:<br>
Display of v-a trajectories, effect of various parameters from the epidemiological models in the v-a trend, comparison btw different time dependencies of the infection rate.

- Models comparison:<br>
Performance of each model based on AIC value. Analysis on the effectiveness of the introduction of weights and acceleration terms.

- SIRtype comparison:<br>
Comparison btw SIR, SIAR and SEIAR.

- Basic reproductive number:<br>
Analsysis on reproductive number R0 from SIR, SIAR and SEIAR.
