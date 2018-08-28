swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
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
  /trips/89abe0bd-ea2e-44e5-b573-a8a346fdfb54:
    get:
      summary: Get Details of a Trip
      description: Get details of a trip.
      operationId: Trips89abe0bdEa2e44e5B573A8a346fdfb54Get
      x-api-path-slug: trips89abe0bdea2e44e5b573a8a346fdfb54-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Trip