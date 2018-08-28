swagger: "2.0"
x-collection-name: BBC
x-complete: 1
info:
  title: BBC Nitro
  description: bbc-nitro-is-the-bbcs-application-programming-interface-api-for-bbc-programmes-metadata-
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /programme_details:
    get:
      summary: Exposes programme information for a single pid
      description: Exposes programme information for a single pid
      operationId: listProgrammeDetails
      x-api-path-slug: programme-details-get
      parameters:
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: partner_pid
        description: Filter for programme information by partner PID
      - in: query
        name: pid
        description: Filter for programme information for the provided PID
      responses:
        200:
          description: OK
      tags:
      - Programme
      - Details