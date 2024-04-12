# Catalogue Service for the Web

The Catalogue Service for the Web (CSW) end point exposes the metadata records in in XML format using the OGC CSW protocol. This makes it possible for other data aggegators/systems/data products to access and use the metadata and assocaited data in our catalgoue. 

The CSW protocol is currently being used by the [data.govt.nz catalogue](https://catalogue.data.govt.nz/dataset/?_organization_limit=0&organization=antarctica-new-zealand) to harvest the catalogue's metadata records.

GeoNetwork's [CSW Documentation](https://docs.geonetwork-opensource.org/4.4/api/csw/) provides a detailed description of the endpoint.

Example:  
```text
# https://antcat.antarcticanz.govt.nz/geonetwork/srv/eng/csw?service=CSW&version=2.0.2&request=GetRecordById&id=ec3ea6f7-93ec-479e-934a-5db834f05646&ElementSetName=full&outputSchema=http://www.isotc211.org/2005/gmd
```
