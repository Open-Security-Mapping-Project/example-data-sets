# Example data sets for ICE detention facilities

This repository is for showing both data sources and examples of output from the
programs we are developing.

This shows input and output data from the _[ICE Detention Facilities Data Scraper
and Enricher](https://github.com/Open-Security-Mapping-Project/ice_detention_scraper)_,
a Python script managed by the [Open Security Mapping Project](https://github.com/Open-Security-Mapping-Project).

The ICE detention facility script scrapes ICE detention facility data from ICE.gov and enriches it
with information from [Wikipedia](https://en.wikipedia.org), [Wikidata](https://wikidata.org), and
[OpenStreetMap](https://openstreetmap.org).

## Contents

* ice_detention_facilities_enriched-debugmode-aug-25-2025.csv - this is an output of 
the ICE detention scraper program from August 25 2025. It is set with all debug modes
enabled. Note that a lot of results in for example Wikidata.org are incorrect.
* ice-detention-facilities-extracted-aug-23-2025.json - the source for the data processed 
above. (A similar version is inside the ICE detention scraper program, in data_loader.py) 
Please note this was automatically extracted by an LLM AI from ICE.gov and has not been 
verified exhaustively, but it appears to be OK on spot checks. 

More data sources and examples may be added to this repository.

## Credits

These files were gathered and organized by Dan Feidt (@hongpong).

## License

Creative Commons Zero - Public Domain. See License.txt
