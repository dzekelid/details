swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /references/seatdetails/{aircraftCode}/{cabinCode}:
    get:
      summary: Seat Details
      description: A description of all available seat details by aircraft type. You
        can retrieve the full set or details for a particular aircraft type.
      operationId: references.seatdetails.aircraftCode.cabinCode.get
      x-api-path-slug: referencesseatdetailsaircraftcodecabincode-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: aircraftCode
        description: Aircraft type
      - in: path
        name: cabinCode
        description: 'Cabin class: M, E, C, F (Acceptable values are: , M, E, C, F)'
      - in: query
        name: lang
        description: 2-letter ISO 3166-1 language code
      responses:
        200:
          description: OK
      tags:
      - Seat
      - Details