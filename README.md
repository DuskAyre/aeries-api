# README
New incarnation of an Aeries API (to go along with the districts new version of Aeries). Currently, only finds gradebook. Please run using aeries-cli, which can be found at DavidHarrison/aeries-cli. However, it is possible to run by adding a few lines to Main.py to call get() on execution.

## Dependencies
- selenium (from pypi)
    - phantomjs (install through the operating system)
- beautifulsoup4 (from pypi)
- dateutil (from pypi)

## TODO
- **clean up code**
- check for edge case bugs
- decide on how to deal with blank fields (None/null type, '' string, 'blank' string etc.)

## Ideally
- generalized parsing
	- give the parser a model (like a regex statement) with defined variable names
        - Things already exist for this (e.g. Scrapely)
	- parser outputs dictionary with variable names from model
