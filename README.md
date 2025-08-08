# egdata.fastbioclim

This package provides example data for the [`fastbioclim`](https://github.com/gepinillab/fastbioclim) R package.

The data is intended for demonstration and testing purposes only.

## Installation

```r
# install.packages("remotes")
remotes::install_github("gepinillab/egdata.fastbioclim")
```

# Data Source
The data included in this package is a derivative of the CHELSA V2.1 (Climatologies at high resolution for the earth’s land surface areas) dataset.
Original Source: https://chelsa-climate.org/
Citation:
* Karger, D.N., Conrad, O., Böhner, J., Kawohl, T., Kreft, H., Soria-Auza, R.W., Zimmermann, N.E., Linder, H.P. & Kessler, M. (2017) Climatologies at high resolution for the earth’s land surface areas. Scientific Data. 4:170122.
* 
Modifications: The original global data has been cropped to a smaller geographical area to reduce its size for example usage.

# License
The original CHELSA data is based on ERA5 which is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).
In accordance with these terms, the data in this package is also provided under the CC BY 4.0 license.