---
swagger: "2.0"
x-collection-name: IBM Financial Crimes Insight for Insurance
x-complete: 0
info:
  title: IBM Financial Crimes Insight for Insurance API Retrieve details of a folio,
    by its internal id
  description: This method is used to retrieve the folio contents from the database
  version: 1.0.0
host: fcihost.ibm.com:9443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ibm/fci/platform/folio_management/folio/{id}:
    get:
      summary: Retrieve details of a folio, by its internal id
      description: This method is used to retrieve the folio contents from the database
      operationId: getFolioById
      x-api-path-slug: ibmfciplatformfolio-managementfolioid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
        description: Investigation folio to retrieve
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Details
      - Of
      - Folio
      - ""
      - By
      - Its
      - Internal
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