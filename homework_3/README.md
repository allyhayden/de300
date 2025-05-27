# Homework 3 - Ally Hayden

## How to Run

1: Run in Jupyter Notebook
Open `ajh6975_hw3_de300.ipynb` in Jupyter Notebook and run all cells.

2: Run in Docker

```bash
docker build -t hw3 .
docker run -p 8888:8888 -v $(pwd):/home/jovyan/work hw3
