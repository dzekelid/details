---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 1
info:
  title: Expedia
  description: expedia-mobile-api-documentation--brfont-colorblue-note-in-case-of-authorization-exception-just-a-hrefstaticmobileswaggeruiusersigninusersigninafont
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/flight/details:
    get:
      summary: Details
      description: Mobile API Flight Details Operation
      operationId: flights-details
      x-api-path-slug: apiflightdetails-get
      parameters:
      - in: query
        name: arrivalAirport
        description: The three letter airport code for where the customer is going
      - in: query
        name: childTravelerAge
        description: childTravelerAge represents the age of a single child traveler
      - in: query
        name: departureAirport
        description: The three letter airport code for where the customer is leaving
          from
      - in: query
        name: departureDate
        description: Date the customer wants to leave for their flight on, in ISO
          format
      - in: query
        name: infantSeatingInLap
        description: Set to true if infant(s) are without a reserved seat (in an adults
          lap)
      - in: query
        name: numberOfAdultTravelers
        description: 'Number of Adult Travelers (Default: 1)'
      - in: query
        name: productKey
        description: A productKey, obtained from a call to flight search, within the
          past 20 minutes
      - in: query
        name: returnDate
        description: Date the customer wants to return on
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
---