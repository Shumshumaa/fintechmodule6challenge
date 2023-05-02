# Proptech Opportunity Analysis


This opportunity analysis is for an instant one-click service for people to buy properties and rent them. The analysis is in the jupyter notebook included and shows visualizations of aggregation, and geospatial analysis that's interacrtive, to find properties in the San Fransico market that are viable investment opportunities.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For data manipulation and analysis.
* [hvplot](https://hvplot.holoviz.org/) - For interactive user prompts and dialogs
* [pathlib](https://docs.python.org/3/library/pathlib.html) - To provide for an easier method to interact with the filesystem no matter what the operating system is.
* [warnings](https://github.com/python/cpython/blob/3.11/Lib/warnings.py) - The warnings filter controls whether warnings are ignored, displayed, or turned into errors (raising an exception).


---

## Installation Guide

Before running the application first install the following dependencies.

``` pyviz
  conda install -c pyviz hvplot geoviews
```

---

## Analysis

The idea to buy and rent seems generally a good idea as rent growth prices have rarely slowed down over the 6 year time period observed, however the one click strategy may be risky as sales price/sqft vary over different periods due to various economic, social and political factors. 

I would recommend looking into the Anza Vista neighborhood for buy and rent opportunities as the sales price/sqft are trending downwards but there there is still a continuous and steady growth in rent prices.

---

## Contributors

Brought to you by PShum Loan Consulting

---

## License

MIT