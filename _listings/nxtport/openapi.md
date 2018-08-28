swagger: "2.0"
x-collection-name: NxtPort
x-complete: 1
info:
  title: Portcall+ API (sandbox)
  description: portplus-api
  version: 1.0.0
host: api-sb.nxtport.eu
basePath: /PortCallPlus/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/locations/{id}:
    get:
      summary: Details
      description: Get details of 1 location.
      operationId: getApiV1Locations
      x-api-path-slug: apiv1locationsid-get
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: path
        name: id
        description: id of the location
      responses:
        200:
          description: OK
      tags:
      - Details