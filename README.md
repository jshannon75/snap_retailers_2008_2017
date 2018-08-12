# National database of SNAP authorized retailers, 2008-2017
This repository stores data on SNAP authorized retailers nationally from 2008-2017. Data are from the USDA, with records linked across years and all stores geocoded. An research rationale for these data, details on its construction, and a short descriptive analysis are [available here](https://jshannon75.github.io/snap_retailers_2008_2017/overview_paper).

Multiple files are available on this site:

* The main CSV file [with this link](https://github.com/jshannon75/snap_retailers_2008_2017/raw/master/data/snap_retailers_usda.csv). This includes a combined version of the listings provided by USDA with dummy variables for each year and geographic coordinates for all stores.

* An additional file with the state, county, census tracts, and metropolitan statistical areas of each store [is avilable here](https://github.com/jshannon75/snap_retailers_2008_2017/raw/master/data/snap_retailers_crosswalk.csv) and can be joined with the store id code. Right click and choose "Save link as" to download. 

* Metadata showing variable names are available [on this spreadsheet](https://github.com/jshannon75/snap_retailers_2008_2017/raw/master/data/snap_retailers_metadata.csv). 
* The data folder of this repo contains the original files provided by USDA, which show store listings for June 30 from 2008-2017. 

R scripts showing the data consolidation and editing process are also available in the home directory of the repo.
