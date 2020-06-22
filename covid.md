[BACK TO MAIN PAGE](README.md)<br />
**Real Time Forecasting of an Epidemic Using Discrete Time Stochastic Model: A Case Study of Pandemic Covid-19**

This work recognises the stochastic nature of the epidemic dynamics and uses the concepts of well established stochastic models like Reed-Frost model and Greenwood Model, to predict the epidemiological trend of the prevalence and incidence of COVID-2019. <br /><br />
The Algorithm used is based on a premise that a person in susceptible population can either be infected or escapes the infection with certain probability when he comes in adequate contact with an infective. This process creates a chain of infection in population. The
Algorithm-2 models this chain of infection as a binomial process, and estimates the probabilities, which can be further used to predict incidence of COVID-19.

# Results
**Lets directly jump to results, since they are **exciting!!, I will upload the abridged report of the implemented algorithm in a shortwhile.**<br />
NOTE: The filled dots represent the data window i.e. the data used for estimating the parameters of the model. The unfilled dots represents the observed data. The black dotted line is the estimated curve, **the blue line is the 20 days ahead prediction**.

![daily_confirm](https://user-images.githubusercontent.com/65863581/84596351-cbffbf00-ae7a-11ea-84ab-7de7e7b51931.jpg)

|    Day    | Observed daily  <br />incidences of  COVID-19 in India | Prediction of  Daily <br />incidence  of COVID-19 in INDIA |
|:---------:|:------------------------------------------------:|:----------------------------------------------------:|
| 13-Jun-20 |                       11314                      |                         12038                        |
| 14-Jun-20 |                       12031                      |                         12453                        |
| 15-Jun-20 |                       10014                      |                         12881                        |
| 16-Jun-20 |                       11090                      |                         13323                        |
| 17-Jun-20 |                       13107                      |                         13777                        |
| 18-Jun-20 |                       13826                      |                         14245                        |
| 19-Jun-20 |                       14740                      |                         14727                        |
| 20-Jun-20 |                       15898                      |                         14510                        |
| 21-Jun-21 |                       15158                      |                         14727                        |
| 22-Jun-21 |                       !!                         |                         15330                        |
| 23-Jun-21 |                       !!                         |                         15750                        |
| 24-Jun-21 |                       !!                         |                         16180                        |
| 25-Jun-21 |                       !!                         |                         16620                        |
| 26-Jun-21 |                       !!                         |                         17530                        |




