---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 0
info:
  title: hetras Hotel API Version 0 Get the details of the hotel with the speccified
    hotel id.
  version: v0
  description: Get the details of the hotel with the speccified hotel id..
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}:
    get:
      summary: Get the details of the hotel with the speccified hotel id.
      description: Get the details of the hotel with the speccified hotel id..
      operationId: Hotels_GetHotel
      x-api-path-slug: apihotelv0hotelshotelid-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: hotelId
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Hotel
      - Speccified
      - Hotel
      - Id
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