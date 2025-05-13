# Homework 2: Ally Hayden

## How to Run

1. Launch JupyterLab from your EC2 Docker container.
2. Open `ajh_hw2.ipynb` inside the `homework2/` folder.
3. Ensure all required CSVs are present in this folder.
4. Step through each cell, top to bottom.

### Prerequisites

- DuckDB and Pandas for SQL analysis
- AWS Keyspaces credentials and SSL cert for Cassandra
- Python packages: `duckdb`, `boto3`, `cassandra-sigv4`, `pandas`, `uuid`

## Analysis Questions

### 1.
- Create a summary of type of drugs and their total amount used by ethnicity. Report the top usage in each ethnicity group.

### 2.
- Create a summary of procedures performed on patients by age groups (<=19, 20-49, 50-79, >80). Report the top three procedures, along with the name of the procedures, performed in each age group.

### 3. 
- How long do patients stay in the ICU? Is there a difference in the ICU length of stay among gender or ethnicity?


## Generative AI - the following questions were asked to ChatGPT

### 1.
- What’s the best way to join multiple MIMIC-III tables in DuckDB?

### 2.
- How do I upload files into my EC2 instance?
