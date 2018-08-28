swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
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
  /v1/maps/{mapId}/layers/{layerId}:
    get:
      summary: Return layer details
      description: |-
        For the layer identified by the map and layer identifiers, returns the
        layer details (identifier, name, Uniform Resource Identifier (URI), and
        visibility).
      operationId: for-the-layer-identified-by-the-map-and-layer-identifiers-returns-thelayer-details-identifier-name-u
      x-api-path-slug: v1mapsmapidlayerslayerid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Return
      - Layer
      - Details
  /v1/tenant/{tenantName}/service/{serviceName}:
    get:
      summary: Retrieve service details
      description: Retrieve service details.
      operationId: getServiceDetailsUsingGET
      x-api-path-slug: v1tenanttenantnameserviceservicename-get
      parameters:
      - in: header
        name: Predix-Zone-Id
      - in: path
        name: serviceName
        description: serviceName
      - in: path
        name: tenantName
        description: tenantName
      responses:
        200:
          description: Successful response
      tags:
      - Retrieve
      - Service
      - Details