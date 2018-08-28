---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get warehouse location details
  description: Gets warehouse location details
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/newsletters/folders/{folderId}:
    get:
      summary: List details of a folder
      description: Lists details of a folder. The ID of the folder must be specified.
      operationId: getRestNewslettersFoldersFolder
      x-api-path-slug: restnewslettersfoldersfolderid-get
      parameters:
      - in: path
        name: folderId
      responses:
        200:
          description: OK
      tags:
      - List
      - Details
      - Of
      - Folder
  /rest/newsletters/{entryId}:
    get:
      summary: List details of an entry
      description: Lists details of an entry. The ID of the entry must be specified.
      operationId: getRestNewslettersEntry
      x-api-path-slug: restnewslettersentryid-get
      parameters:
      - in: path
        name: entryId
      responses:
        200:
          description: OK
      tags:
      - List
      - Details
      - Of
      - Entry
  /rest/warehouses/locations/details:
    get:
      summary: Get warehouse location details
      description: Gets warehouse location details
      operationId: getRestWarehousesLocationsDetails
      x-api-path-slug: restwarehouseslocationsdetails-get
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Details
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---