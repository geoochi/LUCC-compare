# LUCC Compare

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/szchixy/LUCC-compare/HEAD)

The jupyter file `LUCC_compare.ipynb` uses gdal and scikit-learn to read the truth value and classification value LUCC tif images and extracts the ValidData part for calculating accuracy, kappa, and classification report.

Case study area is Shenzhen city, with true value refers to `./img/source.tif`, classification result refers to `./img/result.tif`.

Each tiff file contains land use category value in {1, 2, 3, 4, 5}, with NoData = 0.
