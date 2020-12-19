# Readme
# Facebook Stock Price Prediction & Trading Strategy Project
#   
#  

### Tong Yang 001302930
### Minghao Ru 001088106
----
#### Portfolio github link:https://github.com/yangtong951019/INFO7390_Final_Project


[![N|Solid](https://assets.weforum.org/article/image/large_F1lpSz-GPutLjMAb4MPFZwTgamzGLZRRpB8CSlOFNwM.jpg)]

This documentation is try to show what's contain in different file in this zip file.

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Our project is a Facebook stock price prediction model.

 There are four main parts in our project. In the first part, we analyze the daily returns and log daily returns of Facebook’s stock price by statistical features, then we use Karman Filter & Garch models to do a regression on the returns. In the second part, we use several models includes Fama French 3 Factors, SVM bootstrap & ARIMA etc. to predict the Facebook’s stock close price. We compare the prediction result to get a best model. Then we use Random Forest to combine each model to give the most accurate prediction. In the last part, we analyze Trading Strategies like MACD Signal Crossovers and Bollinger Band to give a proper investment advice for new investors. 
Key word: Stock Price daily return, Close price, Prediction, Trading Strategies. 


# Features

  -  Get the data of Facebook stock price.
  -  Use Karman Filter & Garch models to do a regression on the returns.
  -  use several models includes Fama French 3 Factors, SVM bootstrap & ARIMA etc. to predict the Facebook’s stock close price.
  -  Combine every model to give the most accurate prediction.





> Facebook was founded in 2004, and went public in 2012. The code for Trading on NASDAQ is ‘FB’. Facebook’s Market Cap is $781.80B on Dec. 17, 2020. Revenue for third quarter 2020 is $21.22B. Acquisition of Facebook includes Oculus, Instagram, Whatsapp & GIPHY etc. 

Bingo!

# Guide of our portfolio

### Report File：

It include our 'Final Report.pdf': It's a report of the whole project, containing output of code and prediction results. It also shows the guides of running the project.





# Tech and Concept

We use a number of open source projects to work properly:

* [Commons Math] - The important package we use to do the math work
* [.csv] - The result's format we chosse




# Usage


Install the dependencies and devDependencies and start the server.

For dealing with the data...
```sh
$ import matplotlib.pyplot as plt
$ import numpy as np
$ import pandas as pd
$ from scipy import stats
$ import seaborn as sns
$ import scipy.stats as ss
$ from pandas_datareader import DataReader
$ from datetime import datetime
```

For processing the data work...

```sh
$ import tweepy
$ import json
$ import datetime
$ import warnings
```



# Development


Core package:
```sh
$ import matplotlib.pyplot as plt
$ from sklearn.svm import SVR  
$ from EMA_Bootstrap import ema_bootstrap
$ from MACD_bootstrap import bootstrap
$ from SVM_bootstrap import svm_bstr
$ from Autoregression_Bootstrap import AR_bootstrap
```

Imports:
```sh
$ import pandas as pd
$ import re
$ import urllib.request
$ import tweepy
$ import json
$ import datetime
$ import warnings
```




### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


## Todos in future

 - Use models to predict the stock price and plot it
 - Use the our learning models to predict more stock model we want
...

## Professionalism
50% Minghao Ru

50% Tong Yang

## Licensing
Copyright <2020> Minghao Ru, Tong Yang

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
Licenses
----




**Thank you! Have a nice day and stay safe!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)



   [df1]: <http://daringfireball.net/projects/markdown/>
   [.csv]: <https://en.wikipedia.org/wiki/Comma-separated_values>
   [Commons Math]: <http://commons.apache.org/proper/commons-math/index.html>
   [Requests]: <https://realpython.com/python-requests/>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
