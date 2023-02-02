# A Bayesian Approach to Unsupervised, Non-Intrusive Load Disaggregation

The [paper](https://www.mdpi.com/1424-8220/22/12/4481) "A Bayesian Approach to Unsupervised, Non-Intrusive Load Disaggregation" by Luca Massidda and Marino Marrocu was published in Sensors 2022, 22(12), 4481; https://doi.org/10.3390/s22124481 (14 June 2022)

### Project
[SENDER](https://www.sender-h2020.eu) is a project funded by the European Commission under the Horizon 2020 programme, which will develop the next generation of integrated energy service applications for demand-response management, tailored to the end-users' needs and preferences.

[![SENDER H2020 - Consumers at the core of the energy system](https://img.youtube.com/vi/VnnyQ3YskU0/0.jpg)](https://www.youtube.com/watch?v=VnnyQ3YskU0)

### Funding
This project has received funding from the European Union’s Horizon 2020 Research and Innovation programme under Grant Agreement No. 957755.

### Abstract

Estimating household energy use patterns and user consumption habits is a fundamental requirement for management and control techniques of demand response programs, leading to a growing interest in non-intrusive load disaggregation methods. In this work we propose a new methodology for disaggregating the electrical load of a household from low-frequency electrical consumption measurements obtained from a smart meter and contextual environmental information. The method proposed allows, with an unsupervised and non-intrusive approach, to separate loads into two components related to environmental conditions and occupants’ habits. We use a Bayesian approach, in which disaggregation is achieved by exploiting actual electrical load information to update the a priori estimate of user consumption habits, to obtain a probabilistic forecast with hourly resolution of the two components. We obtain a remarkably good accuracy for a benchmark dataset, higher than that obtained with other unsupervised methods and comparable to the results of supervised algorithms based on deep learning. The proposed procedure is of great application interest in that, from the knowledge of the time series of electricity consumption alone, it enables the identification of households from which it is possible to extract flexibility in energy demand and to realize the prediction of the respective load components.

### Keywords: energy disaggregation; non-intrusive load monitoring; NILM; Bayesian methods


### Reference:

```
@article{massidda2022bayesian,
  title={A bayesian approach to unsupervised, non-intrusive load disaggregation},
  author={Massidda, Luca and Marrocu, Marino},
  journal={Sensors},
  volume={22},
  number={12},
  pages={4481},
  year={2022},
  publisher={MDPI}
}
```

![Load disaggregation examples for different periods in a year, with different values of the outdoor mean temperature.
](sensors-22-04481-g005.png "Load disaggregation examples for different periods in a year, with different values of the outdoor mean temperature.
").

