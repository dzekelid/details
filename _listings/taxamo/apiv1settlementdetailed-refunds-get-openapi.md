---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 0
info:
  title: Taxamo Detailed Refunds
  description: Detailed refunds.
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/settlement/detailed_refunds:
    get:
      summary: Detailed Refunds
      description: Detailed refunds.
      operationId: getDetailedRefunds
      x-api-path-slug: apiv1settlementdetailed-refunds-get
      parameters:
      - in: query
        name: country_codes
        description: Comma separated list of 2-letter country codes
      - in: query
        name: date_from
        description: Take only refunds issued at or after the date
      - in: query
        name: date_to
        description: Take only refunds issued at or before the date
      - in: query
        name: format
        description: Output format
      - in: query
        name: limit
        description: Limit (no more than 1000, defaults to 100)
      - in: query
        name: offset
        description: Offset
      responses:
        200:
          description: OK
      tags:
      - Detailed
      - Refunds
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