# Q Search

The Q Search endpoint allows you to query the catalogue programmatically.  

Search by:
- Keyword - https://antcat.antarcticanz.govt.nz/geonetwork/srv/eng/q?any=K085A  
- Records carrying data: https://antcat.antarcticanz.govt.nz/geonetwork/srv/eng/q?download=true  
- Records carrying data and contain "OCEAN" as keyword - https://antcat.antarcticanz.govt.nz/geonetwork/srv/eng/q?download=true&any=OCEAN  

Expose all Catalogue Records:  
- XML - https://antcat.antarcticanz.govt.nz/geonetwork/srv/eng/q?=*$fast=false  
- JSON - https://antcat.antarcticanz.govt.nz/geonetwork/srv/eng/q?=*&_content_type=json&fast=false