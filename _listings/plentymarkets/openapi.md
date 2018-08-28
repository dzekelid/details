swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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