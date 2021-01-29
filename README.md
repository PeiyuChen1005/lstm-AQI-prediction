# LSTM AQI Prediction

### :book: Introduction

The air quality index (AQI) presents six pollutants, including sulfur dioxide, nitrogen dioxide, PM10, PM2.5, carbon monoxide and ozone, with unified evaluation standards. Air quality index is the data used to quantitatively describe air quality. It describes the degree of air pollution and its impact on health.

Air quality tends to fluctuate periodically. For example, in northern cities with heating demand, the ambient air quality index will increase every winter. Air quality is often related to recent activities. If the air quality is poor for several consecutive days, the next day's air quality will not be particularly good. The ability to predict the air quality index will help us make more reasonable plans in travel, sports and so on.

### :earth_asia: Environment

![](https://img.shields.io/badge/Python-3.7.9-green)![](https://img.shields.io/badge/Pytorch-1.6.0-yellow)

### :oil_drum: Dataset

The dataset comes from crawling data from a [weather website](http://www.tianqihoubao.com/aqi/)

### :stars: Statistical analysis

* AQI/AQI rank-city

![](https://github.com/PeiyuChen1005/lstm-AQI-prediction/blob/main/imgs/AQI_linechart.png?raw=true)

* best /worst air quality days

![](https://github.com/PeiyuChen1005/lstm-AQI-prediction/blob/main/imgs/AQI_barchart.png?raw=true)

* analysis of pollutant composition

![](https://github.com/PeiyuChen1005/lstm-AQI-prediction/blob/main/imgs/AQI_box.png?raw=true)

* heatmap

![](https://github.com/PeiyuChen1005/lstm-AQI-prediction/blob/main/imgs/heatmap.png?raw=true)

### :m: Model

```
RNN(
  (lstm): LSTM(30, 32, num_layers=4)
  (out): Linear(in_features=32, out_features=1, bias=True)
)
```

