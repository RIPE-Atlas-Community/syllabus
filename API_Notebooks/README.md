# Jupiter notebook with RIPE Atlas API examples

## Installation prerequisites
   To use this notebook you need to have a modern browser, python2, Ipython([Jupiter](https://jupyter.org/)) notebook, and number of python modules.
   
   For new users it is advised to install [Anaconda](https://www.continuum.io/downloads)

## Ubuntu/Debian installation
  Prepare the system to run notebooks in the python virtualenv
  * `$ sudo apt-get update`
  * `$ sudo apt-get install python-pip python-virtualenv python-dev`
  * `$ sudo apt-get -y install ipython ipython-notebook`

## Set up and activate the new virtualenv in the python directory
 * `$ virtualenv python`
 * `$ . python/bin/activate`

## Install Python modules
 * `$ pip install jupyter`
 * `$ pip install sphinx ujson`
 * `$ pip install ripe.atlas.cousteau ripe.atlas.sagan`
 
 If you're having problems installing `ripe.atlas.sagan` please consult with the [sagan documentation](https://github.com/RIPE-NCC/ripe.atlas.sagan/blob/master/README.rst#troubleshooting)

## Run jupiter
 * `$ jupyter notebook`
 * in newly opened browser window upload atlas.ipynb and start experimenting!
