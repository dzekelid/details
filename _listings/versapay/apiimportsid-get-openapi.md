---
swagger: "2.0"
x-collection-name: VersaPay
x-complete: 0
info:
  title: VersaPay View Batch Details
  description: View batch details.
  contact:
    name: VersaPay Support
    url: https://www.versapay.com/support
    email: support@versapay.com
  version: 1.0.0
host: secure.versapay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/imports/{id}:
    get:
      summary: View Batch Details
      description: View batch details.
      operationId: viewBatchDetail
      x-api-path-slug: apiimportsid-get
      parameters:
      - in: path
        name: id
        description: The import batch identifier
      responses:
        200:
          description: OK
      tags:
      - View
      - Batch
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