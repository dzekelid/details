---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Intelligent Mapping Return map details
  description: |-
    For the specified map identifier, returns the map properties and an
    array of the associated layers. For each layer, the identifier, name and
    Uniform Resource Identifier (URI) are returned.
  version: 1.0.0
host: insights-api.data-services.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/proxy/signature/details:
    post:
      summary: Post Proxy Signature Details
      description: Post proxy signature details.
      operationId: postV1ProxySignatureDetails
      x-api-path-slug: v1proxysignaturedetails-post
      parameters:
      - in: header
        name: Authorization
        description: token
      - in: header
        name: Predix-Zone-Id
        description: serviceInstanceId
      - in: body
        name: request
        description: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Signature
      - Details
  /v1/maps/{mapId}:
    get:
      summary: Return map details
      description: |-
        For the specified map identifier, returns the map properties and an
        array of the associated layers. For each layer, the identifier, name and
        Uniform Resource Identifier (URI) are returned.
      operationId: for-the-specified-map-identifier-returns-the-map-properties-and-anarray-of-the-associated-layers-for
      x-api-path-slug: v1mapsmapid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Return
      - Map
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