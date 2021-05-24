# Stock market analysis during Covid-19
*Work in progress

Contents:
1. Project overview
2. Methodology
3. Code examples (including notebooks)

# Project overview

The Covid-19 pandemic had severe impacts on stock markets. It would be informative to identify the trends of a chosen industry and validate the claims/forecasts of different analysts and agencies. Through public data from yahoo finance, stock market data can be obtained to identify these trends. Also, through qualitative research on various agencies such as Morningstar, their claims can be validated with data. An overall stock price trend report of a chosen industry can be used as a general guide for future pandemics and financial crises.

# Methodology

Please refer to /docs

# Code, Notebook examples

Please refer to /notebooks

# Datasets

Please upload data to /data

Take note of privacy and copyrights.

# Statis resources

For storing static resources such as images, graphs etc

![](res/github_mark.png)

Please upload to /res

# Create new environment

install [miniconda](https://docs.conda.io/en/latest/miniconda.html)
and create new virtual environment

create new environment, replace ```dss``` with the env name
```bash
conda create -n dss python==3.9
```

activate the new environment
```bash
conda activate dss
```

install essential packages
```bash
pip install -r requirements.txt
```


# Reproducing the codes

Please include requirements.txt
```python
conda list --export > requirements.txt
```

