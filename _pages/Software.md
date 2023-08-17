---
layout: archive
title: ""
permalink: /software/
author_profile: true
redirect_from:
  - /software
---


# Software
I create open-source Python statistical tools tailored for central banks, quants, economists, and financial professionals. These tools cater to financial modeling and forecasting needs, and they are conveniently accessible via GitHub and some are also hosted on PyPI, allowing effortless installation using pip.

**Disclaimer**: Reuse of these tools does not imply any endorsement of the research and/or product. Any research presented should not be reported as representing the views of the institutions I am currenlty or have been affiliated with.
{: .notice}


Model selection and combination for forecasts
=============================================

Overview
--------

`forecast_combine` is a Python library built upon the foundation of the sktime library, designed to simplify and streamline the process of forecasting and prediction model aggregation. It provides tools for aggregating predictions from multiple models, evaluating their performance, and visualizing the results. Whether you're working on time series forecasting, data analysis, or any other predictive modeling task, forecast_combine offers a convenient and efficient way to handle aggregation and comparison.

Key Features
------------
* **Model Aggregation**: Easily aggregate predictions from multiple models using various aggregation modes such as best model overall, best model per horizon, inverse score weighted average model, and more.
* **Out-of-Sample Evaluation**: Evaluate model performance using out-of-sample data and choose the best models based on user-defined performance metrics.
* **Visualization**: Visualize model performance, aggregated predictions, and prediction intervals with built-in plotting functions.
* **Flexibility**: Accommodate various aggregation strategies, forecast horizons, and performance metrics to cater to your specific use case.

Package Information
-------------------
* PyPI deployment  [forecast-combinae . PyPI](https://pypi.org/project/forecast-combine/). Easy installtion
```bash
pip install forecast_combine
```
* Seamless Integration of new features and bug fixes. Simply upgrade using the command
```bash
pip install --upgrade forecast_combine
```
* Comprehensive documentation, along with illustrative examples and interactive notebooks, enabling users to confidently utilize the tool independently. [Online Documentation](https://amineraboun.github.io/forecast/)
* We welcome contributions from the community! If you have suggestions, bug reports, or feature requests, please open an issue or submit a pull request. [Link to the Github repo](https://github.com/amineraboun/forecast)


Distributional GaRCH model to design VaR-based FX Interventions for Central Banks
=================================================================================

Overview
--------

`varfxi` is a Python module that extends the ARCH package by K. Sheppard, focusing on estimating conditional densities from various GaRCH models. It particularly aims to facilitate VaR-based interventions in the foreign exchange (FX) market for central banks. Practical usage examples and theoretical insights can be found on the [STI course website](https://amineraboun.github.io/STI_FX_Intervention/docs/index.html), showcasing its relevance in enhancing central banks risk management setup.

Key Features
------------ 
* **Out-of-Sample Evaluation**: Evaluate different GARCH models and density functions combinations out-of-sample data and choose the best model
* **Visualization**: Visualize model performance, Fan charts, conditional volatility and CDF with the recommended Rule-based FX Interventions for the central bank to adopt
* **Flexibility**: Accommodate various GARCH models, forecast horizons, exogenous variables inclusion and performance metrics to cater to your specific use case.

Package Information
-------------------
* PyPI deployment  [varfxi . PyPI](https://pypi.org/project/varfxi/). Easy installtion
```bash
pip install varfxi
```
* Seamless Integration of new features and bug fixes. Simply upgrade using the command
```bash
pip install --upgrade varfxi
```
* We welcome contributions from the community! If you have suggestions, bug reports, or feature requests, please open an issue or submit a pull request. [Link to the Github repo](https://github.com/romainlafarguette/varfxi)
    
    
