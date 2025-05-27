FROM jupyter/pyspark-notebook

USER root
RUN pip install pandas numpy

COPY . /home/jovyan/work
WORKDIR /home/jovyan/work
