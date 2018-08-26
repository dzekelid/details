---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/art/{unique}/details:
    get:
      summary: Get Art Unique Details
      description: Get art unique details.
      operationId: getApiV1ArtUniqueDetails
      x-api-path-slug: apiv1artuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Art
      - Unique
      - Details
  /api/v1/event/{id}/details:
    get:
      summary: Get Event Details
      description: Get event details.
      operationId: getApiV1EventDetails
      x-api-path-slug: apiv1eventiddetails-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Event
      - Details
  /api/v1/event/{unique}/details:
    get:
      summary: Get Event Unique Details
      description: Get event unique details.
      operationId: getApiV1EventUniqueDetails
      x-api-path-slug: apiv1eventuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Event
      - Unique
      - Details
  /api/v1/gigme/artist/{unique}/details:
    get:
      summary: Get Gigme Artist Unique Details
      description: Get gigme artist unique details.
      operationId: getApiV1GigmeArtistUniqueDetails
      x-api-path-slug: apiv1gigmeartistuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Unique
      - Details
  /api/v1/gigme/event/{id}/details:
    get:
      summary: Get Gigme Event Details
      description: Get gigme event details.
      operationId: getApiV1GigmeEventDetails
      x-api-path-slug: apiv1gigmeeventiddetails-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Event
      - Details
  /api/v1/gigme/event/{unique}/details:
    get:
      summary: Get Gigme Event Unique Details
      description: Get gigme event unique details.
      operationId: getApiV1GigmeEventUniqueDetails
      x-api-path-slug: apiv1gigmeeventuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Event
      - Unique
      - Details
---