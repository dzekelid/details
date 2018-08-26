---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Get Vehicle Details
  description: Get vehicle details.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /vehicles/aa44769b-3c0a-4662-9bad-25481cf5198f:
    get:
      summary: Get Vehicle Details
      description: Get vehicle details.
      operationId: VehiclesAa44769b3c0a46629bad25481cf5198fGet
      x-api-path-slug: vehiclesaa44769b3c0a46629bad25481cf5198f-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Vehicle
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