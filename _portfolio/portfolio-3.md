---
title: "BTA Deep Hole Drilling"
excerpt: "The purpose of this project is to detect chattering and raise an alarm so that the drilling process is stopped"
collection: portfolio
---

Chattering is really a big problem when it comes to drilling. To prevent that shattering it should be detected before hand, In this project the data was provided by the Professor of TU Dortmund. After intial descriptive analysis was then performed to identify trends and patterns within the data. Subsequently, change point detection was carried out to pinpoint transitions in the data, revealing that the majority of datasets exhibited a change in variance after the third change point. ACF plots were employed to identify seasonality before and after the change points. Additionally, periodograms were plotted to identify dominant frequencies in the sensor data, and spectrograms were used to observe the occurrence times of these frequencies. The project concluded with the proposal of an alarm system that can be triggered to halt the drilling process and prevent shattering. The code for this project can be found [here](https://github.com/farrukh-ahmed/Case-Studies---Project-2)

Tech Used : Python, pandas, numpy, matplotlib, jupyternotebook
