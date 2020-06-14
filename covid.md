**Real Time Forecasting of an Epidemic Using Discrete Time Stochastic Model: A Case Study of Pandemic Covid-19**

This work recognises the stochastic nature of the epidemic dynamics and uses the concepts of well established stochastic models like Reed-Frost model and Greenwood Model, to predict the epidemiological trend of the prevalence and incidence of COVID-2019. <br /><br />
The Algorithm described is based on a premise that a person in susceptible population can either be infected or escapes the infection with certain probability when he comes in adequate contact with an infective. This process creates a chain of infection in population. The
Algorithm-2 models this chain of infection as a binomial process, and estimates the probabilities, which can be further used to predict incidence of COVID-19.

# Results
Lets directly jump to results, since they are **exciting!!**. <br />
NOTE: The filled dots represent the data window i.e. the data used for estimating the parameters of the model. The unfilled dots represents the observed data. The black dotted line is the estimated curve, **the blue line is the 20 days ahead prediction**.

![daily_confirm](https://user-images.githubusercontent.com/65863581/84596351-cbffbf00-ae7a-11ea-84ab-7de7e7b51931.jpg)

|    Day    | Observed daily  <br />incidences of  COVID-19 in India | Prediction of  Daily <br />incidence  of COVID-19 in INDIA |
|:---------:|:------------------------------------------------:|:----------------------------------------------------:|
| 31-May-19 |                       8332                       |                         7644                         |
|  1-Jun-19 |                       8788                       |                         7923                         |
|  2-Jun-19 |                       7722                       |                         8210                         |
|  3-Jun-19 |                       8815                       |                         8507                         |
|  4-Jun-19 |                       9638                       |                         8813                         |
|  5-Jun-19 |                       9838                       |                         9129                         |
|  6-Jun-19 |                       9462                       |                         9455                         |
|  7-Jun-19 |                       10521                      |                         9791                         |
|  8-Jun-19 |                       10884                      |                         10137                        |
|  9-Jun-19 |                       8444                       |                         10495                        |
| 10-Jun-19 |                       8852                       |                         10863                        |
| 11-Jun-19 |                       11156                      |                         11243                        |
| 12-Jun-19 |                       11128                      |                         11634                        |
| 13-Jun-19 |                       11314                      |                         12038                        |
| 14-Jun-19 |                       12031                      |                         12453                        |
| 15-Jun-19 |               Lets see what happens!!            |                         12881                        |
| 16-Jun-19 |               Lets see what happens!!            |                         13323                        |
| 17-Jun-19 |               Lets see what happens!!            |                         13777                        |
| 18-Jun-19 |               Lets see what happens!!            |                         14245                        |
| 19-Jun-19 |               Lets see what happens!!            |                         14727                        |

![cum_confirm](https://user-images.githubusercontent.com/65863581/84599053-daef6d00-ae8c-11ea-9155-ef82c5e7bc52.jpg)
**Day**|**Observed Cumulative incidence**|**Predicted Cumulative incidences**
:-----:|:-----:|:-----:
8-Jun-19|257487|250900
9-Jun-19|265929|261040
10-Jun-19|274781|271530
11-Jun-19|287156|282400
12-Jun-19|298284|293640
13-Jun-19|309607|305270
14-Jun-19|321630|317310
15-Jun-19|Lets see what happens!!|329760
16-Jun-19|Lets see what happens!!|342650
17-Jun-19|Lets see what happens!!|355970
18-Jun-19|Lets see what happens!!|369750
19-Jun-19|Lets see what happens!!|383990
