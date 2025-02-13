`skchange` tutorial at Hydro Data Science Forum
============================================================

This tutorial is about [skchange] and [sktime].

`skchange` is a python library for fast change and anomaly detection in time series.

`skchange` is based on, and extends, `sktime`, the most widely used scikit-learn compatible framework library for learning with time series.

Both packages are maintained under permissive license, easily extensible by anyone, and interoperable with the python data science stack.
This workshop gives a hands-on introduction to the new joint detection interface developed in skchange and sktime, for detecting point anomalies, changepoints, and segment anomalies.

[skchange]: https://skchange.readthedocs.io/en/latest/
[sktime]: https://www.sktime.net

## :bulb: Description

The tutorial will give an introduction to the detection API in skchange and sktime, with a focus on unsupervised detection of segment anomalies and change points. The tutorial includes:

- An introduction to the different types of detection tasks for time series data:

    * Change detection
    * Segmentation
    * Point anomaly detection
    * Segment anomaly detection
    * Subset anomaly detection for multivariate data
- How to use `skchange` and `sktime` for these tasks
- Cost and score functions for anomaly and changepoint detectors

We invite anyone to get involved as a developer, user or supporter.

[clone]: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository
[conda]: https://docs.conda.io/en/latest/
[installation instructions]: https://www.sktime.net/en/latest/installation.html

## :floppy_disk: Installation

Here's how to run the notebooks locally using [python virtual environment].
This tutorial has only been tested on Windows using [VSCode].
Apologies if some details are missing for other setups.

[VSCode]: https://code.visualstudio.com/
[python virtual environment]: https://docs.python.org/3/tutorial/venv.html

### Clone the repository
```
git clone https://github.com/NorskRegnesentral/skchange-tutorial-hydro
```

### Create a python virtual environment
```
python -m venv .venv
```

### Activate your environment

Linux
```
source .venv/bin/activate
```
Windows
```
.venv/Scripts/activate
```

### Install the requirements
```sh
pip install -r requirements.txt
```

## :arrow_forward: Running the tutorial

1. Open the notebooks folder.
2. Run through the notebooks and cells in order.

    * When [VSCode] asks if you want to activate the `.venv` environment for Jupyter, click "Yes".


## :movie_camera: Other Tutorials

 - [Pydata Global 2024 - Anomaly detection, change detection and segmentation](
    https://github.com/sktime/sktime-tutorial-pydata-global-2024)
- [EuroSciPy 2024 - Hierarchical, global forecasting, foundation models, extensions and marketplace](https://github.com/sktime/sktime-workshop-euroscipy2024)

- [Pydata Global 2023 - General sktime introduction, new features 2023](https://github.com/sktime/sktime-tutorial-pydata-global-2023)

- [Europython 2023 - General sktime introduction, half-day workshop](https://github.com/sktime/sktime-tutorial-europython-2023)

- [PyCon Prague 2023 - Forecasting, Advanced Pipelines, Benchmarking](https://github.com/sktime/sktime-tutorial-pydata-global-2023)

- [Pydata Amsterdam 2023 - Probabilistic prediction, forecasting, evaluation](https://github.com/sktime/sktime-tutorial-pydata-Amsterdam-2023)

- [ODSC Europe 2023 - Forecasting, Pipelines, and ML Engineering](https://github.com/sktime/sktime-tutorial-ODSC-Europe-2023)

- [Pydata London 2023 - Time Series Classification, Regression, Distances & Kernels](https://github.com/sktime/sktime-tutorial-pydata-london-2023)

- [Pydata Berlin 2022 - Advanced Forecasting Tutorial](https://www.youtube.com/watch?v=4Rf9euAhjNc)

- [Pydata London 2022 - How to implement your own estimator in sktime](https://www.youtube.com/watch?v=S_3ewcvs_pg)

- [Pydata Global 2022 - Feature extraction, Pipelines, Tuning](https://github.com/sktime/sktime-tutorial-pydata-global-2022)


## :wave: How to contribute

If you're interested in contributing to `skchange` or `sktime`,
you can find out more how to get involved [here](https://www.sktime.net/en/latest/get_involved.html).

Any contributions are welcome, not just code!
