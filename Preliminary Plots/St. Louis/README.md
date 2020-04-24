## Preliminary Plots for St. Louis

**Goal for 4/27:** make preliminary visualizations of food access, internet access, and unemployment in St. Louis
+ By geographical location
+ By demographic group (age / race)

Make a copy of `prelim_plots_stl.ipynb` to use as a template.

We will start with a different exploratory notebook per data source, and will combine later.


### Data sources used
[St. Louis Neighborhoods](https://www.stlouis-mo.gov/data/datasets/dataset.cfm?id=85)
+ Leo can you explain the file formats or add links to the documentation?

### Installation instructions

GP: This is what I used:
1. Install Anaconda/Miniconda.
2. Create a new environment: `conda create -n aspen python=3.6`
3. Activate that environment: `conda activate aspen`
4. Install dependencies: `conda install geopandas jupyter matplotlib descartes`

To run notebook:
1. Open Anaconda prompt
2. `conda activate aspen`
3. `cd` to the github folder
4. `jupyter notebook`


### Github usage
1. Download Github Desktop
2. Clone repository from `pnuk23/aspen` (see File menu)
3. Change the `Current Branch` to one with your name!
4. Commit your changes to **your branch** NOT master
    + please comment so we know what you changed/did
5. Create pull request when code is ready to be shared (see Branch Menu)


### Useful links
[Info about Shapefiles](https://www.earthdatascience.org/workshops/gis-open-source-python/intro-vector-data-python/)
[Python open-source GIS tools](https://automating-gis-processes.github.io/CSC18/lessons/L1/Intro-Python-GIS.html)
