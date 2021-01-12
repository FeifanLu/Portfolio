# Portfolio
A repository of the projects I worked on or currently working on. It is updated regularly. The projects are either written in R or Python. Some visualizations are made by using Tableau. Click on the projects to see full analysis and code.

Please contact me on [Linkedin](https://www.linkedin.com/in/feifan-lu-0b8b02142/) if you are looking to hire a data scientist.

## Projects:

### Climate Bet : Statistical View of Global Warming

**Keywords (Global Warming, ARIMA, ETS, TBATS, Naïve Model, Time Series)**

I dived into the ["Climate Bet"](http://www.theclimatebet.com/) and looked at the statistical evidence for global warming – a primarily scientific, fact-based view on the situation.

* Obtain the data from [NASA](https://data.giss.nasa.gov/gistemp/) and [UK MET Office](https://crudata.uea.ac.uk/cru/data/temperature/). Mr.Armstrong used NASA data for his analysis. Mr.Gore's team used UK MET data for their analysis.

* Apply time series analysis and train six models on NASA data and seven models on UK MET data.

* Utilize the rolling window cross-validation to find the best model for each dataset.

* Train the two best models on the pre-2007 data and use them to make predictions. Then make the naïve model forecast of constant temperature per [Mr. Armstrong's method](http://www.kestencgreen.com/G&A-Skyfall.pdf)  and use it as a benchmark model to compare with my best two models using the actual temperatures for 2007-2017 (a period of the bet).

* Repeat the same analyses starting in the year 1999 with 10- and 20-year time-intervals

* Justify the outcome and identify the flaws in UK MET dataset.

<img src="https://github.com/FeifanLu/Climate_bet/blob/main/Climate_bet/Results.png" width="800" length="600">

