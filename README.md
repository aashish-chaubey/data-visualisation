# Data Visulization Learning in Python
*A self taught tutorial for myself *taking help from various sources*

1. Plotting data on a geospatial map making use of `bokeh` and `geopandas`
    In this example, I plot the obesity of all the countries over the years from 1975 through 2016.
    The data file `obesity.csv` is attached in the repository. This is the data file I used to plot on the map
    I've also attached the shapefile which was downloaded from [here](https://www.naturalearthdata.com/https://www.naturalearthdata.com/). For this example, I've used the `ne_110m_admin_0_countries.shp` file. I've also attached this file in the notbook.

    Also, it is important to note that this file when served with jupter notebook, does not slide through the years and an alternative to this is to serve this visualization with `bokeh` using `bokeh serve --show worldplot.ipynb`