# Usage
This repository using for data analysis implementation

ARIMA Tools
===========

Author: Ignacio Laguna
Contact: ilagunap@gmail.com

Implementation of time series forecasting using ARIMA models in C++.
The library provides an API for forecasting pre-created models - it does not
provide methods for training the models (this can be easily done using R).

Building
--------
$ ./configure --prefix=/path/to/install
$ make && make install

This will install a shared library libarimatools.so that can be linked with
your C++ application to forecast future observations.
