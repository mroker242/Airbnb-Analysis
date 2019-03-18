# Airbnb-Analysis

The following is an analysis of a dataset of Airbnb in Seattle.

## Table of Contents

<ul>
<li><a href="#Installation">Installation</a></li>
<li><a href="#Dependencies">Depenencies</a></li>
<li><a href="#Motivations">Motivations</a></li>
<li><a href="#File Descriptions">File Descriptions</a></li>
<li><a href="#User Guide">User Guide</a></li>
<li><a href="#licenses">Licenses</a></li>

</ul>

## Installation

This analysis requires:

### Dependencies

- Pandas 
- Numpy
- plotly
- Python 3

## Motivations

As an Airbnb host, there are a lot of factors which can contribute to getting persons to rent your home
or not. Some hosts are more successful than others, some make more profits than others. This analysis 
is to explore trends in the dataset and any key observations that may help with making profits or
be successful in renting your home.

## File Descriptions

- **calendar.csv**: contains data such as availability, dates, price
- **listings.csv**: contains every listing and has data such as bedrooms, bathrooms, host rating
- **Aibnb Seattle.ipynb** - jupyter notebook containing analysis of Seattle Airbnb

## User Guide

After installing the libraries in the dependencies section, you can simply run all of the cells in the notebook.
This should generate all of the plots here.

## Licenses

The source for the data is on kaggle [here] (https://www.kaggle.com/airbnb/seattle).  Also, a kernel that helped with some of
their observations on kaggle was [here] (https://www.kaggle.com/jeremywickman/sleeping-in-seattle-predicting-airbnb-ratings).
Finally, credit to [Practical Business Python](https://pbpython.com/categorical-encoding.html) for a good guide on handling categorical
values.
