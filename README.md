# ml-problems

## Overview

A repository consisting of 4 ML problems:

- Abalone age classification
- Classifying the number of shares for a given news article
  - The former two problems were made into classification problems by binning the continuous range of values into a set of bins.
- Classifying fetal heart rate (FHR) signals into 10 types (calm sleep, REM sleep, etc.).
- Predicting house pricing, using regression models, according to features that describe a given house.

Details about the dataset processing, ML models used, and comparison of results is shown in the [project document](./Assignment%201/Group%201%20-%20ML%20Problems%20on%20Abalone%2C%20Online%20News%20Popularity%2C%20and%20Cardiotocography.pdf).

## Notes

Side note: it is recommended you paste the links of the notebook files to [nbviewer.org](https://nbviewer.org/), as it displays the plotly graphs done in the notebooks. 
<br><br>
Another side note: we could've written `fig.show("png")` instead of `fig.show()` for the [plotly images to be rendered in github](https://github.com/plotly/plotly.py/issues/931#:~:text=Jul%2017%2C%202020-,Yes%2C%20check%20out%20the%20notebook%20I%20mentioned%20above%3A%20https%3A//github.com/nicolaskruchten/plotly_img_test/blob/master/Untitled.ipynb%20you%20just%20call%20fig.show(%22png%22)%20or%20fig.show(%22svg%22),-%F0%9F%91%8D)
, but that would've made it non-interactive, and we don't want that to happen :]
