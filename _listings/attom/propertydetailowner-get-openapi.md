---
swagger: "2.0"
x-collection-name: ATTOM
x-complete: 0
info:
  title: Attom Data Solutions API Returns property details owner based on an ID.
  description: Get property details owner based on its Onboard property ID.
  version: 1.0.0
host: search.onboard-apis.com
basePath: /communityapi/v2.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /property/detail:
    get:
      summary: Returns property details based on an ID.
      description: Get property details based on its Onboard property ID.
      operationId: propertyDetails
      x-api-path-slug: propertydetail-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: query
        name: address
        description: The mailing address
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: id
        description: property id
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Property
      - Details
      - Based
      - "On"
      - ID
  /school/detail:
    get:
      summary: Return details about a particular school.
      description: Search by school ID to return all of the available details about
        a school
      operationId: propertyDetails
      x-api-path-slug: schooldetail-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: id
        description: school id
      responses:
        200:
          description: OK
      tags:
      - Return
      - Details
      - About
      - Particular
      - School
  /school/districtdetail:
    get:
      summary: Return details about a particular school district.
      description: Search by district number to return all of the available details
        about a school district
      operationId: propertySchoolDistrictDetail
      x-api-path-slug: schooldistrictdetail-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: id
        description: district number
      responses:
        200:
          description: OK
      tags:
      - Return
      - Details
      - About
      - Particular
      - School
      - District
  /property/detailmortgage:
    get:
      summary: Returns property details mortgage based on ID.
      description: Get property details mortgage based on its Onboard property ID.
      operationId: propertyDetailsMortage
      x-api-path-slug: propertydetailmortgage-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: query
        name: address1
        description: The first line of the mailing address
      - in: query
        name: address2
        description: The second line of the mailing address
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: id
        description: property id
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Property
      - Details
      - Mortgage
      - Based
      - "On"
      - ID
  /property/detailowner:
    get:
      summary: Returns property details owner based on an ID.
      description: Get property details owner based on its Onboard property ID.
      operationId: propertyDetailsOwner
      x-api-path-slug: propertydetailowner-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: query
        name: address1
        description: The first line of the mailing address
      - in: query
        name: address2
        description: The second line of the mailing address
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: id
        description: property id
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Property
      - Details
      - Owner
      - Based
      - "On"
      - ID
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