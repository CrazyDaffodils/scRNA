FROM jupyter/datascience-notebook

RUN pip install --upgrade pip \
    && pip install datapackage \
    && pip install folium \
    && pip install --upgrade seaborn \
    && pip install geopandas \
    && pip install tensorflow

WORKDIR '/home/jovyan/work/code/'
