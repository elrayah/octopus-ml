# octopus-ml
 
[![PyPI Latest Release](https://img.shields.io/pypi/v/octopus-ml.svg)](https://pypi.org/project/octopus-ml/)
[![License](https://img.shields.io/pypi/l/octopus-ml.svg)](https://github.com/gershonc//octopus-ml/blob/master/LICENSE)
[![Python Version](https://img.shields.io/pypi/pyversions/pandas-profiling)](https://pypi.org/project/octopus-ml/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)
[![Binder](https://mybinder.org/badge.svg)](https://hub.gke2.mybinder.org/user/gershonc-octopus-ml-k5of97xu/tree)
<!-- 
[![Code Coverage](https://codecov.io/gh/pandas-profiling/octopus-ml/branch/master/graph/badge.svg?token=gMptB4YUnF)](https://codecov.io/gh/octopus/octopus)
-->
Set of handy ML and data tools - from data exploration, visualization, pre-processing, hyper parameter tuning, modeling and all the way to final Ml model evaluation 
<img src="/images/octopus_know_your_data.png" width="350" height="450" />
## Installation
The module can be easily installed with pip:

```conslole
> pip install octopus-ml
```
https://pypi.org/project/octopus-ml/

This module depends on `Scikit-learn`, `numpy`, `pandas`, `light GBM` as defualt classifier. Optionally you can get also some nice visualisations if you have `seaborn` installed.



## Usage
The module contains ML and Data related methods:

```python
from octopus_ml import plot_imp, adjusted_classes,cv,cv_plot,roc_curve_plot, ...


```
