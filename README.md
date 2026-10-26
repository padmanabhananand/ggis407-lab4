# GGIS 407 – Lab 4: Geospatial Python Libraries (Fiona, Pandas and GeoPandas)

Two Jupyter notebooks for GGIS 407 (University of Illinois Urbana-Champaign), set up to run on the
[I-GUIDE JupyterHub](https://jupyter.i-guide.io) with the `iguide` kernel.

| Notebook | Covers |
| --- | --- |
| `Lab4_Fiona_and_Pandas.ipynb` | Reading vector data with Fiona; Pandas `Series` and `DataFrame` basics, selection and simple plots |
| `Lab4_GeoPandas.ipynb` | GeoDataFrames, plotting and choropleth maps, spatial operations, reprojection, dissolve, attribute and spatial joins |

## Data

- `data/nybb/`: New York City borough boundaries (NYC Department of City Planning), from the sample data
  that used to ship with [GeoPandas](https://github.com/geopandas/geopandas), reprojected to WGS 84 (EPSG:4326).
- `data/naturalearth_lowres/` and `data/naturalearth_cities/`: country boundaries and major cities from
  [Natural Earth](https://www.naturalearthdata.com/) (public domain), as previously bundled with GeoPandas.
- `data/us_cities.zip`: the 1,000 largest U.S. cities with 2013 Census Bureau population estimates, from
  [plotly/datasets](https://github.com/plotly/datasets) (`us-cities-top-1k.csv`), saved as a zipped shapefile.

Adapted by Anand Padmanabhan from earlier GGIS 407 course notebooks on CyberGISX.
