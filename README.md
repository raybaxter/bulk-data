# bulk-data

GPO provides the capability to download XML in bulk for select collections from https://www.govinfo.gov/bulkdata. 

Please see the User Guides within this repository for more information on how to make use of the XML data for the available collections.
 
## govinfo bulk data
The **govinfo** team has migrated bulk data functionality to govinfo. 

https://www.govinfo.gov/bulkdata

### XML and JSON endpoints
New in govinfo, you can add /xml or /json to any govinfo bulkdata link to receive the listing in that format.

https://www.govinfo.gov/bulkdata/BILLS/115/1/hjres<br/>
XML: https://www.govinfo.gov/bulkdata/xml/BILLS/115/1/hjres<br/>
JSON: https://www.govinfo.gov/bulkdata/json/BILLS/115/1/hjres

#### Note
If crawling the xml and json endpoints programmatically, you should ensure that you set the appropriate accept headers in your request, or you may see a 406 response.
E.g for json - `Accept: application/json`



### Examples 

Federal Register Issues from September 2012: http://www.govinfo.gov/bulkdata/FR/2012/09

Code of Federal Regulations: http://www.govinfo.gov/bulkdata/CFR/

Bills back to the 113th Congress: http://www.govinfo.gov/bulkdata/BILLS




