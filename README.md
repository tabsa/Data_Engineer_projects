# Data_Engineer_projects
I use this repository to implement guides and/or my own projects on SQL database and data engineers in order to get familiar with different modules in this field.

# Project structure
```
├── data/                 # Sample datasets or generated data
├── notebooks/            # Jupyter notebooks with examples
├── scripts/              # Python scripts for ETL pipelines, or automation
├── tests/                # Unit tests using pytest
├── pyproject.toml        # Poetry environment configuration file
├── README.md             # Project description and setup instructions
```

## Usage
I use `poetry` to python environment tool, therefore you find the `pyproject.toml` with the necessary packages to run the `scripts/notebooks` of this repo. Therefore, you should install the python environment on your local setup as follow:
```bash
poetry install
```
Then, you are good to start using this repo code.

## Projects and tutorials
I have followed some tutorials and open-source documentation to get familiar with packages and tools in this topic. I would like to give credit to the authors of such documentation that supported my learning on SQL database and data engineer.

### DuckDB on python
I have followed the [duckdb guide](https://medium.com/@anshubantra/using-duckdb-in-python-a-comprehensive-guide-d14bc0b06546) pusblished in medium at _September 2024_ that resulted in the [example notebook](/notebooks/guide_on_duckdb.ipynb).


