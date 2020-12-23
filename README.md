# ozone-time-series

A mini app for filtering through a large dataset of time series data

## Requirements

* Python 3.6 or higher

In a command prompt:

```bash
#clone repo to the desired directory
git clone https://github.com/ricerb/ozone-time-series.git
cd ozone-time-series

#install requirements
pip install -r ./requirements.txt

#enable widgets
jupyter nbextension enable --py --sys-prefix widgetsnbextension
```

## Run the jupyter notebook

* Add the .pkl data file to the "ozone-time-series" folder

In a command prompt:

```bash
cd ozone-time-series

#launch jupyter
jupyter-notebook
```
Jupyter navigator should open in browser. Open "data explorer notebook.ipynb".
