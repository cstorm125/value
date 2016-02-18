# How to Beat The Thai Market With Value Investing

## Executive Summary
We set out to find whether value investing strategy such as Joel Greenblatt's earning yields and Piotroski's F-score can actually beat the Thai stock market. The fundamental data are obtained from [Gurufocus](http://gurufocus.com) while the benchmark SET TRI is obtained from [Stock Exchange of Thailand](http://set.or.th). We perform support vector machine, boosted logistic regression and random forest classification based on the data, as well as a backtest to verify the models. Most our models perform better than a coin toss with random forest achieving the highest accuracy and sensitivity of 85.13% and 79.25% respectively (20.08% annual return).

See the analysis [here](http://cstorm125.github.io/value/). Codes in index.Rmd

## Codebook

The [codebook](http://cstorm125.github.io/value/codebook.html) demonstrates how fundamental data on Thai stocks from the [Gurufocus](http://gurufocus.com) and SET TRI from [Stock Exchange of Thailand](http://set.or.th) are transformed into the tidy format used in this [analysis](index.html).

## udf.csv

The ```tidy Thai stock dataset``` includes annual fundamental data of 463 Thai stocks in ```udf.csv``` and annual return of SET TRI in ```set_return.csv``` from 2002-2015. Monetary unit is THB.

## ```stocks``` Folder

Contains JSON format of all stocks in Thai market obtained from [Gurufocus](www.gurufocus.com).

## set_return.csv

Annual returns of SET TRI

## symbols.csv

List of symbols in Thai market
