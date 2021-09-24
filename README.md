# GRANDMA/Kilonova-catcher: 1st campaign

This repository hosts the [ZTF](https://www.ztf.caltech.edu/) alert data processed by [Fink](https://fink-broker.org) and used in the first phase of the [GRANDMA/Kilonova-catcher](https://grandma-kilonovacatcher.lal.in2p3.fr/) campaign (2021/04/01 to 2021/08/31). You will find 4 notebooks:

- [Introduction](introduction.ipynb): Describe the basics to manipulate alert data
- [KN-LC filter](KN-LC_filter.ipynb): Candidates from the filter using the kilonova classifier
- [KN-Mangrove filter](KN-Mangrove_filter.ipynb): Candidates from the filter using a crossmatch with Mangrove galaxies
- [KN-rate-based filter](KN-rate-based_filter.ipynb): Candidates from the rate-based filter

Alert data are located under [data](data/). Note that during this period, ZTF sent XX alerts, and Fink processed YY alerts that pass the quality cuts.
