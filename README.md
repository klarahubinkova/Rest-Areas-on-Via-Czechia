# Rest Areas on Via Czechia
An exam project for Geospatial Data Science course. It investigates the distribution of rest areas around the Via Czechia trail based on data from OpenStreetMaps with focus on the coverage of shelters and benches.

## Instalation
It is recommended to create a virtual environment and execute the program in the environment.
All dependencies needed for proper run are specified in the `requirements.txt` file
```sh
# Create a virtual environment
python -m venv .venv

# Activate it
.venv\Scripts\activate

# Upgrade pip inside the venv (optional but recommended)
(.venv) pip install --upgrade pip

# Install your dependencies
(.venv) pip install -r requirements.txt
```

## Execution
The code can be found in the `main.ipynb` Jupyter Notebook.
After proper run of all the cells, new version of `locations.html`, `density.html` and `distant_sections.html` files is created.
These files can be accessed directly or through `index.html` file that contains links to all the files.

## Prototype
The prototype can be also accessed [online](https://klarahubinkova.github.io/Rest-Areas-on-Via-Czechia/).
