# Jupyter Notebook Copernicus Sentinel Data Analysis

Jupyter notebook with support for geospatial analyses. Everything that gives [Jupyter Notebook Scientific Python Stack](https://github.com/jupyter/docker-stacks/tree/master/scipy-notebook) and more:

* [GDAL](http://www.gdal.org/)
* [rasterio](https://mapbox.github.io/rasterio/)
* [Sentinel Hub](https://github.com/sentinel-hub/sentinelhub-py)

## Basic Use

The following command starts a container with the Notebook server listening for HTTP connections on port 8888 with a randomly generated authentication token configured. The current folder is mapped to the server.

```bash
docker run -it --rm -p 8888:8888 -v $PWD/:/home/jovyan krostir/jupyter-geo-sentinelhub
```

For all other options see [jupyter/docker-stacks](https://github.com/jupyter/docker-stacks).